[Table of Contents](README.md)

# Class 8: Loop notes

### Symbols

- **`&&`** Logical and
- **`||`** Logical or
- **`!`** Logical not
- **`==`** is equal to
- **`===`** strict equal to
- **`!=`** is not equal to
- **`!==`** strict not equal to

### Loops

Loops check a condition. If it returns **true**, a code block will run. The condition will repeat until the condition returns **false**. 

A ***FOR*** loop is useful if you need to run code a specific number of times.

A ***WHILE*** loop is useful if you do not know how many times the code whould run. 

The ***DO WHILE*** loop is similar to the *while loop* but has one key difference; it wll always run the statments inside the curly braces at least once, ven if the condition evaluates to **false**.

A for loop uses a counter as a condition. Example of a condition made up of three statements:

`for (var i =  0; i < 10; i++)`

*Initialization*
`var i = 0;` - created a variable and set it to 0 (this acts as the counter). The variable is only created the first time th loop is run. 

*Condition*
`i < 10` - the loop should continue to run until the counter reaches a specified number. The condition may also use a variable that holds a number. 

*Update*
`i++` - Every time the loop has run the statemetns in the curly braces, it adds one to the counter. (it's also possible to count backwards using `--`)


- [Previous - Function Notes](function-notes.md)