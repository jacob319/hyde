---
published: true
---
### Intro to HTML

So what is [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
>HTML (HyperText Markup Language) is the most basic building block of the Web. It describes and defines the content of a webpage. Other technologies besides HTML are generally used to describe a webpage's appearance/presentation (CSS) or functionality/behavior (JavaScript).

So HTML has these elements that are tags such as heading tags`<h1> Hello World </h1>,<h2>Hello World</h2>`, paragraph tags `<p>Hello World</p>` as you can see each tag has a opening tag `<h1>, <p>`, and a closing tag `</h1>,</p>`. 

So here's a example of a HTML page:
```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```





### INTRO To CSS

 [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) brings color and style to ones website. Brings  a little pop too something interesting to your site that views will enjoy.
>Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.

CSS can either be written between the head tags, include in the element tag, or in a separate css file. OK to use CSS between the head tags which is called <em>internal Style Sheet</em> let's use some style tags: `<style>h1{ backgroud-color:yellow;}</style>`:
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My CSS experiment</title>
    <style>
      body {
         background-color: yellow;
     }
   </style>
  </head>
  <body>
    <h1>Look at me!</h1>
    <p> See writing CSS not that hard.</p>
  </body>
</html>
```
 One can also link a css file which will hold the style for the HTML page: `<link rel="stylesheet" href="style.css">`. Now let me show you what I mean:

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My CSS example</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <h1>Look at you writing HTML and CSS!</h1>
    <p>I knew you could do it.</p>
  </body>
</html>
```
So let's write some CSS for our HTML that's above remember this will be written in a file called style.css

```
h1 {
  color: purple;
  background-color: yellow;
  border: 1px solid black;
}

p {
  color: green;
}
```
OK here we go so the `<h1>` header tag yep the text is purple. Also has a background color of yellow, a solid black border that's 1 pixel wide. The last tag `<p>` is a paragraph tag which text is green yep Hulk green. 

So there you have it a short intro to HTML and CSS to learn more head over to [MDN Web Docs](https://developer.mozilla.org/en-US/).
