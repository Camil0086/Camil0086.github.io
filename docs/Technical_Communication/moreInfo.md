---
layout: default
title: Additional content
parent: Technical Communication
nav_order: 6
---

Additional content
==================

- [Additional content](#additional-content)
  - [Title](#title)
  - [New line and paragraph](#new-line-and-paragraph)
  - [Bold text](#bold-text)
  - [Italic text](#italic-text)
  - [Link to a website](#link-to-a-website)
  - [Image](#image)
  - [Headers](#headers)
  - [Inline code](#inline-code)
  - [Block of code](#block-of-code)
  - [Quote](#quote)
  - [Bullet list](#bullet-list)
  - [Numbered list](#numbered-list)
  - [Table](#table)
  - [Link to another file](#link-to-another-file)
  - [Table of contents](#table-of-contents)

## Title 
A title can be created by underlining a normal text with an **equal** sign "=". In case of one or more equal signs, the outcome is the same. It is good practice to make as many equal signs as the length of the text. Thanks to "#" before a text you can achieve the same effect, although it is used for different purposes. [More information]().

## New line and paragraph
While writing a text, new lines will appear automatically. To create a new line put two *spaces* and click *Enter*. To create a new paragraph make a **blank line**.

## Bold text

To mark a text as bold, put two **asterisk** signs "**" in front and at the end of the text you want to bulk.

## Italic text

To mark a text as italic, put one **asterisk** sign "*" in front and at the end of the text you want to bend.

## Link to a website

Put any normal text into square brackets "[...]" to change it into a hyperlink. Put the website address in round brackets "(...)" after the hyperlink.

## Image

To put an image into a text use the exclamation mark "!" and then as a first one square and as a second one round brackets. In the former, put any text to be displayed in case the image is not found. In the latter put the address of an image and as an option, a hover text in the quotation marks. There are two ways of pasting the image address:

* if the image is in the same directory as the markdown file, use the following route (./folderName). Remember that the image can be put in any numbers of subfolders, like (./subfolder1/subfoler2/folderName)
* you can paste in round brackets an URL address with the image host.

## Headers

There are 6 levels of headers. Put a **hash** sign "#" before a text to get a level 1 header. The same effect as in case of a *Title*. Each level of header has the proper amount of hash signs. Remember to put a *space* between a hash and the text.

## Inline code

Put a **grave accent** sign " ` " before and after a text to mark it as a programming language or any other code being a part of the text.

## Block of code

Put three **grave accent** signs " ``` " in separate paragraphs, before and after a text to mark it as a piece of programming language or any other code apart from the text.

## Quote

To turn a piece of text into a quote, put a **greater than** sign ">" in front of a text. 

## Bullet list

Put an **asterisk** sign "`*`" in front of a text to create a bullet list. To make a subpoint put two *spaces* before the asterisk. To make another level subpoint put four *spaces* in front of the asterisk.

## Numbered list

To make a numbered list begin with "1." in front of a text. To make another put "2.", "3.", etc. Do not forget about the space after a dot. Without it, the text remains a normal text, although it looks like a point of the list. 

## Table

To create a table follow the below steps:
1. divide the text into particular title cells with **vertical bars** "`|`". Remember to put such in front of the first cell and at the end of the last cell.
2. in the next row underline each cel with a **minus** sign "-" and, as in case of title cells, divide them with **vertical bars**. Remember about the first and last cell.
3. to create another row divide the text of particular cells with vertical bars as in case of title cells.

## Link to another file

Put any normal text into square brackets to change it into a hyperlink. Put the name of the file with *.md* extension in round brackets after the hyperlink.

## Table of contents

To create a table of contents you have to install the *Markdown All in One* extension. Open **Command Palette** and choose *Markdown All in One: Create Table of Contents* to include all headers from your file. Remember that the Table of contents appears in the place of the *insertion point*. Go to Tips and Hints in [Markdown guide](Markdown.md) for more information. 
