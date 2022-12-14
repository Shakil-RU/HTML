# HTML
 - [Online Code Editor](https://codepen.io/pen/)
 
 # HTML Documentation
 
### Total Chapters are as follows
1. Introduction
2. Typography
3. List, Link, Media
4. Table & Form
5. HTML5 Sematic Elements
6. Web Accessibility
7. HTML Graphics
8. Projects

## Chapter 1: Introduction

### [1.1 Introduction to HTML]()

#### What is HTML & Why HTML?

- HTML stands for Hyper Text Markup Language
- It is not a **programming language**
- HTML helps us to create the main structure of a webpage
- With the help of markup tag we can display text, image, video etc. on the webpage

#### History of HTML

- Tim Berners-Lee created HTML in 1991
<br />

### [1.2 Tag, content, attribute, element]()

#### What is Tag & its syntax?

- Tag is the heart of html; HTML document is mainly built with tag.
- Tag Syntax: `<keyword>` ; Inside the angular brackets we need to write predefined keywords to use html tag.
- Small / capital letters both can be used when writing html tag; however small letter is prefered.
- Example: `<p> This is a paragraph </p>`
- In the example, `<p>` is an opening tag, `</p>` is a closing tag and `This is a paragraph` is called content
- In between the starting tag to end tag we have content
- Everything from starting tag to end tag is called Element

#### What are the types of Tag?

- There are 2 types of html tag: Pair/container tag and empty tag
- Pair tag has starting and ending; However, empty tag has no closing tag.
- Some of the example of pair tag and empty tags are given below:

  ```html
  <!-- Some examples of Pair/Container Tag -->
  <html>
    ...
  </html>
  <head>
    ...
  </head>
  <body>
    ...
  </body>
  <p>...</p>
  <h1>...</h1>
  ....

  <!-- Some examples of Empty Tag -->
  <br />
  <hr />
  <img />
  <input />
  ...
  ```

#### What is attribute & how to use attribute?

- Attribute helps tag to extend its capabilities
- In the following example, `<img/>` is tag; src, height, width are the attributes
  ```html
  <img src="anis.jpg" height="200" width="200" />
  ```
- Attribute Syntax: `attributeName="attributeValue"`

<br />

### [1.3 Structure of an HTML document]()

#### HTML basic structure

- HTML document has 2 important part: head, body
- In the following example a basic structure of a HTML document

  ```html
  <!DOCTYPE html>
  <html>
    <head>
      TITLE, META TAG ETC.
    </head>
    <body>
      CONTENT OF THE WEBPAGE
    </body>
  </html>
  ```

- Always use `<!DOCTYPE html>` to tell the browser what type of document to expect; remember it is not a tag, just a declaration
- Every HTML document must have `<html>` pair tag and Inside `<html>` tag we use `<head>` and `<body>` as the example shows above.
- Inside head tag we use meta tag, set title etc.
- Inside body tag we write everything that we want to display on web page.

#### Environment setup

- Editor: VScode / Notepad++ / Sublime
- Browser: Google Chrome / Firefox
- Version Control: GitHub

<br/>

### [1.4 First HTML Program]()

#### Example of a basic webpage

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
  </head>
  <body>
    This is my first webpage <br />
    I am Abdullah Numan Shakil <br />
    A full stack web developer & Competitive Programmer<br />
  </body>
</html>
```

- Here, lang attribute refers to the language; attribute value en refers to english
- Inside `<head>` tag we have set title of the webpage using `<title>` tag
- Inside `<body>` tag we are displaying some text. here `<br/>` tag creates a line break

<br/>

### [1.5 Inside Head Tag]()

#### Example

```html
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Free complete html tutorials 2022" />
  <meta name="keywords" content="HTML, html, html5" />
  <meta name="author" content="Shakil Hossan" />
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      background-color: aquamarine;
    }
  </style>
  <script src="index.js"></script>
  <title>Document</title>
</head>
```

- Inside `<head>` tag we can define metadata(document title, character set, links, scripts, styles), other information that will not be visible to the users
- meta tag provides information to the browsers and search engines about the webpage
- `<meta charset="UTF-8" />` defines the character encoding for the HTML document.
- `<meta http-equiv="X-UA-Compatible" content="IE=edge" />` for supporting older version of IE.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0" />` defines that webpage width is related to devices width and initial zoom level is 1.
- `<link rel="stylesheet" href="style.css">` generally connects css file to html. Inside of href attribute we give the css file name.
- `<style> ... </style>` we can use `<style> ... </style>` tag directly inside the head tag for designing html elements.
- `<script src="index.js"></script>` generally connects js file to html. we can also use `<script> ... </script>` tag directly inside the body tag.

<br/>

### [1.6 Debugging](https://youtu.be/ApmhBx908Ik)

- After writing your html code you can check the validity on this website https://validator.w3.org/

<br/>
<br/>

