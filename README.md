# HTML
A demo repo to document and cover HTML concepts and examples.

## Overview
HTML stands for HyperText Markup Language. 
It is the standard markup language used to create web pages. 

HTML describes the structure of a web page using a series of elements and tags.
For example, the `<p>` tag is used to define a paragraph, while the `<a>` tag is used to create a hyperlink.

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

 ## Tags vs Attributes
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

 ## HTML Validation
 HTML validation is the process of checking an HTML document against a set of rules and standards to ensure that it is well-formed and follows best practices.
 Validating HTML can help identify and fix errors in the code, improve accessibility, and ensure that the web page is displayed correctly across different browsers and devices.
 There are various tools available for validating HTML, such as the W3C Markup Validation Service, which checks the HTML code against the official HTML specifications and provides feedback on any errors or warnings found in the code.
 
 To use, go to https://validator.w3.org/ to validate your HTML code.

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