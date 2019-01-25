# HTML

## Introduction to VSCode

- Demo on Using [VSCode](https://code.visualstudio.com/)
- Installing the [LiveServer Extension](https://ritwickdey.github.io/vscode-live-server/)
- Installing the [Prettier extension](https://prettier.io/)

## Before we start 

[Let look at the survey results to see what skills you already have](https://ivocosta1.typeform.com/report/Q8VI4d/yoBybcHpj6P1tNem)


## What is HTML

HTML stands for _Hyper Text markup language_
A Markup language basically annotates the text so that the computer can manipulate that text.

When a browser (IE,Chrome,Firefox) displays a webpage, it reads the contents and interprets the HTML.

HTML is a set of pre-defined elements or tags that tell browser what content to display and how to display that content.

HTML (Hypertext Markup Language) is the basic language that websites are built in. It’s right underneath the surface of everything you see on the web and you can uncover it with a couple quick steps. Try this:

- Open a new browser window or tab and go to flatironschool.com.
- Right-click anywhere in the browser screen and choose “View Page Source.”
- Behold the HTML!

## TAGS

- HTML is made up of tags
- Tags tell the browser where an element should start and end
- The markup tags are **<** and **>**
- tags should be lowercase
- each tag and its content is an **HTML element**

[Tag Example](https://codepen.io/CostaIvo/pen/xVWvyZ)

## Elements

```html
<p>this is a paragraph element</p>
```

Above is a paragraph element. The text content inside the **P** tag is formatted as a paragraph when dispalyed on the browser

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

Above are list of various header elements.

## Empty Elements

Elements usually have a start and closing tag, like <p></p>. But there are some elements which dont have closing tag, this type of tags are called **Empty tags**

```html
<br />
<input />
<hr />
```

## Structure of HTML Page

```html
<!DOCTYPE html>
<html>
  <!--THIS IS THE HEAD SECTION -->

  <head>
    <title>Document</title>
  </head>

  <!-- THIS IS THE BODY SECTION-->

  <body></body>
</html>
```

- The **<html>** tag tells the browser "hey contained in here is a bunch of HTML code."
- The **<head>**  it  contain our references to outside bits of code such as CSS or Javascript.
- The **<body>** tag tells the browser "contained in here is the stuff I actually want you to show the user."

## Commenting HTML Code

A comment starts with the tag `<!-- and ends with tag -->`. Whatever content is added inside a comment tag is never displayed in the browser.

## Summary

- HTML element starts with a opening tag
- HTML element ends with a closing tag
- The letters between the < and > are abbreviations
- The element content is everything between the **start tag** and the **end tag**
- Some HTML elements are empty
- Empty elements are closed in the **start tag**
- Make it a habit to type all your tags in **lowercase** - it is considered good practice

## Lesson 2

### Attributes
- Attribute is a characteristic of a element. E.g. font size or color.
- Attributes are used to amplify a tag. 
- When a browser interprets and HTML tag it will also check if its attributes are set so that it can display the **elements** properly.

### Image Tag

The HTML <img> element embeds an image into the document.

`<img src="http://www.itsgoa.com/wp-content/uploads/2017/05/Goa-tourism-780x405.jpg" alt="Goa Tourism" />`

### Link Tag

`<a href="https://en.wikipedia.org/wiki/HTML">Wiki Link: HTML </a>`

### Web Standards

Validate if your webpage is well formed using the below url
https://validator.w3.org/nu/#file

## [Lesson 3 : Demo 1]()

Convert the text file to a HTML document

## Lesson 4 :HTML Block and Inline Elements

### Block Elelements

Block element always starts on a new line and takes up the full width available.

Example:

```HTML
<div>Hello HTML</div>
<article> i am a important text </article>
```

### Inline Elements

An Inline element does not start on a new line and takes up as much width as necessary

Example:

```HTML
<span>Hello HTML</span>
<strong> i am a important text </strong>
```

## Lesson 5: Other HTML Elements

### HTML Tags related to Formatting

- <b>Bold text
- <strong>Important text
- <i>Italic text
- <em>Emphasized text
- <mark>Marked text
- <small>Small text
- <del>Deleted text
- <ins>Inserted text
- <sub>Subscript text
- <sup>Superscript text

### Lists

**Unordered lists**

```html
<ul>
  <li>One</li>
  <li>Two</li>
  <li>Three</li>
  <li>four</li>
  <li>five</li>
</ul>
```

**Ordered lists**

```html
<ol>
  <li>One</li>
  <li>Two</li>
  <li>Three</li>
  <li>four</li>
  <li>five</li>
</ol>
```

### Tables

```html
    <table style="width:100%">
        <tr style="text-align: left">
            <th>Name</th>
            <th>Degree</th>
            <th>Year</th>
        </tr>
        <tr>
            <td>Student Name</td>
            <td>Course Name</td>
            <td>Semester</td>
        </tr>
```

### Quotations

```html
    <blockquote>
      <p>This is a blockquote</p>
    </blockquote>
```
## [Quiz](http://www.costaivo.com/Tutorial-BootStrap/1_HTML/9_Quiz/HTML-Quiz.html)

### References for Further Learning

- [HTML Dog HTML Tags](http://www.htmldog.com/references/html/tags/)
- [Mozilla Developer Network HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
