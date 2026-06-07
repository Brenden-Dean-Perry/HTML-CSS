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
 - `<!DOCTYPE html>`: This declaration defines the document type and version of HTML being used.
- `<html>`: This is the root element of the HTML document that contains all other elements.
- `<head>`: This section contains meta-information about the document, such as the title, character encoding, and links to external resources like CSS and JavaScript files.
- `<body>`: This section contains the content of the web page that is displayed to the user, such as text, images, links, and other multimedia elements.

The <HTML> <Head> <Body> are three the main elements of an HTML document, and they define the structure and content of the web page.

The basic structure of an HTML document can be represented as follows:

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

 Note: The `<!DOCTYPE html>` declaration is important as it tells the browser to render the page in standards mode, ensuring that the HTML is interpreted correctly.
 The `<html lang="en">` attribute specifies the language of the document, which can help with accessibility and search engine optimization (SEO).
 Initial-scale=1.0 in the viewport meta tag ensures that the page is displayed correctly on different devices, especially mobile devices.

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

 ### Difference between block and inline elements
 Important concept!
 Block elements take up the full width of the page and start on a new line, while inline elements only take up as much width as necessary and do not start on a new line.

 Examples of block elements include `<div>`, `<p>`, `<h1>`, and `<ul>`, while examples of inline elements include `<span>`, `<a>`, and `<strong>`.

 However, it is important to note that some elements can be both block and inline depending on their context and the CSS styles applied to them.
 For example, the `<a>` tag is typically an inline element, but it can be styled with CSS to behave like a block element if needed.
 Alternatively, the `<div>` tag is typically a block element, but it can be styled with CSS to behave like an inline element if needed where it does not take up the full width of the page and does not start on a new line.

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

 ## Div vs Span
 The `<div>` element is a block-level element that is used to group other elements together and apply styles or attributes to them. It is often used for layout purposes.
 Div stands for "division" and is used to create sections or containers in a web page. 

 Span, on the other hand, is an inline element that is used to group inline elements together and apply styles or attributes to them without affecting the layout of the document. 
 It is often used for styling specific parts of text or other inline content.
 For example, you might use a `<div>` to create a section of a web page, and then use `<span>` elements within that section to style specific words or phrases:
 ```html
 <div class="section">
   <h2>Section Title</h2>
   <p>This is a paragraph with a <span class="highlight">highlighted</span> word.</p>
   </div>
```

Div and spans used to be used often for layout purposes, but with the advent of CSS and modern web design practices, they are now primarily used for styling and grouping content rather than for layout.
Most modern web design relies on CSS for layout and styling, and the use of divs and spans is often limited to specific cases where they are needed for grouping or styling purposes.

HTML5 introduced new semantic elements that provide more meaningful structure to web pages, such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`. 
These elements help improve the accessibility and SEO of web pages by providing clear indications of the different sections and their purposes.
These semantic elements should be used instead of generic `<div>` elements whenever possible to enhance the structure and meaning of the content on a web page.

But it's important to note that divs and spans are still widely used in web development, especially for cases where specific styling or grouping is needed that cannot be achieved with semantic elements alone.

## Nested layout technique
The nested layout technique is a method of structuring HTML documents by nesting elements within each other to create a hierarchical layout.
This technique allows developers to create complex layouts and organize content in a way that is both visually appealing and semantically meaningful.

Layouts can be horizontal or vertical. These can be combined to create more complex layouts. 
For example, a common layout is a header at the top, a sidebar on the left, and main content in the center.
You can build any layout you want by nesting elements within each other and applying CSS styles to them.

## Advanced CSS Layouts
The two most common advanced CSS layout techniques are Flexbox and Grid.
- Grid is a two-dimensional layout system that allows you to create complex layouts with rows and columns. It is particularly useful for creating grid-based designs, such as photo galleries or product listings.
- Flexbox, on the other hand, is a one-dimensional layout system that allows you to create flexible and responsive layouts. It is particularly useful for creating layouts that need to adapt to different screen sizes, such as navigation menus or card layouts.

When using Flexbox, you can control the direction of the layout using the `flex-direction` property. 
Other common properties include `justify-content`, which controls the alignment of items along the main axis, and `align-items`, which controls the alignment of items along the cross axis.

Setting flex=1 on a child element of a flex container will make that element grow to fill the available space in the container. This is because the `flex` property is a shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`. 
When you set `flex: 1`, it means that the element should grow to fill any available space in the container, while also allowing it to shrink if necessary and setting its initial size to 0.

Example of a flex container with flex-direction set to row and column-reverse:

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

 Note: style elements should be placed within the head section of the HTML document to ensure that the styles are applied correctly when the page loads.

Example:
```html
<head>
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
</head>
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

  You can also target element attributes. 
  For example, you can target all `<a>` elements with a specific `href` attribute value:
  ```css
  a[href="https://www.example.com"] {
  color: green;
  }
  ```
  This will apply the specified styles to all `<a>` elements that have an `href` attribute with the value "https://www.example.com".

  You can also target specific parts of an element using pseudo-elements in CSS.
  ```css
  .input::placeholder {
  color: gray;
  }
  ```
  This example targets the placeholder text of input elements with the class `input` and sets the color to gray.

  Helpful hints:
	- Use classes when you want to apply the same styles to multiple elements, and use IDs when you want to target a specific element that is unique on the page.
	- To make your CSS more efficient, try to avoid using overly specific selectors, as they can make it harder to maintain and update your styles in the future. Instead, use more general selectors and combine them with classes or IDs as needed.
	- To make round buttons, you can use the `border-radius` property in CSS. For example, `border-radius: 50%;` will create a circular button, while `border-radius: 10px;` will create a button with rounded corners. Circular buttons are achievable by setting the border-radius to 50% the height and width of the button, while rounded corners can be achieved by setting a specific pixel value for the border-radius property. Which makes intutive sense becuase a radius of 50% mean the radius is half the size of the button, creating a perfect circle.
	- There are multiple ways to change the size of elements in CSS, such as using the `width` and `height` properties, or using padding and margin to adjust the spacing around elements. Using padding and margin can be more flexible and responsive, as it allows you to adjust the spacing around the element content so you do not have to worry about the actual size of the element, which can be helpful when designing for different screen sizes and devices. However, using width and height can be more precise when you want to set specific dimensions for an element, such as a fixed-size image or button. See box model below for more information.
	- Vertical-align is used to align inline elements vertically within a line of text. It can be used to align text, images, or other inline elements to the top, middle, or bottom of the line. For example, `vertical-align: middle;` will align the element to the middle of the line, while `vertical-align: top;` will align it to the top of the line. This property is particularly useful when you want to align images or icons with text in a visually appealing way.

### Box Model

The box model is a fundamental concept in CSS that describes how elements are structured and how they interact with each other on a web page.

The box model consists of four main components:
1. Content: This is the innermost part of the box, where the actual content of the element is displayed (e.g., text, images).
2. Padding: This is the space between the content and the border of the element. It can be used to create space around the content within the element.
3. Border: This is the line that surrounds the padding and content of the element. It can be styled with different colors, widths, and patterns.
4. Margin: This is the outermost part of the box, which creates space between the element and other elements on the page. It can be used to create separation between elements and control the layout of the page.

The box model is important to understand because it affects how elements are sized and positioned on a web page. 
When you set the width and height of an element, you are actually setting the size of the content area, and the padding, border, and margin will be added to that size to determine the total size of the element on the page.

Since HTML ignores whitespace, you can use the box model to create space between elements without relying on extra spaces in the HTML code.
For example, if you want to create space between two paragraphs, you can use the margin property in CSS to add space around the paragraphs instead of adding extra spaces in the HTML code.
```css
p {
  margin-bottom: 20px; /* Adds space below each paragraph */
}
```
This will create a 20px space below each paragraph, making the layout cleaner and more consistent across different browsers and devices.

Alternatively, you can use padding with a span element to create space within an element without affecting the overall layout of the page.
```html
<p>This is a paragraph with <span style="padding: 10px;">extra space</span> around the text.</p>
```
In this example, the span element has a padding of 10px, which creates extra space around the text "extra space" without affecting the layout of the entire paragraph. 
This can be useful for creating visual separation or emphasis within a block of text.

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

  ## Scriping
  Using the `<script>` tag, we can include JavaScript code in our HTML document to add interactivity and dynamic behavior to our web pages.
  For example, we can use JavaScript to create a simple alert message when a button is clicked:
  ```html
  <button onclick="alert('Button clicked!')">Click me</button>
  ```

  Alternatively, we can include an external JavaScript file using the `src` attribute of the `<script>` tag:
  ```html
  <script src="script.js"></script>
  ```
  This will load the JavaScript code from the `script.js` file and execute it when the page loads.

  Or we can write JavaScript code directly within the `<script>` tag:
  ```html
  <script>
  function showAlert() {
	alert('Hello, World!');
  }
  </script>
  <button onclick="showAlert()">Click me</button>
  ```

  Generally, it's best practice to place the `<script>` tag just before the closing `</body>` tag to ensure that the HTML content is fully loaded before the JavaScript code runs. This helps prevent issues with accessing DOM elements that may not yet be available when the script executes.

  This project is not intended to cover JavaScript in depth, but it is important to understand how to include and use JavaScript in your HTML documents to create interactive and dynamic web pages.

  For more JavaScript resources, you can check out the following:
  https://github.com/Brenden-Dean-Perry/JavaScript

 ## Validation
 ### HTML Validation
 HTML validation is the process of checking an HTML document against a set of rules and standards to ensure that it is well-formed and follows best practices.
 Validating HTML can help identify and fix errors in the code, improve accessibility, and ensure that the web page is displayed correctly across different browsers and devices.
 There are various tools available for validating HTML, such as the W3C Markup Validation Service, which checks the HTML code against the official HTML specifications and provides feedback on any errors or warnings found in the code.
 
 To use, go to https://validator.w3.org/ to validate your HTML code.

 ### CSS Validation
 
CSS Valiation can be done at https://jigsaw.w3.org/css-validator/
