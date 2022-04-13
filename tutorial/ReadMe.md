
# Basics of Markdown

## Header
There are diferent header lever starting from 1 to 6
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

# Italics
To style your text with italics you can use either double asterics(*) or underscore(_)

For example

*This paragraph* is Italics

or

_This paragraph_ is Italics

## Strong

To make your text strong you can use double asterics(**) or double underscore(__)

**This paragraph** is Strong

or

__This paragraph__ is 

# Horizontal Line

To create a horizontal line which most often used as a seperator. you use either triple hyphen(---) or triple  underscore(___)

for example
___

---

# Blockquote

To create a quote you can use greater than sign(>).

For example

> The is a quote

## Link

To create a link you use square bracket[] and parenthesis(). The link label will be inside the square bracket while the link will be inside the parenthesis

For Example

\[oshabz.dev](https://oshabz.dev)

## Unordered List

To create an unordered list you can use a single asterics(*)

For example

\* Item 1

\* Item 2

\* Item 3

To create a nested item you use tab

\* item 4

    \* Nested item 1

    \* Nested item 2

    ## Ordered List

To create an ordered list you can use numbers

1. Item 1
2. Item 2
3. Item 3


## Inline code block

To create inline code block you can use backticks

`<p> This is an inline code`

## Images
To create an image you can use square bracket[] and parenthesis just like link but in this case the link to the image goes inside the parenthesis while the alt goes inside the square bracket

For example

![Markdown Image](https://imagepath.png)

The above is the basics of markdown. Github has it's own added markdon flavour which will be looking at next

## Code Blocks

This is basically for hightlighting code if you want to insert code into mark down. To insert a code block you can use three backtics

For example

\```
npm install
npm start
\```

### Output
```
npm install
npm start
```

or 

you can specify the language

\```javacript

    function add(num1, num2){

        return num1 + num1
    }
\```

### Output
```javacript
    function add(num1, num2){
        return num1 + num1
    }
```

## Table

To create a table you use pipe and underscore together

For example

| Name |  Position |
|-------|----------|
| Okoye Ifeoma | UI/UX |
| Nwafor Emeka | Software Engineer |

## Task List

This is used if you want to create checkbox.

For example

\* [*] Task 1

\* [*] Task 2

\* [] Task 3

### Output
* [*] Task 1
* [*] Task 2
* [] Task 3
