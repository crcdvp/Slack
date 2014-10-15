# Markdown Tutorial

Markdown is a text formatting documentation type thing, it's commonly used on places like blogs, Reddit, Github, scientific papers, etc. It's really easy to learn, and incredibly useful to know.

This guide is taken originally from [Reddit's commenting wiki](https://www.reddit.com/wiki/edit/commenting) with several edits made.

---

##Common Formatting


###Italics

Use a single asterisk to italicize text:

    *italics*

Looks like:

*italics*

###Bold

Use double asterisks to bold text:

    **bold**
    
Looks like:

**bold**

###Hyperlinks

Use the format: \[text](link) to create a hyperlink

    [google](http://google.com)
    
Looks like:

[google](http://google.com)

###Quotes

    > A fine quote

is displayed as

 > A fine quote
 
###Numbered Lists

Type a numbered list to get a numbered list. (Pretty self explanatory)

    1. Apples
    2. Bananas
    3. Carrots
    
Looks like:

1. Apples
2. Bananas
3. Carrots

If you begin a numbered list, you don't need to type the actual numbers. Markdown will format the numbers for you. So these four will all give the same result:

    1. Apples
    1. Bananas
    1. Carrots

and

    2. Apples
    1. Bananas
    3. Carrots

and

    1. Apples
    * Bananas
    - Carrots
    
and

    1. Apples
    80. Bananas
    37. Carrots
    
They all look like:

1. Apples
80. Bananas
37. Carrots

###Bulleted Lists

Use an asterisk or hypen to begin a bulletted list:

    * Apples
    * Bananas
    * Carrots

Looks like:

* Apples
* Bananas
* Carrots

If you want to indent your bullets, simply add two spaces before them:

    * Apples
      * Bananas
    * Carrots 

Looks like:

* Apples
  * Bananas
* Carrots

###Tables

You can create a table by organizing pipes (|), hyphens (-) and text within a particular syntax. For example, inputting this:

`Column A | Column B | Column C`  
`---------|----------|----------`  
`A1 | B1 | C1`  
`A2 | B2 | C2`  

will display this:

Column A | Column B | Column C
-|-|-
A1 | B1 | C1  
A2 | B2 | C2

To change the alignment of the elements in a column, add a colon (:) to the left side, right side, or both sides of the appropriate set of hyphens on the second line. For example, inputting this:

`Column L | Column C | Column R`  
`:--------|:--------:|---------:`  
`A1 | B1 | C1`  
`A2 | B2 | C2`  

will display this:

Column L | Column C | Column R
:-|:-:|-:
A1 | B1 | C1
A2 | B2 | C2

Note that in both cases, only one hyphen is needed between the pipes on the second line, and no spaces are needed to separate table elements from pipes on the third and fourth lines. Adding multiple hyphens and spaces may be useful for clarity, but they will not affect the final layout.

Lines with table syntax can be preceded with pipe characters, but this is entirely optional.

Be warned: pressing enter twice and putting blank lines between lines with table syntax will break table formatting.

###Strikethrough

Use double tildes to strikethrough text:

    ~~strikethrough~~
    
Looks like:

~~strikethrough~~

###Code Indents

Indent a line of text with 4 spaces to get a "code"-like formatting

[4 spaces]text

Looks like:

    text
    
###Escape the Formatting

Type a backslash to "escape" the formatting system:

    \*hi*
    
Looks like

    *hi*

---

##Common issues

###Numbering

If a number is followed by a period at the beginning of a line, Markdown interprets it as a numbered list and always starts at one. For example, if you typed "2009. What a year.", it will output as "1. What a year." To fix this, put a backslash in front of the period: "2009\\. What a year."

###Links with special characters

An issue affects links to Wikipedia and websites with similar URLs. To link to:


> http://en.wikipedia.org/wiki/Pica_(disorder)

escape the problematic characters "(" and ")" by adding backslashes in front:


> http://en.wikipedia.org/wiki/Pica_\(disorder\)

The same applies to named links:

`[Pica (disorder)](http://en.wikipedia.org/wiki/Pica_\(disorder\))`

renders as:

[Pica (disorder)](http://en.wikipedia.org/wiki/Pica_\(disorder\))

###Line Breaks

Individual line breaks are ignored, so if you type:

    Hu Ha Hu Ha Hu Ha Hu Ha  
    Eh Meh Eh Meh Eh Meh Eh Meh

...you get:

    Hu Ha Hu Ha Hu Ha Hu Ha Eh Meh Eh Meh Eh Meh Eh Meh

To display a line break in your post, use a double line break to start a new paragraph. If you type:

    Hu Ha Hu Ha Hu Ha Hu Ha
    [line break]
    Eh Meh Eh Meh Eh Meh Eh Meh

...you get:

    Hu Ha Hu Ha Hu Ha Hu Ha
    Eh Meh Eh Meh Eh Meh Eh Meh

---

##More Stuff


For more advanced syntax options, see the [ Official Markdown Syntax](http://daringfireball.net/projects/markdown/syntax).

Or this popular user-created [ Markdown primer](http://www.reddit.com/r/reddit.com/comments/6ewgt/reddit_markdown_primer_or_how_do_you_do_all_that/).