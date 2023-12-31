# Readings: HTML Links, JS Functions, and Intro to CSS Layout

## Why this reading topic relates to our training statement.

HTML, CSS, and JS all work together to create a dynamic webpage.  The more tools you know the better your page will look and feel.

## To create a basic link, we wrap text or other content inside what element?

A basic link is created by wrapping the text or other content inside an <a> element and using the href attribute, also known as a Hypertext Reference, or target, that contains the web address. (MDNWEBDOCS)

## The href attribute contains what information?

The href attribute is commonly used in HTML (Hypertext Markup Language) to specify the hypertext reference, or the destination of a hyperlink. It contains a URL (Uniform Resource Locator) or a URI (Uniform Resource Identifier) that points to the location of another web resource, such as a web page, an image, a document, a video, or any other type of file that can be accessed over the internet.

When you click on a hyperlink in a web page, the browser uses the information in the href attribute to navigate to the specified URL or URI, which may load a new web page or trigger some other action depending on the type of resource linked to.(chatpgpt)

## What are some ways we can ensure links on our pages are accessible to all readers?

**Descriptive Link Text:** Use descriptive and meaningful link text that conveys the purpose or destination of the link. Avoid using generic text like "click here" or "read more." Instead, use text that gives users a clear idea of where the link will take them.

**Title Attribute:** Use the title attribute to provide additional context or information about the link. This can be especially helpful for users who rely on screen readers.

## What is meant by “normal flow”?

In web design and CSS (Cascading Style Sheets), "normal flow" refers to the default layout behavior of HTML elements on a web page before any additional CSS styling or positioning is applied. It represents the way elements are displayed in the order they appear in the HTML document, with each block-level element stacking on top of the previous one vertically. (chatgpt)

## What are a few differences between block-level and inline elements?

**Display Behavior:**

**Block-level elements:** These elements create a block-level box, typically spanning the full width of their parent container, and they start on a new line. Block-level elements stack vertically on top of each other. 

**Inline elements:** Inline elements, on the other hand, do not create a new block-level box. They flow within the content alongside other inline elements and do not start on a new line. 

**Width and Height:**

**Block-level elements:** By default, block-level elements typically have a width of 100% of their parent container and a height that adjusts to their content. You can control their width, height, and positioning using CSS.

**Inline elements:** Inline elements take up only as much width as necessary for their content and only as much height as needed to accommodate their content. You can control their width but not their height with CSS.

**Line Breaks:**

**Block-level elements:** Block-level elements create line breaks before and after themselves, causing content following them to appear on a new line.
Inline elements: Inline elements do not introduce line breaks. They flow within the text content and do not force new lines.
Nested Elements:

**Block-level elements:** Block-level elements can contain other block-level elements and inline elements, allowing for the creation of complex hierarchical structures.
Inline elements: Inline elements are typically contained within block-level elements. Nesting block-level elements within inline elements is not valid HTML.

**Default Styling:**

**Block-level elements:** Block-level elements often have default styling that includes starting on a new line and stacking vertically, making them suitable for structuring the layout of a web page.
Inline elements: Inline elements are used for text-level styling and formatting within the content, such as emphasizing text, creating hyperlinks, or applying inline styles.(chatgpt)

## ___ positioning is the default for every html element.

The default positioning for every HTML element is called "static positioning." In static positioning, elements are displayed in their normal order in the HTML document, following the flow of the document. Elements are positioned according to their place in the document's structure and do not respond to CSS properties like position, top, left, right, or bottom.

In other words, when you don't apply any specific positioning to an HTML element using CSS, it remains in its default static position, and it is affected by the normal flow of the document. This is the default behavior for all HTML elements, and it's often referred to as "normal flow" or "static flow." (chaptgpt)

## Name a few advantages to using absolute positioning on an element.

Precise Placement: Absolute positioning allows you to place an element precisely at a specific location within its containing parent element. This level of control is valuable when you need to position elements with pixel-perfect accuracy.

Layering and Z-Index: Elements with absolute positioning can be layered on top of one another using the CSS z-index property. This makes it easier to create complex layouts where elements overlap or are stacked in a specific order.

Floating Elements: Absolute positioning can be used to "float" elements above the normal flow of content, which can be useful for creating overlays, tooltips, dropdown menus, or modal dialogs.

Positioning Relative to a Container: You can position an element relative to a containing parent element, not just the viewport. This allows you to create elements that are positioned within a specific container, which can be especially useful for responsive design.

No Impact on Surrounding Elements: Elements with absolute positioning do not affect the layout or positioning of other elements in the document flow. This means they won't push surrounding content around, making it easier to create unique design elements without disrupting the rest of the page.

Animation and Transformation: Absolute positioning can be combined with CSS animations and transformations to create dynamic effects, such as sliding, fading, or rotating elements into view.

Custom Dropdowns and Tooltips: Absolute positioning is commonly used to create custom dropdown menus, tooltips, and pop-up windows that appear at specific locations when triggered by user interactions.

While absolute positioning offers these advantages, it should be used judiciously. Overusing absolute positioning can lead to layout issues, especially on responsive websites where elements need to adapt to different screen sizes and orientations. Additionally, absolute positioning can make your code less accessible and harder to maintain if not used carefully. It's important to consider the specific design requirements and user experience when deciding whether to use absolute positioning for an element.(chatgpt)

## What is a key difference between fixed positioning and absolute positioning?

A function declaration is a way to define a function and its code, giving it a name and specifying its parameters, while a function invocation is the actual execution of that function, providing the required arguments and triggering the code to run.(chatgpt)

## What is the difference between a parameter and an argument?

parameters are placeholders for data expected by a function, defined in the function's declaration. Arguments, on the other hand, are the actual data or values that are passed to the function when it is called, and they take the place of the parameters within the function's execution. (chatgpt)

## Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.

It not only helps you write better code but also accelerates your learning by exposing you to different perspectives and experiences.  By working in pairs you can learn together by failing together.  You can speed up your learning by having two sets of eyes focus on the problem.  It helps both programmers.
