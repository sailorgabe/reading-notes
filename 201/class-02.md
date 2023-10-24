# Readings: Basics of HTML, CSS & JS

**Why this topic matters.**

To create dynamic websites it is important to know HTML, CSS, & JS.  These three work together to create a web page, make it look good, and make it do fun stuff.

## Why is it important to use semantic elements in our HTML?

Using semantic elements in HTML is important for several reasons:

**Accessibility:** Semantic elements provide a clear and meaningful structure to web documents, making them more accessible to people with disabilities who use screen readers or other assistive technologies. These technologies rely on semantic HTML to understand the content and present it in a coherent way.

**Search Engine Optimization (SEO):** Search engines use semantic HTML to better understand the content and context of web pages. Properly structured content with semantic tags can lead to improved search engine rankings and better visibility in search results.

**Readability and Maintainability:** Semantic elements make the HTML code more readable and self-explanatory. Developers and other team members can quickly understand the purpose of various parts of a webpage, which makes the code easier to maintain and update.

**Consistency:** Semantic elements help in creating a consistent structure across different web pages or within a web application. This consistency in structure and naming conventions improves the user experience as users navigate through various parts of a website.

**Future-Proofing:** Semantic elements are designed to reflect the meaning and purpose of the content they contain. As web technologies evolve, using semantic elements ensures that your content remains relevant and adaptable to future changes in web standards.

**Enhanced Styling:** Semantic elements often come with default styling that can be more meaningful and predictable than generic HTML elements. This default styling can serve as a starting point for CSS styling, saving time and effort in the design process.

**Compatibility:** Modern web development practices encourage the use of semantic elements. As a result, using semantic HTML ensures better compatibility with current and future web technologies and frameworks.

(source Chat.Openai.com)

## How many levels of headings are there in HTML?

There are six headings in HTML. h1, h2, h3, h4, h5, h6

## What are some uses for the <sup> and <sub> elements?

Superscript text is smaller and raised in words and used for things like footnotes or copyright symbols.

Subscript text is smaller and lowered within in words and used for things like chemical formulas. (Source: Chat.openai.com)

## When using the <abbr> element, what attribute must be added to provide the full expansion of the term?

When using the <abbr> element in HTML to define an abbreviation or acronym, you should include the title attribute. The title attribute is used to provide the full expansion or explanation of the term represented by the abbreviation or acronym. (Source Chat.Openai.com)

# Learn CSS

## What are ways we can apply CSS to our HTML?

**Inline CSS:** You can apply CSS directly to individual HTML elements using the style attribute. Inline styles are defined within the HTML element's opening tag. 

**Internal CSS:** Internal CSS is placed within a <style> element in the HTML document's <head> section. It applies styles to elements throughout the document.

**External CSS:** External CSS involves placing CSS rules in a separate external file (usually with a .css extension) and linking it to the HTML document using the <link> element in the <head> section. 

**CSS Frameworks and Libraries:** You can use CSS frameworks like Bootstrap, Foundation, or Materialize, which provide pre-designed styles and components that you can apply to your HTML by including their CSS files and using their classes.

**CSS Preprocessors:** CSS preprocessors like Sass or Less allow you to write CSS in a more structured and efficient way with features like variables, nesting, and functions. You compile these preprocessor files into standard CSS for use in your HTML.

**Inline Stylesheet:** You can also define styles directly in the HTML document using the <style> element within the <head>. This is similar to internal CSS but kept separate for better organization.

**JavaScript and Inline Styles:** You can apply styles to HTML elements dynamically using JavaScript by modifying the style property of the element. This is useful for adding or changing styles based on user interactions or other dynamic events.(Source Chat.Openai.com)

## Why should we avoid using inline styles?

While there are situations where inline styles may be appropriate (e.g., quick prototyping, one-off styling adjustments), it is generally recommended to use external or internal CSS for most styling needs. This approach promotes maintainability, reusability, and a more organized codebase, which is essential for web development projects of any significant size or complexity. (chat.openai.com)

# Review the block of code below and answer the following questions:
h2 {
     color: black;
     padding: 5px;
   }


## What is representing the selector?

h2

## Which components are the CSS declarations?

The CSS declarations are the individual style rules enclosed within the curly braces. In this code, there are two CSS declarations:

color and black This is the first CSS declaration. It sets the text color property of the selected h2 elements to black.

padding 5px This is the second CSS declaration. It sets the padding property of the selected h2 elements to 5 pixels.

Each declaration consists of a property (e.g., color or padding) followed by a colon (:) and a value (e.g., black or 5px). These declarations define how the selected elements should be styled. Multiple declarations can be included within the same set of curly braces for a single selector to apply multiple styles to the selected elements. (Source: chat.openai.com)

## Which components are considered properties?

The components considered as properties are:

color, This is a CSS property that defines the text color of the selected elements, in this case, the h2 elements. It is set to the value black.

padding, This is another CSS property that defines the padding around the content of the selected elements. It specifies the spacing between the content and the element's borders. In this example, it is set to 5px. (Source chat.openai.com)

# Learn JavaScript

## What data type is a sequence of text enclosed in single quote marks?

In JavaScript, a sequence of text enclosed in single quotes (' ') is known as a string. Strings are used to represent and manipulate textual data. They can contain letters, numbers, symbols, and spaces, and they are one of the basic data types in JavaScript. (Source: chat.openai.com)

## List 4 types of JavaScript operators.

1. **Arithmetic Operators:** These operators perform mathematical operations on numeric values. Common arithmetic operators include addition (+), subtraction (-), multiplication (*), division (/), and modulus (%) for finding the remainder of division.

2. **Comparison Operators:** These operators are used to compare values and return Boolean results (true or false). Common comparison operators include equality (== or === for strict equality), inequality (!= or !== for strict inequality), greater than (>), less than (<), greater than or equal to (>=), and less than or equal to (<=).

3. **Logical Operators:** Logical operators are used to combine or modify Boolean values. Common logical operators include AND (&&), OR (||), and NOT (!).

4. **Assignment Operators:** Assignment operators are used to assign values to variables. Common assignment operators include the assignment operator (=), which assigns a value to a variable, and compound assignment operators like +=, -=, *=, /=, and %=, which combine an operation with the assignment. (source chat.openai.com)

## Describe a real world Problem you could solve with a Function.

You could create a website that catalogs baseball cards.  Use of JS operators could be used to search and retrieve baseball cards and link them to value sites.  

**An if statement checks a __ and if it evaluates to ___, then the code block will execute.**

condition. else

**What is the use of an else if?**

The else if statement in JavaScript is used to check additional conditions when the initial if condition evaluates to false. It allows you to create a chain of conditional statements to handle multiple cases or options.

**List 3 different types of comparison operators.**

1. **Equality Operator (==):** The equality operator checks if two values are equal, regardless of their data types. If the values are equivalent, it returns true, otherwise, it returns false. For strict equality (considering both value and data type), you can use ===.

2. **Inequality Operator (!=):** The inequality operator checks if two values are not equal. If the values are not equal, it returns true, otherwise, it returns false. For strict inequality (considering both value and data type), you can use !==.

3. **Greater Than Operator (>) and Less Than Operator (<):** These operators are used to compare numeric values. The greater than operator (>) checks if the value on the left is greater than the value on the right. The less than operator (<) checks if the value on the left is less than the value on the right.

**What is the difference between the logical operator && and ||?**

The logical operators && (logical AND) and || (logical OR) are used to combine and evaluate boolean expressions in JavaScript. Here's the key difference between them:

**Logical AND (&&):**

The && operator returns true if both operands (expressions) on its left and right side are true.
If any one of the operands is false, the entire expression evaluates to false.
It's often used to ensure that multiple conditions must all be true for a statement to execute.

**Logical OR (||):**

The || operator returns true if at least one of its operands (expressions) on its left or right side is true.
If both operands are false, the entire expression evaluates to false.
It's often used to provide alternatives or to check if at least one condition is true.

In summary, && requires both conditions to be true for the result to be true, while || only requires one of the conditions to be true for the result to be true. These operators are fundamental for creating conditional logic and controlling the flow of your JavaScript programs based on different conditions.(source chat.openai.com)
