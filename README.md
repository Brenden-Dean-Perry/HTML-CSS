# HTML-CSS
A demo repo to document and cover HTML & CSS concepts and examples.

## Overview
HTML stands for HyperText Markup Language. 
It is the standard markup language used to create web pages. 
HTML adds the building blocks of a web page, such as text, images, links, and other multimedia elements.

HTML describes the structure of a web page using a series of elements and tags.
For example, the `<p>` tag is used to define a paragraph, while the `<a>` tag is used to create a hyperlink.

HTML is not a programming language, but rather a markup language that provides the structure and content of a web page. 

It is not a case-sensitive language, meaning that tags can be written in uppercase or lowercase. 
However, it is a common convention to write tags in lowercase for consistency and readability.
White space in HTML is generally ignored, meaning that multiple spaces, tabs, and line breaks are treated as a single space. 
However, there are certain elements, such as `<pre>`, that preserve white space.

Even <p>Hello   world</p> will be rendered as "Hello world" in the browser, with only a single space between "Hello" and "world".

 ## Language Comparison

 ### HTML vs CSS
 HTML is used to structure the content of a web page, while CSS (Cascading Style Sheets) is used to style and layout the content.
 
 They work together to create visually appealing and well-structured web pages.
 CSS applies styles to HTML elements, allowing developers to control the appearance of the web page, such as colors, fonts, and layout.

 ### HTML vs JavaScript
 HTML is used to structure the content of a web page, while JavaScript is a programming language that is used to add interactivity and dynamic behavior to web pages.

 ### JavaScript vs TypeScript
 JavaScript is a programming language that is commonly used for web development.
 TypeScript is a superset of JavaScript that adds static typing and other features to the language.

 TypeScript can help catch errors at compile time and improve code maintainability, while JavaScript is more flexible and widely supported across different environments.

 Can be used together in a project, with TypeScript being transpiled to JavaScript for execution in the browser.
 TypeScript cannot run directly in the browser, but it can be transpiled to JavaScript using tools like the TypeScript compiler (tsc) or Babel.

## Basics of web development
Web development is the process of creating websites and web applications.

To create a web page, you need to use a combination of HTML, CSS, and JavaScript.
- HTML is used to structure the content of the web page.
- CSS is used to style the web page, such as changing colors, fonts, and layout.
- JavaScript is used to add interactivity to the web page, such as handling user input and creating dynamic content.

When you navigate to a web page, your browser sends a request to the server, which then responds with the HTML, CSS, and JavaScript files needed to render the page. 
The browser then processes these files and displays the web page to the user.

URL stands for Uniform Resource Locator.

Resource refers to any item that can be accessed on the web, such as a web page, an image, a video, fonts, or a file.

It is the address used to access a web page on the internet.
A URL typically consists of several parts:
- Protocol: This specifies the method used to access the resource, such as `http` or `https`. The `https` protocol is more secure than `http` because it encrypts the data transmitted between the browser and the server. HTTP stands for HyperText Transfer Protocol, while HTTPS stands for HyperText Transfer Protocol Secure.
- Domain: This is the unique name that identifies the website, such as `www.example.com`.
- Path: This specifies the specific page or resource being accessed, such as `/about` or `/contact`.
- Query Parameters: These are optional parameters that can be added to the URL to provide additional information, such as `?id=123` or `?search=html`.
- Fragment: This is an optional part of the URL that specifies a specific section of the page, such as `#section1` or `#top`.
- Port: This is an optional part of the URL that specifies the port number used to access the resource, such as `:80` for HTTP or `:443` for HTTPS.
- Username and Password: These are optional parts of the URL that can be used for authentication, such as `username:password@` before the domain name.
- Subdomain: This is an optional part of the URL that can be used to specify a subdomain, such as `blog.example.com` or `shop.example.com`.
- Top-Level Domain (TLD): This is the last part of the domain name, such as `.com`, `.org`, or `.net`.
- IP Address: Instead of a domain name, a URL can also use an IP address to access a resource, such as `http://192.168.1.1`.

### The Document Object Model (DOM)
When a browser receives an HTTP document, it parses the HTML content, creates a Document Object Model (DOM) tree, and then renders the page based on the structure defined by the HTML.
The browser also applies CSS styles to the elements in the DOM tree and executes any JavaScript code included in the HTML document to create an interactive web page.
The DOM contains all the elements of the web page, such as headings, paragraphs, images, links, and other multimedia content.

## Basic Structure of an HTML Document
The basic structure of an HTML document includes the following elements:
```html
 <!DOCTYPE html>
 <html lang="en">
   <head>
	 <meta charset="UTF-8">
	 <meta name="viewport" content="width=device-width, initial-scale=1.0">
	 <title>Page Title</title>
   </head>
   <body>
	 <h1>This is a Heading</h1>
	 <p>This is a paragraph.</p>
   </body>
 </html>
 ```

 ## Tags vs Attributes vs Element
 In HTML, tags are used to define elements, while attributes provide additional information about those elements.
 For example, in the `<a>` tag, `href` is an attribute that specifies the URL of the link:
 ```html
 <a href="https://www.example.com">Visit Example</a>
 ```

 Another example is the `<img>` tag, where `src` is an attribute that specifies the path to the image:
 ```html
 <img src="image.jpg" alt="Description of the image">
 ```

 ## Abolute vs Relative References
 Absolute references specify the full URL of a resource, while relative references specify the path to a resource relative to the current document.
 For example, an absolute reference to an image might look like this:
 ```html
 <img src="https://www.example.com/images/photo.jpg" alt="Photo">
 ```
 A relative reference to the same image might look like this:
 ```html
 <img src="images/photo.jpg" alt="Photo">
 ```

 ## Explanation of the Structure & Elements

 Primary elements include:
 - `<!DOCTYPE html>`: This declaration defines the document type and version of HTML being used.
 - `<html>`: This is the root element of an HTML document. It contains all other elements. can also include a `lang` attribute to specify the language of the document.
 - `<head>`: This section contains meta-information about the document, such as the title, character set, and links to stylesheets.
 - `<meta charset="UTF-8">`: This tag specifies the character encoding for the document, ensuring that it can display a wide range of characters correctly.
 - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: This tag ensures that the web page is responsive and displays correctly on different devices and screen sizes.
 - `<title>`: This element specifies the title of the web page, which is displayed in the browser's title bar or tab included in head section.
 - `<body>`: This section contains the content of the web page that is displayed to users, such as text, images, and links.
 
 Text elements:
 - `<h1>`: This tag defines a top-level heading, which is typically used for the main title of the page.
 - `<h2>`, `<h3>`, etc.: These tags define subheadings of different levels, used to organize content hierarchically.
 - `<p>`: This tag defines a paragraph of text.
 - `<a>`: This tag defines a hyperlink, which can be used to link to other web pages or resources.
 - `<br>`: This tag defines a line break, which is used to create a new line of text without starting a new paragraph.
	
Inline elements:
 - `<span>`: This tag is used to group inline elements and apply styles or attributes to them without affecting the layout of the document.
 - `<strong>`: This tag is used to indicate that the text is of strong importance, typically displayed in bold.
 - `<em>`: This tag is used to indicate emphasis on text, typically displayed in italics.
 - `<abbr>`: Tooltip declaration. This tag is used to define an abbreviation or acronym, providing a tooltip with the full term when hovered over.
	- Example: `<abbr title="HyperText Markup Language">HTML</abbr>` will display "HTML" with a tooltip that shows "HyperText Markup Language" when hovered over.

Symbols (Entitys):
- &lt: This tag is used to display the less-than symbol (<) in HTML, which is otherwise reserved for defining tags.
- &gt: This tag is used to display the greater-than symbol (>) in HTML, which is also reserved for defining tags.
- &nbsp: This tag is used to create a non-breaking space in HTML, which prevents the browser from breaking a line of text at that point.
	- Example: `Hello&nbsp;World` will display as "Hello World" without breaking the line between "Hello" and "World".
	- Another example: `&nbsp;&nbsp;&nbsp;Indented Text` will create an indented effect by adding multiple non-breaking spaces before the text.


 The index.html is the main entry point of the website. 
 It is the file that is loaded when a user visits the website.

 ## Terms
 Block-level elements: These elements typically start on a new line and take up the full width of their container. Examples include `<div>`, `<p>`, and `<h1>`.
 For example:
 ```html
 <div>This is a block-level element.</div>
 <p>This is another block-level element.</p>
 ```

 Inline elements: These elements do not start on a new line and only take up as much width as necessary. Examples include `<span>`, `<a>`, and `<img>`.
 For example:
 ```html
 <p>This is an inline element: <span>Span text</span></p>
 <p>This is a hyperlink: <a href="https://www.example.com">Example</a></p>
 <p>Emphasized text: <em>Emphasized</em></p>
 ```

 ## Browser Rendering
 When a user visits a website, the browser retrieves the HTML document and renders it on the screen. 
 This process involves parsing the HTML, applying CSS styles, and executing any JavaScript code to display the final web page to the user.

 ### Security Note
 HTML can be inspected within the browser.
 Not all HTML is visible on the page, as some elements may be hidden or styled in a way that makes them invisible. 
 Comment elements (`<!-- comment -->`) are also not visible on the page, as they are meant for developers to include notes or explanations within the HTML code.
 However, all HTML elements, including hidden ones and comments, can be viewed by inspecting the page source or using developer tools in the browser.
 Do not rely on HTML elements being hidden or invisible for security purposes, as they can still be accessed and viewed by users through inspection tools.
 HTML is rendered on the client side, meaning that it is processed and displayed by the user's browser so do not include sensitive information in the HTML code, as it can be easily accessed by users.

  ## CSS
 To write CSS with an HTML document we need to add a style element <style>.

Example:
```html
<style>
  body {
	background-color: lightblue;
  }
  h1 {
	color: white;
	text-align: center;
  }
  p {
	font-family: verdana;
	font-size: 20px;
  }
</style>
```

The first word in the CSS rule is called a selector, which specifies the HTML element to which the styles will be applied. 
In the example above, `body`, `h1`, and `p` are selectors that target the `<body>`, `<h1>`, and `<p>` elements in the HTML document, respectively.

Inside the brackets `{}`, we have a declaration block that contains one or more declarations. 
Each declaration consists of a property and a value, separated by a colon `:`, and ends with a semicolon `;`.

Example:
```css
body {
  background-color: lightblue;
  }
```

In this example, `background-color` is the property, and `lightblue` is the value.

We can also write CSS in an external file and link it to the HTML document using the `<link>` element in the `<head>` section.
Example:
```html
<link rel="stylesheet" href="styles.css">
```

In this example, `rel="stylesheet"` specifies that the linked file is a stylesheet, and `href="styles.css"` specifies the path to the CSS file.

Instead of calling selectors by their tag name, we can also use classes and IDs to target specific elements in the HTML document.
Example:
```html
<p class="my-class">This is a paragraph with a class.</p>
<p id="my-id">This is a paragraph with an ID.</p>
```

In this example, we have added a class called `my-class` to the first paragraph and an ID called `my-id` to the second paragraph.
We can then target these elements in our CSS using the class selector (.) and ID selector (#).
Example:
```css
.my-class {
  color: blue;
  }
  #my-id {
  color: red;
  }
  ```


  Helpful hints:
	- Use classes when you want to apply the same styles to multiple elements, and use IDs when you want to target a specific element that is unique on the page.
	- To make your CSS more efficient, try to avoid using overly specific selectors, as they can make it harder to maintain and update your styles in the future. Instead, use more general selectors and combine them with classes or IDs as needed.
	- To make round buttons, you can use the `border-radius` property in CSS. For example, `border-radius: 50%;` will create a circular button, while `border-radius: 10px;` will create a button with rounded corners. Circular buttons are achievable by setting the border-radius to 50% the height and width of the button, while rounded corners can be achieved by setting a specific pixel value for the border-radius property. Which makes intutive sense becuase a radius of 50% mean the radius is half the size of the button, creating a perfect circle.
	- There are multiple ways to change the size of elements in CSS, such as using the `width` and `height` properties, or using padding and margin to adjust the spacing around elements. Using padding and margin can be more flexible and responsive, as it allows you to adjust the spacing around the element content so you do not have to worry about the actual size of the element, which can be helpful when designing for different screen sizes and devices. However, using width and height can be more precise when you want to set specific dimensions for an element, such as a fixed-size image or button.

### Pseudo-classes, Pseudo-elements, and Transitions

To apply effects to elements when the user interacts with them, we can use pseudo-classes in CSS.

For example, the `:hover` pseudo-class allows us to change the style of an element when the user hovers over it with their mouse.
Example:
```css
button:hover {
  background-color: lightgreen;
  }
 ```

 In this example, when the user hovers over a button element, its background color will change to light green.

 Transitions allow us to create smooth animations when the styles of an element change.
 Example:
 ```css
 button {
  background-color: lightblue;
  transition: background-color 0.3s ease;
  }
  ```
  In this example, when the background color of the button changes (such as on hover), it will transition smoothly over 0.3 seconds with an easing function of "ease".
  We need to specify the property we want to transition (in this case, `background-color`), the duration of the transition (0.3 seconds), and the easing function (ease) to control the speed of the transition.

  Transitions can be applied to various CSS properties, such as `color`, `width`, `height`, `opacity`, and more, allowing for a wide range of animation effects on web elements.
  Transitions should always be set on the element's default state, not on the state that triggers the transition (like `:hover`), to ensure that the transition effect works correctly when the state changes.


 ## Validation
 ### HTML Validation
 HTML validation is the process of checking an HTML document against a set of rules and standards to ensure that it is well-formed and follows best practices.
 Validating HTML can help identify and fix errors in the code, improve accessibility, and ensure that the web page is displayed correctly across different browsers and devices.
 There are various tools available for validating HTML, such as the W3C Markup Validation Service, which checks the HTML code against the official HTML specifications and provides feedback on any errors or warnings found in the code.
 
 To use, go to https://validator.w3.org/ to validate your HTML code.

 ### CSS Validation
 
CSS Valiation can be done at https://jigsaw.w3.org/css-validator/
