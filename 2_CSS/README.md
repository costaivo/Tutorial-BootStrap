# CSS

Mixing content and presentation is difficult to maintain. 
CSS helps seperate presentation rules with structrue

### Add style to HTML page
<head>
  ...
<style type="text/css">
  body {background-color:red}
 </style>
 </head>
 
 
 ### Add styles in seperate page. 
 Adding styles in seperate page allow the same styles to applies across multiple pages
 
 styles.css
 -----------
  body {background-color:red}
  
  index.html
  ----------
  <head>
  <link rel="stylesheet" href="styles.css" type="text/css" />
  </head>
 
 
 
 ### Adding another CSS rule 
 p{ 
 font-size:larger;
 }
 
