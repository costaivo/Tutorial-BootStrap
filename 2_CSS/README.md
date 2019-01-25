# CSS

## CSS basics

HTML allows us to view text and pictures on the webpage. CSS exists to make the content on the page look good.
- CSS describes how the HTML elements should be displayed.
- Mixing content and presentation is difficult to maintain.
- CSS helps seperate presentation rules with structrue

### Demo : How CSS Works

In Demo we will see how applying css makes visual difference to a page.
 - [Without CSS, just plain HTML](http://www.costaivo.com/Tutorial-BootStrap/2_CSS/1_Introduction/index.html)
 - [With CSS, lets see how the page looks now](http://www.costaivo.com/Tutorial-BootStrap/2_CSS/1_Introduction/final.html)
 - [Slightly modified page](http://www.costaivo.com/Tutorial-BootStrap/2_CSS/1_Introduction/final_2.html)

#### CSS Code

```css
body {
  font-family: "Montserrat", sans-serif;
}

.destination {
  box-sizing: border-box;
  width: 320px;
  height: 420px;
  margin: 20px auto;
  border: 1px solid #aaa;
  box-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
  cursor: pointer;
  transition: background-color 400ms ease-out;
}

.destination:hover,
.destination:active {
  background-color: #fa923f;
  color: white;
}

.thumbnail {
  width: 100%;
  height: 300px;
  overflow: hidden;
}

.thumbnail img {
  width: 100%;
}

.content {
  text-align: center;
}

.content h1 {
  margin: 10px 0;
}

```
### Add style to HTML page

```html
<head>
  <style type="text/css">
    body {
      background-color: red;
    }
  </style>
</head>
```

### Add styles in separate page.

Adding styles in seperate page allow the same styles to applies across multiple pages

## File:styles.css

```css
body {background-color:red}
```

## File:index.html

```html
<head>
  <link rel="stylesheet" href="styles.css" type="text/css" />
</head>
```

## Style Rules

A CSS comprises of style rules that are interpreted by the browser and then applied to the corresponding elements in your document. A style rule is made of three parts −

- **Selector** − A selector is an HTML tag at which a style will be applied. This could be any tag like <h1> or <table> etc.

- **Property** − A property is a type of attribute of HTML tag. Put simply, all the HTML attributes are converted into CSS properties. They could be color, border etc.

- **Value** − Values are assigned to properties. For example, color property can have value either red or #FFFF etc.

### Style Rules Syntax:

```css
selector {
    property-name:value;
}
```

### [Example:](/Rules.html)

```css

body{
     background-color:grey
}

p {
      background-color:green;
      font-family:arial;
}
```

## [Selectors](/3_Selectors.html)

A selector is a pattern used to apply styles to elements

### Simple Selector / Type Selectors

```css
body {
    background-color:lightblue;
}

p {
    color: red;
    font-style: italic;
    font-weight: bolder;
    font-size: xx-large;
}
```

### ID Selectors

```css
 #mySuperHeader {
    background-color: #ffff00;
    color: blue;
    font-style: italic;
    font-size: xx-small;
}
```

### Class Selectors

```css
  .greenPara {
            color: green
        }
```

### Universal Selectors

Rather than selecting elements of a specific type, the universal selector quite simply matches the name of any element type.
The below rule renders the content of every element in our document in black.

```css
* {
    color: #000000;
}
```

### Descendant Selectors

Suppose you want to apply a style rule to a particular element only when it lies inside a particular element. As given in the following example, style rule will apply to <em> element only when it lies inside <ul> tag.

```css
ul em {
   color: #000000;
}
```

### Child Selectors

```css
ul em {
   color: #000000;
}
```


