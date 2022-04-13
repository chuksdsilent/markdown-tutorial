
# Basics of Markdown

## Header
There are diferent header level starting from 1 to 6 just like HTML

* \# Header 1

* \## Header 2
* \### Header 3
* \#### Header 4
* \##### Header 5
* \###### Header 6
### Output

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

## Italics
To style your text with italics you can use either single asterics(*) or underscore(_) before and after the word(s) or paragraph

For example

\*This paragraph* is Italics

or

\_This paragraph_ is Italics

### Output
*This paragraph* is Italics

or

_This paragraph_ is Italics

## Strong

To make your text strong you can use double asterics(**) or double underscore(__) before and after the word(s) or paragraph

\**This paragraph** is Strong

or

\__This paragraph__ is Strong

### Output
**This paragraph** is Strong

or

__This paragraph__ is 

## Horizontal Line

To create a horizontal line which most often used as a seperator. you use either triple hyphen(---) or triple  underscore(___)

for example

\___

\---
### Output
___

---

## Blockquote

To create a quote you can use greater than sign(>).

For example

\> The is a quote
### Output

> The is a quote
## Link

To create a link you use square bracket[] and parenthesis(). The link label will be inside the square bracket while the link will be inside the parenthesis

For Example

\[oshabz.dev](https://oshabz.dev)
### Output

[oshabz.dev](https://oshabz.dev)

## Unordered List

To create an unordered list you can use a single asterics(*)

For example

\* Item 1

\* Item 2

\* Item 3
### Output

* Item 1

* Item 2

* Item 3
## Ordered List

To create an ordered list you can use numbers

1. Item 1
2. Item 2
3. Item 3
### Output

1. Item 1
2. Item 2
3. Item 3



## Images
To create an image you can use square bracket[] and parenthesis just like link but in this case the link to the image goes inside the parenthesis while the alt goes inside the square bracket

For example

\!\[Github Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
### Output

![Github Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

The above is the basics of markdown. Github has it's own added markdown flavour which we will be looking at next.

## Inserting Code Snippets

This is basically for hightlighting code if you want to insert code into mark down. To insert a code block you can use triple backtics

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

\```javascript

    function add(num1, num2){
        return num1 + num1
    }
\```

### Output
```javascript
function add(num1, num2){
    return num1 + num1
}
```
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
