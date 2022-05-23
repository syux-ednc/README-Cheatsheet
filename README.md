# README-Cheatsheet

This is a cheatsheet to refer to when creating projects with brief writeup / setup guides.

## Table of Content

- [Table of Content](#table-of-content)
  - [Basic Stuff](#basic-stuff)
  - [Create Blockquotes](#create-blockquotes)
  - [Create Table](#create-table)
  - [Create Code](#create-code)
  - [HyperLinks](#hyperlinks)
  - [Images](#images)

## Basic Stuff

This is a **bold** text. Alternatively, you can also __bold__ text like this.

This is a _italic_ text.

You can combine bold and italic text **_like this_**.

This is a ~~strikethrough~~ text.

Unordered list can use:
* Asterisk Sign
- Minus Sign 
+ Plus Sign

## Create Blockquotes

> You can create blockquotes(a line separator at the left hand side) using the ">" symbol. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam fermentum lorem quam, nec maximus magna sollicitudin ut. Vestibulum varius quam elit, ac tempus dui iaculis vel. Mauris et suscipit nibh. 

## Create Table

You can create table by using the "|" pipe symbol together with the header separator ":---:".

The table row contents need not be aligned with spacing like the title. You can just compact it.

| NAME: `varchar` | USERNAME (p_key): `varchar` | PASSWORD: `varchar` | BALANCE: `number` |
| :-------------: | :-------------------------: | :-----------------: | :---------------: |
| Nico Robin | nico_robin | password123 | 1000 |
| Tony Chopper | tony_chopper | asdf123 | 2000 |
| Sanji Vinsmoke | sanji_vinsmoke | dragon123 | 3000 |
| Zoro Rorona | zoro_rorona | sword123 | 4000 |

## Create Code

You can include line code like this `pip install pandas` in a paragraph using backticks.

Alternatively, you can write block codes in paragraphs using the triple backticks like this:

```
private String username;
private String password;
```

You can also include syntax highlighting for specific programming languages (need check which are supported) or other code related stuff (E.g. HTTP headers) as shown below:

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```

## HyperLinks

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

[Inline-style link](https://www.google.com)

[Inline-style link with title when hover](https://www.google.com "Google's Homepage")

[Reference-style link][This is a custom-ref key]

[Relative reference to a repository file](assets/files/testing.txt)

[Number Reference-style link][1]

Or leave it empty and use the [link text itself].

[This is a custom-ref key]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

## Images

Using normal hyperlink with hover (hover to see the title text):

Inline-style: 
![alt text](https://github.com/syux-ednc/README-Cheatsheet/blob/master/assets/images/Wallpaper.jpg "Logo Title Text 1")

Using html tag:
<p align="center">
  <img src="https://raw.githubusercontent.com/syux-ednc/README-Cheatsheet/master/assets/images/Wallpaper.jpg" width="500px" style="display: block; margin: 0 auto"/>
</p>



