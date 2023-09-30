# Python Part 2

## For-Else
The else function after the for function takes precedence over search adventures - to provide a program exit when the search is not specified.

## Break
* Break is a statement used to stop (break) a for or while loop.
* In general, the break function is usually used in loops, a loop will be stopped at the start of the iteration.
* If the break function is in a nested loop, the loop is stopped only in the nested loop, the parent loop continues to run.
* If the break function is outside the loop, the script file will be stopped directly at the end of the script file or stop the script file in the middle of execution.

## Continue
* In Python, the continue statement is used inside loops such as for or while loops to skip over the current iteration of the loop and move on to the next iteration.
* It can only be used • inside a loop (for loop or while loop) and is usually accompanied by a conditional statement.
* When the continue statement is executed within a loop, the code inside the loop will immediately stop executing for the current iteration, and the loop will jump to the next iteration.

## While
* While loop is a loop that is indefinite, aka uncertain, or even unlimited.
* While keyword, we have to fill in this.
* : this can be a boolean variable or a logical expression.
* And the last one is a block (or set of lines) of code that will repeat the condition being met.

## While-Else
* The Python while else loop is an extension of the while loop with an else block that executes when the while's condition is no longer true.
* The 'while' keyword starts the loop, followed by the condition that determines whether the loop should continue executing.
* A colon (:) follows the condition, indicating the beginning of the while block.
* Code to be executed when the condition is true is indented under the while block.
* The 'else' keyword, followed by another colon (:), starts the else block. This block will execute once the while condition becomes false. The else block is optional.

## List Comprehension (Create a list with In Line Loops and If)
* There are times when we need to create a new list from the previous list operation.
* List comprehension is a way to generate new content based on previously existing lists or irretables.
* The underscore includes valid variable equations.
* In general "_" is usually used as a throwaway variable (unimportant variable).

## Function - Definition, Calling, and Return Function

### Function
* In mathematics, a function is a process that relates between an input and an output.
* In Python, apart from these relational functions, functions are also a way to organize code - with the ultimate goal of code being reusable.
* It is best if functions have only one specific use but can be reused.
* Common functions are provided by Python. But we can define our own functions.

### Defining functions
* Functions are defined with the def keyword followed by the function name and parameters in brackets ()
* Optionally, you can add a docstring - a documentation string that describes the context of the function.
* The code block in each function begins with a colon and uses indentation.
* The function stops when there is a return [expression] statement which returns [expression] to the caller.
* You can also make a function not return output with return None.
* By default, Python will position each parameter according to the order in which they were registered when they were defined, and must be called in that order.
* The return (expression) statement will make the program execution exit the current function, while returning a certain value.
* The return value of a function can be stored in a variable.
* This will differentiate a function that returns a value from a function that does not return a value (filter is called a procedure).
