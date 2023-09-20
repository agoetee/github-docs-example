# Writing good documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown makes it *very easy* for tech people to **copy, paste and share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their codes to replicate or research issues. [<sup>[a]</sup>](#external-references)

- In order to use Codeblocks in markdown, you need to use three backticks **(```)**
- Not to be confused with single quotes __(''')__

### Markdown with backticks
```
# Using chain() + keys() + values()
from itertools import chain
 
# initializing dictionary
test_dict = {"Gfg" : 1, "is" :  3, "Best" : 2}
 
# printing original dictionary
print("The original dictionary is : " + str(test_dict))
 
# chain() is used for concatenation
res = list(chain(test_dict.keys(), test_dict.values()))
 
# printing result
print("The ordered keys and values : " + str(res))
```

- When possible, attempt to apply syntax highlighting to the codeblock
- How? Add the languge after the first set of backticks(eg ```js...)
```python
# Using chain() + keys() + values()
from itertools import chain
 
# initializing dictionary
test_dict = {"Gfg" : 1, "is" :  3, "Best" : 2}
 
# printing original dictionary
print("The original dictionary is : " + str(test_dict))
 
# chain() is used for concatenation
res = list(chain(test_dict.keys(), test_dict.values()))
 
# printing result
print("The ordered keys and values : " + str(res))
```

## Images
- To add an image, You must be in the edit mode. Drag and drop the image
- This method does not allow resizing so the resizing can be done with HTML and CSS syntax 

<img width="500px" src="https://github.com/agoetee/github-docs-example/assets/96971156/fcb2fb54-1110-4e4d-9614-9380210aa360" />

## Errors
Good Cloud Engineers also use codeblock for errors that appear in the console.
> To show syntax highlighting for errors, add bash after the backtics (```bash...)

```bash
Traceback (most recent call last):
File "<pyshell#18>", line 1, in <module>
            
L1[3]
IndexError: list index out of range
```
## Step 3. Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items found in the link [<sup>[1]</sup>](#external-refernces) below.

- [x] Finish task 1
- [ ] Finish task 2
- [ ] Finish task 3 :tada:

## Step 4. Use Emojis(Optional) :smirk: :monocle_face: :muscle: :man_technologist:

Github Flavored Markdown **(GFM)** supports well known emojis. This is a cloud :cloud:
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |

## Step 5. How to create a Table
Table creation is referenced in the resources below [<sup>[2]</sup>](#external-references)

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
```
Github extends the functionality of markdown tables to provide more alignment and table cell formatting options.

## Image Uploads
Added this image via object uploads. It shows multiple monitor setup and it is great Cloud Engineers
> Markdown syntax appears like the below image. No flexibility to resize and format the looks of the image

![Photo Upload- Multi screen](assets/multi-monitor-setup.jpg)

> html syntax appears like this. There is flexibility in size and positioning
<img width="500px" src="assets/multi-monitor-setup.jpg" />

[Secret Window Hidden Garden](secret-window/hidden-garden.md)

## External References
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>[a]</sup>
- [GFM full Documentation](https://github.github.com/gfm/)
- [agoetee Home Repos](https://github.com/agoetee?tab=repositories) 
- [Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
- [Github Emoji Cheat Sheet](https://github.com/agoetee/github-docs-example/edit/main/README.md)
- [GFM Table (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>


