# Reading Notes 07: Programming with JavaScript

1. **What is control flow?**

> Control flow refers to the order in which individual statements, instructions, or function calls in a program are executed or evaluated. In other words, it's the direction the computer "flows" through the code. Control structures in programming languages determine the flow based on decisions (using conditional statements) or by repeating blocks of code (using loops).

> Common control flow constructs include:

>Sequencing – This is the default mode where instructions are executed one after another in the order they appear in the code.

>Selection:

>If-Then: Executes a block of code if, and only if, a condition is true.
If-Then-Else: Executes one block of code if a condition is true, and another block if the condition is false.
Switch (or Case): Allows for a variable to be tested for equality against multiple values.
Iteration (loops):

>For Loop: Executes a block of code a predetermined number of times.
While Loop: Executes a block of code as long as a condition remains true.
Do-While Loop: Executes a block of code once, and then continues to execute it as long as the condition remains true.
Jump:

>Break: Used to exit a loop or switch statement prematurely.
Continue: Skips the current iteration of a loop and moves to the next one.
Return: Exits the current function and returns a value (if specified) to the calling function.
Goto (in some languages): Jumps to another point in the code. This is generally discouraged because it can make the flow of a program hard to understand and maintain.
Control flow is fundamental to programming. It allows developers to implement logic, make decisions, and create repetitive operations, enabling the creation of complex and dynamic software applications.

1. **What is JavaScript function?**

>In JavaScript, a function is a block of reusable code that performs a specific task. Functions can be defined, invoked, and passed around as values, making them first-class citizens in the JavaScript language. They play a crucial role in organizing and modularizing code, allowing for better maintainability and reusability.

1. **What does it mean to invoke - or call - a function?**

>To "invoke" or "call" a function means to execute the code defined within the function. When a function is invoked, the program control is transferred to that function, and the statements within that function are executed in sequence. Once the function finishes executing, the control returns to the point where the function was called, and the program continues executing the next line of code.

1. **What are the parenthesis () for when you define a function?**

>When you define a function in most programming languages, including JavaScript, the parentheses () are used to define parameters for that function. Parameters are variables that act as placeholders for the values you'll pass into the function when you call or invoke it. These values are commonly referred to as "arguments."

>The parameters you define within the parentheses allow the function to accept input and perform operations or produce outputs based on that input.

