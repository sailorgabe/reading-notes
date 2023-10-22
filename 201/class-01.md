# **What is JavaScript?**

## **Compose a short poem describing how HTTP sends data between computers.**

In the realm where data streams dance and flow,
HTTP, a messenger, sets the tempo.
Between computers, it weaves its web so fine,
A protocol of connection in digital rhyme.

With requests and responses, it paints the scene,
A ballet of information, graceful and keen.
From client to server, like whispers in the night,
HTTP carries our words with digital might.

In packets and headers, it crafts its tale,
Through networks and routers, it sets sail.
A symphony of ones and zeroes in the air,
HTTP bridges the gap, with utmost care.

So let us marvel at this digital art,
HTTP, the conduit of our digital heart.
In the world of bytes, it's a conductor's wand,
Sending data between computers, far beyond.

## **Describe how HTML, CSS, and JS files are “parsed” in the browser.**

When a web browser loads a webpage, it undergoes a process known as parsing, which involves interpreting and rendering HTML, CSS, and JavaScript files. Here's how each of these file types is parsed:

1. **HTML (Hypertext Markup Language) Parsing:**
   - HTML parsing begins as soon as the browser receives the HTML file from the web server.
   - The browser's HTML parser reads the HTML document sequentially from top to bottom.
   - It identifies elements, tags, and their attributes, and constructs a Document Object Model (DOM) tree, which represents the structure of the webpage.
   - While parsing, it also fetches external resources like images, stylesheets, and scripts, and may initiate additional requests for them.

2. **CSS (Cascading Style Sheets) Parsing:**
   - CSS parsing occurs after the HTML parsing is underway.
   - The browser's CSS parser reads the CSS files linked within the HTML document.
   - It processes CSS rules, selectors, and properties, and generates a CSS Object Model (CSSOM).
   - The CSSOM defines the styling rules that will be applied to elements in the DOM.

3. **JavaScript (JS) Parsing:**
   - JavaScript parsing occurs after both HTML and CSS parsing.
   - If there are JavaScript files linked or embedded within the HTML, the browser fetches and parses them.
   - The JavaScript parser interprets the JavaScript code, looking for syntax errors.
   - If there are no errors, it executes the script, modifying the DOM and CSSOM as needed.
   - JavaScript execution can also make network requests, handle user interactions, and perform various tasks to enhance interactivity and functionality.

It's important to note that parsing is not always a linear process. Modern browsers use techniques like speculative parsing and asynchronous loading to optimize page loading speed. For example, they may start downloading CSS and JavaScript files while still parsing the HTML. Additionally, some JavaScript files may be deferred or loaded asynchronously to prevent blocking the rendering of the page.

Once parsing is complete, the browser combines the DOM and CSSOM to create a render tree, which is used to generate the visual layout of the webpage. The render tree is then used to render the final display on the user's screen.

This complex process ensures that web pages are displayed correctly, with the proper structure, styling, and interactivity as defined by the HTML, CSS, and JavaScript files.

## **How can you find images to add to a Website?**

You can utilize Google Images or other search engines and filter copyrighted images out to prevent any illegal use of copyrighted material in your website. You can also use your own material that can be uploaded to your website.  

## **How do you create a String vs a Number in JavaScript?**

In JavaScript, you can create both strings and numbers using different syntax and data types. Here's how to create strings and numbers:

*Creating a String:*
You can create a string in JavaScript by enclosing text within single (' '), double (" "), or backticks (` `) quotation marks. Here are examples of each:

*You can create numbers in JavaScript in a few different ways:*

1. Integer and Floating-Point Numbers:

You can create a numeric variable by assigning it a numeric value with or without a decimal point.

2. Using Arithmetic Expressions:

Numbers can also be created through mathematical expressions.

3. Using parseInt() and parseFloat():

You can parse strings into numbers using the parseInt() and parseFloat() functions.

4. Using Number() Constructor:

You can use the Number() constructor to convert values to numbers explicitly.

## **What is a Variable and why are they important in JavaScript?**

A variable in JavaScript is a symbolic name or identifier that is used to store and manage data within a program. Variables allow you to store values, such as numbers, strings, objects, and more, and then manipulate and retrieve those values as needed throughout your code. They are a fundamental concept in programming and play a crucial role in JavaScript and many other programming languages.

## **What is an HTML attribute?**

In HTML (Hypertext Markup Language), an attribute is additional information provided within the opening tag of an HTML element. Attributes are used to modify or define the characteristics, properties, or behavior of the element. They are always specified as name-value pairs, separated by an equal sign (=), and are placed inside the element's opening tag.

elementName attributeName="attributeValue">

elementName: This is the name of the HTML element, such as "img," "a," "div," or "input."

attributeName: This is the name of the attribute, which specifies what aspect of the element you want to modify or define.

attributeValue: This is the value assigned to the attribute. It can be a text string, a number, a URL, or other valid values depending on the attribute's purpose.

## **Describe the Anatomy of an HTMl element.**

The anatomy of an HTML element consists of various parts within the element's opening and closing tags. HTML elements are the building blocks of web pages and are used to define the structure and content of a webpage.

**Opening Tag** (<elementName>): The opening tag is the first part of an HTML element and consists of the following:

The less-than symbol (<) signifies the start of the opening tag.

elementName: This is the name of the HTML element, such as "div," "p," "a," "img," etc. It specifies the type of element you are creating.

Attributes: Optionally, you can include one or more attributes within the opening tag. Attributes provide additional information or settings for the element and are specified as name-value pairs.

**Content:** The content of the HTML element is the information or text that the element encloses. It is placed between the opening and closing tags and represents the main purpose of the element.

**Closing Tag** (</elementName>): The closing tag marks the end of the HTML element. It consists of the following:

The less-than symbol followed by a forward slash (</) signifies the start of the closing tag.

elementName: This matches the name of the opening tag and indicates the end of the element.

**Self-Closing Tag (<elementName />):** Some HTML elements do not require a closing tag because they are self-contained. In such cases, a self-closing tag is used, which combines the opening and closing tags into one.

**Attributes:** Within the opening tag, you can include one or more attributes, which are specified as name-value pairs. Attributes provide additional information or settings for the element.

**Whitespace:** HTML elements can have whitespace (spaces, tabs, line breaks) before and after the opening and closing tags. This whitespace is generally ignored by browsers, but it can be used for formatting and readability in your HTML code.

## **What is the Difference between article and section element tags?**

Use *article* when you have a complete, standalone piece of content that could be distributed and understood independently, like a news article.

Use *section* when you want to group related content within a larger document, such as chapters in a book, sections of a webpage, or thematic content divisions.

**What Elements does a “typical” website include?**

A "typical" website includes a variety of HTML elements to structure and present content in a user-friendly and visually appealing manner. While the specific elements used can vary depending on the website's purpose and design, here are some common elements you'll often find in a standard website:

1. **Document Structure:**
   - `<html>`: The root element that encloses the entire HTML document.
   - `<head>`: Contains metadata and links to external resources.
   - `<title>`: Sets the title of the webpage displayed in the browser's tab.
   - `<meta>`: Provides metadata such as character encoding and page description.
   - `<link>`: Links to external stylesheets, icon files, and other resources.
   - `<script>`: Links to or embeds JavaScript code.
   - `<style>`: Contains internal CSS styles.
   
2. **Page Structure:**
   - `<header>`: Typically includes the site logo, navigation menus, and introductory content.
   - `<nav>`: Contains navigation links, often found in the header or footer.
   - `<main>`: Encloses the main content of the webpage.
   - `<section>`: Groups related content together within the `<main>` element.
   - `<article>`: Represents a standalone, self-contained piece of content like a news article or blog post.
   - `<aside>`: Contains content related to the main content but can be considered secondary or supplementary.
   - `<footer>`: Contains information about the website, copyright, contact details, and footer navigation.
   
3. **Text and Media:**
   - `<p>`: Represents paragraphs of text.
   - `<h1>` to `<h6>`: Headings for different levels of section or content hierarchy.
   - `<ul>`: Unordered (bulleted) lists.
   - `<ol>`: Ordered (numbered) lists.
   - `<li>`: List items within `<ul>` and `<ol>` elements.
   - `<a>`: Anchor tags for creating hyperlinks.
   - `<img>`: Embeds images.
   - `<video>`: Embeds video content.
   - `<audio>`: Embeds audio content.
   - `<iframe>`: Embeds external content or interactive elements.
   - `<blockquote>`: Represents a block of quoted text.
   - `<cite>`: Provides a citation for a piece of content.

4. **Forms and User Input:**
   - `<form>`: Encloses a set of form elements.
   - `<input>`: Creates input fields for text, passwords, checkboxes, radio buttons, etc.
   - `<textarea>`: Provides a multi-line text input field.
   - `<button>`: Defines buttons, including submit buttons and reset buttons.
   - `<label>`: Labels form elements for improved accessibility.
   - `<select>`: Creates dropdown menus.
   - `<option>`: Specifies options within a `<select>` element.

5. **Interactive Elements:**
   - `<button>`: Allows users to trigger actions or events.
   - `<a>`: Hyperlinks for navigation.
   - `<details>`: Creates an expandable and collapsible content section.
   - `<summary>`: Defines a summary or title for a `<details>` element.
   - `<dialog>`: Represents a dialog or modal box.

6. **Semantic and Specialized Elements:**
   - `<mark>`: Highlights or marks text.
   - `<abbr>`: Defines an abbreviation.
   - `<code>`: Represents computer code.
   - `<pre>`: Preserves whitespace and formatting for preformatted text.
   - `<time>`: Specifies a date and/or time.
   - `<figure>`: Groups media and its caption together.
   - `<figcaption>`: Provides a caption for a `<figure>` element.

7. **Meta Elements:**
   - `<meta>`: Contains metadata for SEO and social media sharing (e.g., Open Graph and Twitter Card meta tags).

8. **Comments:**
   - `<!-- Comment text -->`: Allows developers to add comments within the HTML code for documentation or notes.

Remember that the choice and use of these elements depend on the specific content and design requirements of your website. HTML5 introduced a wide range of semantic elements to help improve accessibility, SEO, and code organization, so it's important to use them appropriately to enhance the structure and meaning of your web content.

## **How does metadata influence Search Engine Optimization?**

Metadata influences Search Engine Optimization by providing essential information to search engines, helping them understand the content and context of web pages. This understanding enables search engines to rank pages more accurately and present relevant results to users, ultimately improving the visibility and performance of your website in search engine results.

## **How is the <meta> HTML tag used when specifying metadata?**

The *meta* HTML tag is used to specify various types of metadata within an HTML document. Metadata provides information about the document itself, such as character encoding, viewport settings, author information, and more. Metadata is typically placed in the *head* section of an HTML document.

# **What to start to design a Website**

**What is the first step to designing a Website?**

The first step to designing a website is to plan and define the project's goals, objectives, and scope. This initial planning phase is critical for ensuring that your website meets its intended purpose and serves your target audience effectively. 

**What is the most important question to answer when designing a Website?**

Defining the primary purpose or goal of your website is a critical first step in the design process. It sets the direction for all other decisions and ensures that your website effectively serves its intended function, whether that's to inform, sell, engage, educate, or entertain.

# **Semantics**

**Why should you use an h1 element over a span element to display a top level heading?**

Using an h1 element over a <span> element to display a top-level heading is important for several reasons, primarily related to web semantics, accessibility, and search engine optimization (SEO):

**Semantic HTML:**

h1 is a semantic HTML element specifically designed to represent the highest-level or top-level heading on a webpage. It conveys the structural importance of the content it encloses.
Semantic HTML helps browsers, assistive technologies, and search engines understand the hierarchy and organization of the content. This benefits both human users and automated systems that parse web content.

**Accessibility:**

Screen readers and other assistive technologies rely on semantic HTML elements to provide context and structure to users with disabilities. Using h1 ensures that these users can navigate and understand the content effectively.

When you use h1, it's clear to assistive technology users that they have encountered the most significant heading on the page.

**SEO (Search Engine Optimization):**

Search engines use HTML structure, including heading elements, to determine the content and hierarchy of a webpage. Using h1 for the top-level heading helps search engines understand the page's main topic.
Properly structured headings can positively impact your website's SEO rankings and visibility in search results.

**Consistency and Best Practices:**

Following web development best practices, such as using h1 for top-level headings, makes your code more consistent, maintainable, and easier for other developers to understand.
It aligns with web standards and conventions, contributing to a cleaner and more professional codebase.

**What are the benefits of using semantic tags in our HTML?**

using semantic tags in HTML enhances accessibility, improves SEO, clarifies content structure, and makes your code more maintainable and future-proof. Embracing semantic HTML is a best practice in web development, contributing to a more inclusive, user-friendly, and search engine-friendly web.

# **Waht is JavaScript?**

**Describe 2 things that require JavaScript in the Browser?**

JavaScript is a versatile programming language that can be used in web browsers to enhance interactivity and functionality. Here are two common things that often require JavaScript in the browser:

**Form Validation:**

  - JavaScript is frequently used to perform client-side form validation in web applications. When users submit data through forms on a website (e.g., registration forms, login forms, contact forms), JavaScript can be used to validate that data before it's sent to the server.

  - Form validation with JavaScript allows you to check whether the user has entered data in the correct format (e.g., valid email addresses, required fields filled, password strength), reducing the chances of submitting incorrect or incomplete data.

  - It provides immediate feedback to users, highlighting errors or missing information in real-time, which enhances the user experience.
JavaScript can also be used to create custom validation logic, such as checking if a username is already taken or verifying the uniqueness of certain data.

**Dynamic User Interfaces:**

  - JavaScript is essential for creating dynamic and interactive user interfaces (UI) on websites. It enables web developers to respond to user actions and update the content or appearance of a webpage without requiring a full page reload.

Common examples of dynamic UI elements include:

  - Sliders and Carousels: JavaScript can be used to create image sliders, product carousels, and interactive galleries that allow users to browse through content by clicking or swiping.

  - Modal Dialogs: JavaScript can open and close modal dialogs or pop-up windows for tasks like login, registration, or displaying additional information.

  - AJAX (Asynchronous JavaScript and XML): JavaScript allows for asynchronous data retrieval from a server without refreshing the entire page. This is often used in web applications for features like live search, real-time updates, and chat applications.

  - Interactive Maps: JavaScript libraries like Google Maps API enable the creation of interactive maps that users can explore, zoom in on, and interact with.

  - Drag-and-Drop: JavaScript can be used to implement drag-and-drop functionality, allowing users to move elements or reorder lists.

JavaScript frameworks and libraries like React, Angular, and Vue.js have become popular choices for building highly dynamic and responsive web applications.
These are just two examples of the many ways JavaScript enhances the functionality and interactivity of websites in the browser. JavaScript empowers web developers to create rich, user-friendly web experiences that respond to user input and deliver real-time feedback.

## **How can you add JavaScript to an HTML document?**

You can add JavaScript to an HTML document using several methods, depending on where you want the JavaScript code to be placed and how you want it to interact with your webpage. 

**Inline JavaScript:**

You can include JavaScript code directly within the HTML file using the <script> element. Place the <script> tag either in the <head> section or at the end of the <body> section of your HTML document.

**External JavaScript File:**

For larger JavaScript code blocks or when you want to reuse JavaScript across multiple pages, it's a good practice to put your JavaScript code in an external file with a .js extension. You can then link to this external file using the <script> element in the HTML file.

**External JavaScript Libraries:**

You can include external JavaScript libraries or frameworks like jQuery, React, or Vue.js by linking to their hosted or locally hosted files using the <script> tag, similar to external JavaScript files.

**Event Attributes:**

You can add JavaScript code as event attributes directly within HTML elements to trigger specific actions when events (e.g., clicks, mouseover) occur. This approach is useful for simple interactivity but is less common for complex applications.

