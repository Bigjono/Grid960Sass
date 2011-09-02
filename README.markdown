# SASS Template for Grid960
 ==========================================
This is a SASS of Grid960 css framework (http://960.gs/)

For more information about SASS please visit http://sass-lang.com/

If you wish to use this with your .net project I highly recommend installing Mindscape Web Workbench (http://www.mindscapehq.com/products/web-workbench) 
a free SASS, .Less and CoffeeScript plugin for Visual Studio 2010.


## Example Usage
===================================
Setup your body font

```html 

$mysite-font-family:unquote("'Times New Roman',Arial");
  
@import "reset";

@import "text";

@import "grid960";

@include text($mysite-font-family);

```

##	Delete as appropriate 
====================================
```html  
//   Grid 960 - 12 Columns 
@include grid960(12); // 12 Columns  
 
//   Grid 960 - 16 Columns 
@include grid960(16); // 16 Columns

For 24 Column Grid 960 
@include grid960(24); // 24 Columns `
``` 
 
On your html page simply use a div with an ID of container.   This is the only difference between grid960 
and grid960SaSS


```html
<div id="container">


Your site here 


</div>
```