# Read 08: Operators and Loops

**What is an expression in JavaScript?**

>In JavaScript, an expression is any valid unit of code that resolves to a value. It can be as simple as a literal value or as complex as a series of operations combined with variables. Every expression will evaluate to some value of a certain type, like string, number, object, etc.

**Why would we use a loop in our code?**

>Loops are fundamental constructs in programming that allow for a set of instructions to be executed repeatedly based on a condition or for a specified number of times. Using loops can lead to more concise, efficient, and maintainable code.

**When does a for loop stop executing?**

1. Condition Is Evaluated as False: The loop's central control mechanism is its condition. The loop will stop executing once this condition evaluates to false.

2. Break Statement: If a break statement is encountered inside the loop, it will immediately terminate the loop, regardless of whether the loop's condition is true or false.

3. Return Statement (Inside a Function): If the loop is inside a function and a return statement is executed, the function will terminate, and thus the loop will also stop.

4. Exception or Error: If an unhandled exception or error occurs within the loop, it might cause the loop (and potentially the entire program) to terminate, depending on the language and runtime environment.

5. Infinite Loop: If you design a for loop where the condition always evaluates to true and there's no break or external intervention, then the loop won't stop on its own. This situation is called an infinite loop, and it's usually unintended. You'll typically need to manually stop the program in this case.

6. External Intervention: In some environments or applications, a loop might be terminated by external factors, such as a user manually stopping the program, a timeout being reached, or system constraints being exceeded.

**How many times will a while loop execute?**

>The number of times a while loop executes is determined by its condition. The loop will continue executing as long as the condition evaluates to true. Once the condition becomes false, the loop stops.

