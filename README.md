### _**Note**: You can click `<>` at the top of the file to disable Markdown rendering and view the source of anyone's README instead ._
___
# Headers
The main header is created by using "`#`" followed by an space at the beginning of the line. 
The Sub-headings are followed by the extra number of #s.  
For example: 
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
___

# Styling Text

## Italicize

You can *italicize* text by using either `*[sometext in here]*` or `_[sometext in here]_.`  
The Hotkey for Italicizing the text is `Ctrl+i` i.e. select the text you would like to italicize and press `Ctrl+i`.

## Bold

You can **bold out** text by using either `**[sometext in here]**` or `__[sometext in here]__`.  
The Hotkey to Bold Out the text is `Ctrl+b`.

## Strikethrough

You can ~~Strike through~~ text by using `~~[strike_through_text]~~.`

## Both(Bold and Italic)

_You can nest __Bold text__ inside Italic sentence/block_ or ___Italicize text__ inside the Bold sentence/block__ as well.

## Paragraph & Line Break

If you simply hit `<return>` key after full stop or after the end of the sentence, you won't be getting the same result in the output. 
To break the line in markdown files, you must have at least two `<spaces>` before you hit the `<return>` key.  
And two create a new paragraph, you must hit the `<return>` key twice CONSECUTIVELY. 
___

# Escaping 

The back-slash "`\`" is used as the escape character in markdown files.   
For example: `**bold**` would generate **bold** as the output in the markdown files. For \*\*bold** to be the output in the markdown files, you have to escape the asterisks(\*) before the word(bold) by putting backslash(`\`) before them i.e. `\*\*bold**`
___

# Links

You can use the syntax \[Description text\]\(URL\) to add links. For example:- [Nianfo Right Now.](https://www.youtube.com/watch?v=hxxFvAj-Y98&t=20s)
___

# Online Images

You can use the syntax \!\[Alternative Text\]\(URL of the image\) to insert images in your README.MD 

![Amitabha Buddha!](https://shaolin.org/images-answers/ans11a/amitabha01.jpg)
___

# Unordered list and Nested List

You can use `*` or `-` followed by an space at the beginning of the line to make a bullet point infront of the list items. 
* List Item 1
* List Item 2
* List Item 3

You can make nested lists by indenting each item in the sublist by four spaces before the * at the beginning of the line. 
1. Item No. 1
2. Item No. 2
    * Item No. 2.a
    * Item No. 2.b
    * Item No. 2.c
3. Item No. 3
    1. Item No. 3.1
    2. Item No. 3.2
    3. Item No. 3.3
4. Item No. 4
___

# Blockquotes

You can use greater than sign `>` to specify that the following line is a quote. If you have multiple lines, then use `>` infront of each line.   
For example:  

_The 18th Vow of Amitabha Buddha, The Fundamental Vow:_
>__If, when I attain Buddhahood, sentient beings in the lands of the ten quarters who sincerely and joyfully entrust themselves to me,  
>desire to be born in my land, and call my Name, even ten times, should not be born there, may I not attain perfect Enlightenment.  
>Excluded, however, are those who commit the five gravest offences and abuse the right Dharma.__
___

# Creating and highlighting code blocks

## Fenced Code Blocks
You can create fenced code blocks by placing triple backticks ` ``` ` before and after the code block. It is recommended to place a blank line before and after code blocks to make the raw formatting easier to read.  

To display triple backticks in a fenced code block, wrap them inside quadruple backticks. i.e
`````
````
```
   
   some code in here {}
   
```
````
`````  

would generate:
````
```
   
   some code in here {}
   
```
````

## Syntax Highlighting
You can add an optional language identifier to enable syntax highlighting in your fenced code block.

For example, to syntax highlight batch code:

````
```batch

@echo off
set /p name="What is your name: "
echo The name you have entered is %name%.

```
````

will give the output:
```batch

@ECHO OFF
SETLOCAL
CLS
SET /p name="What is your name: "
ECHO The name you have entered is !name!.
EXIT

```
___


