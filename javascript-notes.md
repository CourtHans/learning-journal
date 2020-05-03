[Return to Table of Contents](README.md)

# Class 5: JavaScript Notes

JavaScript is designed to make our web pages dynamic

* async - asynchronous, not everything is running at the same time
* dynamically typed - functions/programs needed to input all the output on the page
* interpreted scripting language - dependent upon inputs
* variables - a variable is a way to programmatically reference a previously assigned value
* statements - each individual instruction or step (should always end in a semicolon)
* data types - numbers (`1,3,46`), strings (`'text or numbers within single quotes'`), boolean (`true` or `false`)
* **what do we call these?**
    1. `=` - assignment operator
    2. `==` - comparatively equal
    2. `===` - strictly equal 

The **document** object represents the entire web page. 
The **write()** method of the **document** object allows new content to be written into the page where the **`<script>`** element sits.

The **document** object has several methods and properties. They are known as **members** of that object. You can access the members of an object using a dot between the object name and the member you want to access. It is called a **member operator**.

Whenever a method requires some information in order to work, the data is given inside the parentheses. Each piece of information is called a **parameter** of the method. In this case, the **write()** method needs to know what to write into the page.

JavaScript runs where it is found in HTML.

### Six rules for naming variables

1. The name must begin with a letter, dollar sign ($), or an underscore. It must **not** start with a number.
1. The name can contain letters, numbers, dollar signs ($), or an underscore (_). Note that you must not use a dash (-) or a period (.) in a variable name.
1. You cannot use **keywords** or **reserved** words. Keywords are special words tha ttell the interpreter to do something. Reserved words are ones tha tmay be used in a *future* version of JavaScript.
1. All variable are case sensitive. It is bad practice to create two variables that have the same name using different cases.
1. Use a name that describes the kind of information the variable stores (e.g. firstName).
1. If your variable name is made up of more than one word, use camel case (capital letter for the first letter of every word *after* the first word.

[Previous - CSS notes](css-notes.md)

[Next - How Computers Work](computer-videos.md)