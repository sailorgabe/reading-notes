# Readings: Object-Oriented Programming, HTML Tables

## Explain why we need domain modeling.

In essence, domain modeling acts as a foundation upon which software systems are built. By investing time in understanding and modeling the domain, teams can ensure they are building the right solution and addressing the actual needs of the problem space.(chatGPT)

## Why should tables not be used for page layouts?

**Layout tables reduce accessibility for visually impaired users:** screen readers, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screen readers' output will be confusing to their users.

**Tables produce tag soup:** As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.

**Tables are not automatically responsive:** When you use proper layout containers (such as header, section, article, or div), their width defaults to 100% of their parent element. Tables, on the other hand, are sized according to their content by default, so extra measures are needed to get table layout styling to work across a variety of devices effectively.

## List and describe three different semantic HTML elements used in an HTML table.

1. <table> : Description: This is the foundational element for creating a table in HTML. It defines the overall table structure.

2. <tr> : Description: Stands for "table row." It is used to group a set of table cells (<td>) together to form a single row. Optionally, table header cells (<th>) can also be grouped using <tr>.

3. <the> : Description: Represents "table header." It is used to define a header cell in a table. Typically, the content within a th element is bold and centered on differentiating header cells from regular table data cells (td). The th element can be used within both <thead> (table header group) and tr (table row).

## What is a constructor and what are some advantages to using it?
How does the term this differ when used in an object literal versus when used in a constructor?

**In an Object Literal:**

When this is used within an object literal, it refers to the object itself. This allows properties or methods within that object to refer to other properties or methods of the same object.

**In a Constructor Function:**

When a function is used as a constructor typically invoked using this refers to the newly created instance. 

## How does the term this differ when used in an object literal versus when used in a constructor?

In an object literal, this references the object itself, and its value is pretty straightforward in methods of that object.

In a constructor function, this refers to the new object instance being created by the constructor. If you forget the new keyword when calling a constructor, this will not refer to the new instance; instead, in non-strict mode, it will refer to the global object (which is usually window in a browser environment), leading to unexpected behaviors. In strict mode, calling a constructor without new will result in an error.

## Explain prototypes and inheritance via an analogy from your previous work experience

Imagine a Book Publishing House

Prototypes:
Every book published by this house has some basic components in common: a title, an author, a table of contents, page numbers, chapters, and an ISBN number. Let's consider the basic book template as our "prototype". This prototype has methods like read(), openPage(number), and close(). No matter which specific book we're talking about – be it a novel, a cookbook, or a history textbook – they all derive these basic methods and properties from the prototype.

In JavaScript, if we consider the prototype as this basic book template, every new book that is created (or instantiated) will automatically inherit all the properties and methods from the prototype. This is efficient because instead of defining these methods for every single book individually, they can simply look up to the prototype and use the methods defined there.

Inheritance:
Now, while every book has those basic features, some categories of books have specialized features. For instance, textbooks might have an index and practice questions at the end of each chapter. Cookbooks might have a section dedicated to ingredients and dietary restrictions. Novels might have a blurb or a dedication page.

In the context of inheritance, think of these specialized features as methods and properties of derived objects (or sub-classes). A Textbook might inherit all the basic features from the general Book prototype, but it will also have its own methods like practiceQuestions(). Similarly, a Cookbook will inherit the basic features from Book but may also have its own method like listIngredients().

In JavaScript, this specialized behavior is achieved through the prototype chain. When we try to access a method on the Textbook object, it will first look in its own properties and methods. If it doesn't find it there, it will look up to its parent (or prototype), which in this case is the general Book. This chain can go on, forming the prototype chain, until it looks up to the base Object prototype if needed.

In Summary:
Prototypes in JavaScript are like the basic template of a book. Every book, no matter its type, shares some foundational features. Inheritance allows specialized types of books to have their unique features while still retaining the basic ones. This structure provides efficiency and flexibility, much like how a publishing house can produce a diverse range of books using a foundational template and specialized additions.(chatGPT)
