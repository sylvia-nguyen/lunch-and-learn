# lunch-and-learn: Meet your best friend the Dev Tools ✨

We are going to learn how the developer tools works and how to leverage this knowledge to empower all of you to dig into a bit of code when necessary. This L&L is applicable to all disciplines 🎉


## Why should we learn the Dev Tools?

For developers, the DevTools let's use see the styles that are used, the size of the images, the scripts that are used, etc. You can debug and know what errors exist on the page. You can even toggle styles on or off, or change them completely, to see what effect it has on your website.

## What the DevTools will help us with:
- Tightening up the feedback loop
- QA-ing website designs and content
- Quick way to prototype
- Performance and accessibility audits
- Deubugging

## What is HTML?
HTML stands for Hyper Text Markup Language. It is the content of a webpage made-up of semantic block elements.
Semantic block elements for headings look like this:
```HTML
 <h1>This is very important content</h1>

 <h2>This is pretty important too</h2>

 <h3>This is not as important</h3>

 <h4>This is less important</h4>
```


## What is CSS?
CSS stands for Cascading Style Sheets. It is how we style our content. 

```css
 .cool {
    color: red;  
  }
```

## HTML Attributes
- class names
```HTML
 <h2 class="cool"></h2>
```
- ids
```HTML
 <h2 class="cool" id="superUnique"></h2>
```
- href for anchors
```HTML
 <a href="www.cool.com">
```


## HTML Anatomy
- The standard for how an HTML page is structured. 
```HTML
 <html lang="en">
 <head>
  <meta charset="UTF-8">
  <title>Document</title>
 </head>
 <body>
   <h1>I am really really important and cool text</h1>
 </body>
 </html>
```

## CSS
- Stying classes
```css
 .cool {
    color: red;  
  }
```
- Positioning
```css
 .cool {
   position: relative;
   left: 10px;
   top: 10px;  
  }
```
- Margins
```css
 .cool {
   margin-top: 10px;
   margin-left: 10px;
   margin-bottom: 10px;
   margin-right: 10px;
  }
```
- Borders
```css
 .cool {
   border: 1px solid #bada55;
  }
```
- Units (PX, EM, REM)
```css
 .cool {
   font-size: 2px;
   font-size: 2em;
  }
```
-Inheritance
```css
 body {
   font-size: 15px
 }
  
 .cool {
   color: goldenrod;
   width: 250px;
   background-color: black; 
 }
```

-Specificity
```css
 body {
   font-size: 15px
 }
  
 .cool {
   color: goldenrod;
   width: 250px;
   background-color: black; 
   font-size: 20px;
 }
```

- Cascade
```css
  .cool {
   color: #bada55;
 }
  
  .cool {
    color: green;
  }
```



## Ready to code in the DevTools!

We will be using Google chrome's DevTools today. You can access the DevTools

## Explore the following:

### HTML
- Explore the selector/pointer tool
- Update some content in the HTML
- Move HTML blocks around
- Remove / toggle elements
- Download an image
- Upload an image
- Check if devs are using semantic elements in the right places

### CSS
- Change font size, width, height, background-color, color
- Explore color picker (sometimes developers fuck up the colors)
- Contrast Ratio (AA, AAA)
- Use margin, padding, or positing to move elements around (hack spacing)
- Borders and borders-radius for rounded corners
- Styling on hover states

### Testing
- Toggle device tool bar: Desktop, tablet, mobile
- Resizing the browser at specific breakpoints 
- Perform page audits and seek opportunities for improvement





