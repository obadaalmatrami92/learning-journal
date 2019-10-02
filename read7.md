how JavaScript can be used
in browsers to make websites more interactive,
interesting, and user-friendly. You will also learn about
jQuery because it makes writing JavaScript a lot easier.

The only equipment you need to use Java script a computer with a modern web browser
installed, and your favorite code editor, (e.g., Notepad, TextEdit. Sublime Text. or Coda).
ACCESS CONTENT
You can use JavaScript to select any
element, attribute, or text from an
HTML page.
Access the content of the page
Modify the content of the page
Program rules or instructions the browser can follow
React to events triggered by the user or browser.

A script is a series of instructions that a
computer can follow to achieve a goal.
You could compare scripts to any of the following:
RECIPES
By fo llowing the instructions in a
recipe, one-by-one in the order
set out,cooks can create a dish
they have never made before.
Some scripts are simple and only
deal with one individual scenario,
like a simple recipe for a basic
dish.Other scripts can perform
many tasks, like a recipe for a
complicated three-course meal.
Another similarity is that, if
you are new to cooking or
programming, there is a lot of
new terminology to learn.

EXPRESSIONS THAT JUST ASSIGN A
VALUE TO A VARIABLE
In order for a variable to be useful, it needs to be
given a value. As you have seen, this is done using
the assignment operator (the equals sign).
var color = 'beige';
The value of co 1 or is now beige.
When you fi rst declare a variable using the var
keyword, it is given a special va lue of undefined.
This will change when you assign a va lue to it.
Technically, undefined is a data type like a number,

EXPRESSIONS THAT USE TWO OR
MORE VALUES TO RETURN A
SINGLE VALUE
You can perform operations on any number of
individual values (see next page) to determine a
single value. For example:
var area = 3 * 2;
The value of area is now 6.
Here the expression 3 * 2 evaluates into 6. This
example also uses the assignment operator, so the
result of the expression 3 * 2 is stored in the variable
called area.
Another example where an expression uses two
values to yield a single value would be where two
strings are joined to create a single string.
Expressions rely on things called operators; they allow programmers to
create a single value from one or more values.
ASSIGNMENT OPERATORS
Assign a value to a variable
color = 'beige';
The value of co 1 or is now beige.
(See p61)
ARITHMETIC OPERATORS
Perform basic math
area = 3 * 2;
The value of area is now 6.
(See p76)
STRING OPERATORS
Combine two strings
greeting= 'Hi 1 + 'Mol ly';
The value of greeting is now Hi Molly.
A script is made up of a series of statements. Each
statement is like a step in a recipe.
Scripts contain very precise instructions. For example,
you might specify that a value must be remembered
before creating a calculation using that value.
Variables are used to temporarily store pieces of
information used in the script.
Arrays are special types of variables that store more
than one piece of related information.
JavaScript distinguishes between numbers (0-9),
strings (text), and Boolean values (true or false).
Expressions evaluate into a single value.
Expressions rely on operators to calculate a value.
functions 
Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of st atements).
Grouping together the The steps that the function On the right, there is an example
statements that are required to needs to perform in order to of a function in the JavaScript
answer a question or perform a perform its task are packaged file. It is called updateMessage () .
task helps organize your code. up in a code block. You may
remember from the last chapter Don't worry if you do not
Furthermore, the statements in a that a code block consists of one understand the syntax of the
function are not always executed or more statements contained example on the right; you will
when a page loads, so functions within curly braces. (And you do take a closer look at how to wri te
also offer a way to store the steps not write a semicolon after the and use functions in the pages
needed to achieve a task. The closing curly brace - like you do that follow.
script can then ask the function after a statement.)
to perform all of those steps as Remember that programming
and when they are required. Some functions need to be languages often rely upon on
For example, you might have provided with information in name/value pairs. The function
a task that you only want to order to achieve a given task. For has a name, updateMessage,
perform if the user clicks on a example, a function to ca lculate and the value is the code block
specific element in the page. the area of a box would need (which consists of statements).
to know its width and height. When you call the function by its
If you are going to ask the Pieces of information passed name, those statements will run.
function to perform its task to a function are known as
later, you need to give your parameters. You can also have anonymous
function a name. That name functions. They do not have a
should describe the task it is When you write a function and name, so they cannot be called.
performing. When you ask it to you expect it to provide you Instead, they are executed as
perform its task, it is known as with an answer, the response is soon as the interpreter comes
calling the function. known as a return value. across them.

exxample:
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(};

Functions allow you to group a set of related
statements together that represent a single task.
Functions can take parameters (informatiorJ required
to do their job) and may return a value.
An object is a series of variables and functions that
represent something from the world around you.
In an object, variables are known as properties of the
object; functions are known as methods of the object.
Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.
JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
Arrays and objects can be used to create complex data
sets (and both can contain the other).