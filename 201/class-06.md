# Readings: Problem Domain, Objects, and the DOM

## How would you describe an object to a non-technical friend you grew up with?

"Okay, remember those old library card catalogs we saw at the museum? Each drawer had different categories of books, and inside each drawer, there were cards for individual books. Each card had details like the book's title, author, and publication date.

In the world of computer programming, JavaScript has something similar called an 'object'. Think of the object as the drawer. Inside this drawer (or object), you can have many cards (known as 'properties'). Each card (or property) has a name, like 'title' or 'author', and next to that name, there's the actual information, like 'Harry Potter' or 'J.K. Rowling'.

So, a JavaScript object is just a way to organize and store different pieces of related information in one place." (chatGPT)

## What are some advantages to creating object literals?

Object literals in JavaScript are a concise and flexible way to create and organize data.

**Simplicity and Readability:** Object literals provide a clear and straightforward way to define objects. The syntax is intuitive, which makes it easy to read and understand.

No Explicit Instantiation: Unlike using constructors or classes, with object literals, you don’t need to instantiate an object using the new keyword. This makes it quick and straightforward to create objects.

**Dynamic Property Names:** You can define property names dynamically using computed property names in the object literal.

**Flexible:** Object literals can contain various types of values, such as strings, numbers, arrays, other objects, and functions. This makes them versatile for a range of tasks.

**Nesting:** You can easily nest objects within objects, creating complex data structures with relative ease.

## How do objects differ from arrays?

It allows you to send a series of structured data items vice a single item as in an array.

## Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

"if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation." (MDN Web Docs JavaScript Object basics)

## Evaluate the code below. What does the term this refer to and what is the advantage to using this?

"this" refers to name and age.  It allows programmers to use multiple object literals and the method definition for every object you create.

## What is the DOM?

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page. (MdNwebdocs)

## Briefly describe the relationship between the DOM and JavaScript.

The DOM (Document Object Model) is a structured, tree-like representation of an HTML (or XML) document. It provides a way for programming languages to interact with the structure, style, and content of web pages. Each element on the page (like paragraphs, headings, links, and so on) corresponds to a node in this tree.

JavaScript is a programming language that, among other things, can interact with the DOM.

The relationship between the DOM and JavaScript can be understood as follows:

Manipulation: JavaScript can query, modify, add, or delete nodes in the DOM, allowing for dynamic changes to the content, structure, and style of a web page. This is how interactive web pages are created. For instance, when you click a button to open a dropdown menu, it's often JavaScript that's changing the DOM to make the menu visible.

Event Handling: The DOM provides a way to detect events, like clicks, keyboard input, or mouse movements. JavaScript can listen to these events and execute code in response, enabling user interactivity.

Data Population: JavaScript can fetch data from a server (e.g., using AJAX) and then dynamically populate the DOM with this data. This is the basis for many modern web applications that load content without a full page refresh.

Live Representation: The DOM is a "live" representation of a web page. Any changes made to the DOM via JavaScript are immediately reflected on the page.

In summary, while the DOM represents the structure and content of a web page, JavaScript provides the means to interact with and manipulate this structure, enabling the creation of dynamic, interactive web experiences.(chatGPT)
