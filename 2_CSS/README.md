# CSS

## CSS basics

HTML allows us to view text and pictures on the webpage. CSS exists to make the content on the page look good.
CSS describes how the HTML elements should be displayed.
Mixing content and presentation is difficult to maintain.
CSS helps seperate presentation rules with structrue

### [Demo : How CSS Works](http://www.costaivo.com/Tutorial-BootStrap/2_CSS/1_Introduction/index.html)

In Demo we will see how applying css makes visual difference to a page.

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

```html
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

```javascript
selector {
    property-name:value;
}
```

### [Example:](/Rules.html)

```javascript

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

```javascript
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

```javascript
 #mySuperHeader {
    background-color: #ffff00;
    color: blue;
    font-style: italic;
    font-size: xx-small;
}
```

### Class Selectors

```javascript
  .greenPara {
            color: green
        }
```

### Universal Selectors

Rather than selecting elements of a specific type, the universal selector quite simply matches the name of any element type.
The below rule renders the content of every element in our document in black.

```javascript
* {
    color: #000000;
}
```

### Descendant Selectors

Suppose you want to apply a style rule to a particular element only when it lies inside a particular element. As given in the following example, style rule will apply to <em> element only when it lies inside <ul> tag.

```javascript
ul em {
   color: #000000;
}
```

### Child Selectors

```javascript
ul em {
   color: #000000;
}
```

## Linking External CSS file

```

```
