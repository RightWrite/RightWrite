# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
####### There is no H7

This is a test file for Markdown Language.</br>This is a test file using the app Ghostwriter; that's a Linux application.

**bold**
</br>
*italics* using 1 asterisk on each side
</br>
__bold using 2 underscores__ 

according to the Markdown guide udnerscores should show bold, not *italics* like this.

_italics_ using one underscore on each side

So both bold & italics can be shown using asterisks & underscores.

___Bold & italics___ this is done using 3 underscores on each side

***Bold & Italics*** can also be done using 3 asterisks 

## Block Quotes
To show block quotes use the > sign followed by a space (just like pound signs).

> Here's a block quote. Here's a block quote. Here's a block quote. Here's a block quote. Here's a block quote. Here's a block quote. Here's a block quote. Here's a block quote. Here's a block quote. Here's a block quote. Here's a block quote. Here's a block quote.

## Lists
### Ordered
To create an ordered list put the number 1 followed by a period, space then list item. The rest of the numbers can be anything, & don't have to be sequential. For nested lists just use tab key & GW automatically places number.

1. First List Item
5. Second List Item
	1. First Indent of Second Item
	2. Second Indent of Second Item
2. Third List Item
4. Fourth List Item
	1. 

Note: WHen I typed these ordered lists ghostwriter automatically put the next number on the list. I also tried placeing different numbers after 1 & it renders it in order.

### Unordered Lists
To create an unordered list use the minus (-), plus (+), or asterisk (*).

Here's an unordered list:
- First List Item
- Second List Item
- Third List Item
- Fourth List Item

Note when I typed this the app automatically put the dash for the next item, just like it did with the ordered list.

UL using asterisks:
* First List Item
* Second List Item
* Third List Item
* Fourth List Item

Whether hyphens or asterisks are used it looks the same.

You can also add block quotes to lists & sentences as notes without affecting the structure.

Note: The GW app also highlights misspelled words.

## Images

### Adding Images
![Image Description](/images/forest.jpg)

Remember, for images to display correctly, there can't be a space between the closing bracket & starting parenthesis.

### Linking Images
You can create links to images. That can be done like this:<br>

[![Link To Image](/images/forest.jpg "Forest Image")](http://www.google.com/)


## Code
### (Phrases Using Back Ticks)
To depict code use two backticks, like this `code. This code is in a different font`. Note: make sure you don't use two apostrophes. 

### Code Blocks
For blocks of code indent every line 4 or more spaces (or single tabs) like this:</br>
    This is code  
    This is code
	Code
	Code

## Horizontal Rules
These are simple to create -- just use 3 or more asterisks, hyphens or underscores:

### HR using underscore
___

### HR using asterisks
***

### HR using hyphens
___

## Hyperlinks
These are simple. Just enclose the link text in brackets. Immediately after (no space), the URL appears in parentheses.

[Link Title](http://www.DuckDuckGo.com)

You can also make the hyperlinks by enclosing the URL in pointer brackets (<>) like this:</br>
<http://www.DuckDuckGo.com>

The same can be done for email: <name@website.org>.

Such hyperlinks can be formatted, for instance with italics: <br>
*<name@website.org>*

There are also Reference Style Links you can create that are used in citing sources. These are described in the Markdown Guide.

## Escape Characters
The backslash (\) is used to show characters that would otherwise be using in formatting. It goes like this:<br>

- \
- \'
- \*
- \{}
- \[]
- etc

## HTML
Many apps support HTML that some find easier to use than markdown. Check your markdown application documentation to determine if & to what extent HTML is supported.

HTML version of <em>talics</em><br>
HTML version of <strong>bold</strong>

# Extended Syntax
## Description
There is basic syntax that was part of the original development in 2004 & there's the extended syntax that some apps support. This extended syntax was created by organizations. 

A quote from the *Markdown Guide*:<br>
> Not all Markdown applications support extended syntax elements. You’ll need to check whether or not the lightweight markup language your application is using supports the extended syntax elements you want to use. If it doesn’t, it may still be possible to enable extensions in your Markdown processor.

So there are Markdown processors, Markdown applications/editors, & Markdown languages. 

Here are some languages:

- R Markdown
- CommonMark
- GitHub Flavored Markdown (GFM)
- Markdown Extra
- MultiMarkdown

There are allegedly dozens of processors (the guide doesn't mention them) that have extensions for extended syntax. 

## Tables
Tables consist of pipes & hyphens, like this:
|Table Header|Description|
|------------|------------|
|Header 1|*Description*|
|Header 2|Description|
|Header 3|***Description***|
|Header 4|Description|

Text in tables can be formatted.

Note: the pipes & hyphens don't have to be aligned; the processor will render it evenly.

Because this can be time-consuming there are apps for auto-table generation. Some are:<br>

- [Markdown Tables Generator ](https://www.tablesgenerator.com/markdown_tables)
- [AnyWayData Markdown Export](https://anywaydata.com/)

## Footnotes
An example of a sentence with a footnote (using brackets).[^1] Note: The link won't be functional until the counterpart note is created.[^2]

Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>
Text<br>


#### Footnote Data
[^1]: This is the first footnote.
[^2]: This is the second footnote.

It works!

## Heading IDs
Heading IDs can also be used to generate a TOC & to link to specific parts of a document (similar to the # at the end of a URL in HTML).

## Definition Lists
Some Markdown editors let you make these; basically it's a term in bold with the definition in regular font below it.

## Strikethrough
This can be achieved using 2 tildes, like this:<br>
This is a ~~strikethrough~~.

## Task Lists (Check Lists)
These are started same way as unordered list, then square brackets:<br>
- [x] Item 1
- [x] Item 2
- [] Item 3
- [] Item 4
- [] Item 5

## Emojis
Markdown supports emojis that can be copied & pasted directly into the editor & you can use the shortcode. 

- Shortcode :joy:
- pasted emoji 😀


Note: Shortcodes not supported in this editor (Ghostwriter). 

## Highlighted Text
To highlight words use 2 equal signs on each end, like this:<br>
==highlighted word==

Note: highlighting isn't supported in Ghowstwriter.

## Superscript & Subscript

### Superscript
Superscipt use a carat (number ^1^) before & after symbol.

### Subscript
Subscript use a tilde (number ~1~) before & after symbol.

Neither super nor subscript are supported in Ghostwriter; at least not with tildes & carats.

## Auto URL Hyperlinks
Some "processors" will automatically convert a URL to clickable text. Just type it in starting with 'http'. Example: http://www.richessence.com.<br>
Note: Ghostwriter does support this.

You can disable this auto linking by placing the URL in back ticks, like this: `http://www.richessence.com`.

H~2~O

























 
