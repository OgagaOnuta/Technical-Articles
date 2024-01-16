---
title: "How to Write Markdown"
datePublished: Wed Nov 29 2023 14:13:15 GMT+0000 (Coordinated Universal Time)
cuid: clpjuk9o7000m09l5gj5z1fga
slug: how-to-write-markdown
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1701264135486/4d91731b-4661-41a0-81bb-5928664485ff.png
tags: markdown, markdown-cheat-sheet, markdown-how-to-write-markdown-file, markdown-syntax, markdown-technical-writing-technical-documentation-documentation

---

## Introduction

In this article, readers will learn how to write in Markdown and use it in formatting their documents.

A different range of creators can make use of Markdown. For software developers, the file with the information about your projects, like the `README.md` file is written in Markdown. Technical and content writers can also use Markdown to write documentation, blogs, and other write-ups.

This article helps you understand how to write in Markdown.

## Prerequisite

To follow along with this article;

* download and install a text editor able to render Markdown, like [*Visual* *Studio Code*](https://code.visualstudio.com/download), or
    
* use an online editor, like [*Dillinger*](https://dillinger.io/)
    

## What is Markdown?

**Markdown** is a way to write and format content for the web. It uses special syntax to format documents. Writing in Markdown differs from other applications that use **GUI** (Graphical User Interface) to highlight and format text, like *Microsoft Word*, and *Google Docs*.

Some text editors provide **WYSIWYG** *(What You See Is What You Get)* features that render and display the Markdown formatted text as you edit them, like *Visual Studio* *Code, Notepad++, Ghostwriter, etc*. These text editors might require an extension/plugin to display Markdown.

The file extension for markdown is *.md* or *.markdown*. Say you have a file named `my_file`, to make it a Markdown file, you save it as `my_file.md` or `my_file.markdown`.

Markdown was created by **John Gruber** in **2004**.

## Formatting in Markdown

Special characters are used to format Markdown files, *i.e.* making text *italics*, **bold**, and so on. These special characters are highlighted below:

> **TO SPARK YOUR INTEREST, THIS ARTICLE WAS WRITTEN IN MARKDOWN.**
> 
> **NOTE:** The rendered Markdown is shown after every code block.

### Headers

To indicate a *header* in Markdown, begin the line with a *hash* (`#`) sign. There are six levels of headers in Markdown, and the number of `#` signs beginning the line marks the level of the header. Each header must be separated with blank lines.

```md
# Header LEVEL 1

## Header LEVEL 2

### Header LEVEL 3

#### Header LEVEL 4

##### Header LEVEL 5

###### Header LEVEL 6
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701261863709/2e72ef9f-60da-4a66-88b2-5337c2863c8e.png align="center")

### Paragraphs

To write *paragraphs* in Markdown, you separate each paragraph with a *blank line*. Some Markdown renderers require that you end each paragraph with *two spaces* (`[ ][ ]`) to mark the end of the paragraph, and to also indicate blank lines, like *GitHub Flavored Markdown*.

```md
This is a paragraph,
and this is part of the same paragraph.
[BLANK LINE]
This is another paragraph.[ ][ ]
This is yet another paragraph.[ ][ ]
[ ][ ]
And this is also another paragraph.
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701261893923/4c52dc38-8aa9-47bd-870e-0c9d434c84cd.png align="center")

> `[ ]` in the example code above represents a **space** from pressing the "**SPACEBAR**" key

### Bold

To **bolden** a text, surround the text with **two asterisks** (`**`) or **two underscores** (`__`). Be consistent with whichever you choose.

```md
Surround text with **two asterisks** or __two underscores__ to format as bold.
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701261959417/844531c3-1721-481a-9706-f15915fe04ff.png align="center")

### Italics

To display text as *italics*, surround the text with *one asterisk* (`*`) or *one underscore* (`_`). Whichever you decide to use, try to be consistent with it.

```md
Surround text with *asterisk* or _underscore_ to format as italics.
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701261999653/182d59ba-b875-4db3-b232-a3c41f1a6bef.png align="center")

### Lists

*Lists* are used to present text in steps. They are usually separated by blank lines for readability sake. There are two main types of lists as explained below:

#### Ordered Lists

Lists are presented in an order when the next step cannot be done before the previous step. For example, to put on your trainers when you want to go for a run, you don't wear your shoes before wearing your socks, it has to be done the other way around. To indicate an ordered list, begin each line with a number (`1, 2, 3, etc`) and a period (`.`) sign.

```md
Follow this routine when exercising:

1. Warm-up
2. Low-intensity exercises
3. High-intensity exercises
4. Warm-down
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262032903/50b56627-e621-43ea-ab61-6ab59b018c14.png align="center")

#### Unordered Lists

Lists that don't require any particular order are labelled **unordered**. For example, when shopping for groceries, you can decide to get the third, or seventh item on the list provided you are on the aisle where the item is displayed before picking up the first item. To display an unordered list, begin each line with an *asterisk* (`*`), a *dash* (`-`), or a *plus sign* (`+`).

> **REMEMBER**: Be consistent with whichever format you choose.

```md
Provisions List

* Peanut Butter
* Cookies
* Cereal

Body Care List

- Hair Cream
- Body Cream
- Deodorant

Cloth List

+ Shirts
+ Jeans
+ Socks
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262099939/580e239e-7609-4cb6-9da6-6f8a7f9b62e0.png align="center")

Lists can also be nested in lists. To do this, indent the nested list by at least *4 spaces* or *1 tab*.

```md
How to:

* Develop a program
    1. Think out the algorithm
    2. Write the pseudocode
    3. Code the program

* Prepare a cereal
    * Get the cereal
    * Get the bowl and cutlery
    * Pour the milk
    * Pour the cereal
    * Add sweeteners
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262155882/d8bf8176-6462-4dff-b7f0-a7d694455ff0.png align="center")

> Note how you can get the bowl and cutlery before the cereal, or pour the cereal before the milk, for unordered lists.

### Code

`Code` is highlighted and formatted differently from every other text. It is mainly used to display programming languages, but can also be used to display special text. The two ways to display text as code are shown below:

#### Inline Code

To display `code` inline, that is, without breaking the flow of the document, surround the code with *backticks* (`` ` ``).

```md
To display output in Python, use the `print()` function.
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262215235/8c9568c4-488e-4cc8-b394-8b1b22751585.png align="center")

#### Multi-line Code

To display `code` in more than one line, as a block, surround the lines with *three backticks* (` ``` `) or *three tilde* (`~~~`) signs. To format the code as a specific programming language, or as a text, add the language file extension after the first three backticks or tilde signs.

````markdown
Displaying output in Python

```py
print("Hello, world!")

```

Formatting text as bold in Markdown

~~~md
What **country** do you hail from?

~~~
````

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262286921/9744c535-0cf6-4998-8d0a-7acf2663e2cd.png align="center")

### Blockquotes

*Blockquotes* are displayed in a special way to get the reader's attention. It is usually used to indicate important information. To highlight a blockquote, begin each line with the *greater than* sign (`>`). Blank lines in blockquotes also begin with `>`.

```md
Here are two famous quotes:

> The greatest glory in living lies not in never falling, but in rising
> every time we fall.[ ][ ]
> \- Nelson Mandela
>
> The way to get started is to quit talking and begin doing.[ ][ ]
> \- Walt Disney
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262315204/82b92e45-3132-4328-83b0-fa9826eab252.png align="center")

> Note the *two spaces* after the quote to end the paragraph, and the *backslash* "\\" (explained later in this article) used here to prevent the text from becoming a list within the blockquote.

### Links

*Links* are used to direct users to another location, like another page on the website/document, or another website/document entirely. Links are formatted in two ways:

#### Inline Links

For inline links, the links are shown side-by-side with the text when writing Markdown. To create an inline link, surround the link text with *square brackets* `[]`, and then follow up with the link surrounded with *parentheses* `()`. There should be no space between the square brackets and parentheses.

```md
This is a link to my very [first article](https://ogagaonuta.hashnode.dev/python-need-to-know-for-beginners)
```

Clicking on the link text will now point you to the specified link as shown below:

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262368090/b35b3acf-6dfc-4969-9116-d9fa19c2c335.png align="center")

#### Reference Links

For reference links, a *tag name* is placed side-by-side with the text. This tag name then points to the link somewhere else in the document. This makes the document readable, by separating the link(s) from the text. It also helps when editing as you only have to correct the link in one place, rather than going through the whole document and correcting the link in several places.

To create a reference link, surround the link text with *square* *brackets* `[]`, and then follow up with the tag name surrounded in *square brackets*. There should be no space between the square brackets and the tag name. For a multi-word tag name, use underscores or dashes as a separator.

The tag name can now be pointed to the link anywhere else in the document by specifying the tag name in *square brackets*, followed by a *colon* (`:`), a *space*, and then the link, all on its line. This is mostly placed at the end of the document.

```md
Click [here][google] to visit the **Google** website.

[google]: https://www.google.com/
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262393669/53293443-7554-4a7e-9360-25dd9b87eb35.png align="center")

### Images

Images can also be displayed in Markdown. Images are formatted the same way as links, with the *one difference* of beginning each image with an *exclamation mark* (`!`). The link text is replaced with an *alternate* *text* for the image, and the link itself is replaced with a link to the image, either stored locally on your computer or hosted online. As links, there are two ways to format images:

#### Inline Images

To display an image inline, you begin with an *exclamation mark* (`!`), and then follow the same syntax as the *inline links* described above.

```md
This is an image of the **Bash _Shebang_**.

![shebang](https://res.cloudinary.com/practicaldev/image/fetch/s--ggy90Gr7--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/71jsf4ymyf93rz7m45m4.png)
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262418226/baa7189b-0272-47b4-8d30-7c8170d1804b.png align="center")

#### Reference Images

To display an image as a reference, you begin with an *exclamation* *mark* (`!`), and then follow the same syntax as the *reference links* described above.

```md
My present profile picture.

![profile picture][prof-pic]

[prof-pic]: ./images/profile_picture.png
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262442960/4314122f-138a-4008-8c74-bb3cb567670e.png align="center")

### Table

A table is a visual aid arranging elements in rows and columns. Markdown is also able to create tables by using the *pipe* (`|`) character. Each *column* is separated by the *pipe* character, and each *row* is placed on its line. To separate a header row from the body row, you create a row with each column filled with *dashes* (`-`)

Columns can be aligned by placing *colons* (`:`) on the row separating the header and body. By default, columns are left aligned. Put the colons:

* on the *left* for left alignment
    
* on the *right* for right alignment
    
* on *both sides* for centre alignment
    

```md
The Logic **AND** Table

| A     | B     | A AND B |
| :---- | :---- | :-----: |
| True  | True  | True    |
| True  | False | False   |
| False | True  | False   |
| False | False | False   |
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262483556/4fa48e55-1615-40a4-bd31-250ab47cf398.png align="center")

### The "Escape Character"

The *escape character* is used to prevent the character which follows it from executing its special meaning. It removes the formatting of the character and displays it as plain. The escape character is the *backslash* (`\`), and it comes in handy when writing in Markdown.

```md
\* is used to begin a list item in Markdown.

\- is also used, it's just based on preference.

The **asterisk \*** is used to format text as bold.

To escape a backtick in an inline code, surround it with two backticks `` ` ``.

The escape character can also escape a backtick, e.g. \`print()\` instead of
`print()`.
```

RENDERED OUTPUT

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1701262510312/16bd0ca8-a8b0-478a-9321-94d603cb1692.png align="center")

> Note the use of backticks to escape another backtick. This is a special case.

## Conclusion

I hope you enjoyed reading this article and were able to follow along practically. If you did, you should be able to write in **Markdown** now. Markdown is fun and easy to write.

Highlighted below are links for further reading.

See you in my next article.

### Resources

* [https://www.markdownguide.org/tools/](https://www.markdownguide.org/tools/)
    
* [https://www.markdowntutorial.com/](https://www.markdowntutorial.com/)
    
* [https://www.dotcms.com/docs/latest/markdown-syntax](https://www.dotcms.com/docs/latest/markdown-syntax)
    
* [https://markdownguide.offshoot.io/basic-syntax/](https://markdownguide.offshoot.io/basic-syntax/)