# Readings: HTML Lists, Control Flow with JS, and the CSS Box Model
## Learn HTML
### When should you use an unordered list in your HTML document?
When you want to display a list of items, typically in bullet format and not numbered.
### How do you change the bullet style of unordered list items?
You can use CSS list-style-type such as circle, disc, or square 
### When should you use an ordered list vs an unordered list in your HTML document?
An ordered list can be used when you want a numbered list of items, an unordered list works for just a list of items that can be displayed in bullet format. For example, stels in a recipe or turn-by-turn directions would benefit from an ordered list.
### Describe two ways you can change the numbers on list items provided by an ordered list?
You can use a global attribute with a numbering type such as 'a' for lowercase letters, or 'i' for loewrcase Roman numerals.
## Learn CSS
### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled; "The Box Model"?
In a story titled The Box Model there would be a line, this would be the border. Margin would take the space on the outside of the border and padding would take the space on the inside of the border. In this story they could be opposites although different sizes. 
### List and describe the four parts of an HTML elements box as referred to by the box model. 
Content box, padding box, border box, margin box.
Content box displays the contentt, it can be sized using "properties like iline-size and block-size or width and height."
Padding box "sits around the content as white space; size it using padding and related properties."
Border box "wraps the content and any padding; size it using border and related properties."
Margin box is "the outermost layer, wrapping the content, padding, and border as whitepsace between this box and other elements, size it using margin and related properties."
## Learn JS
### What data types can you store inside of an array?
"Strings, numbers, objects and even other arrays."
### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
The people array is a valid array. To access the values stored, we need to chain bracket notation, for example, const people = [1][1];

### List five shorthand operators for assignment in javascript and describe what they do.
x = f(), Assignment operator
x += f(), Addition assignment
x -= f(), Subtraction assignment
x *= f(), Multiplication assignment 
x /= f(). Division assignment 


### Read the code below and evaluate the last expression and explain what the result would be and why.
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

10dog

### Describe a real world example of when a conditional statement should be used in a JavaScript program.
Perhaps at a crosswalk there can be code in a system that says if person pushes button, then change crosswalk light.

### Give an example of when a loop is useful in JavaScript.
A loop is useful in JavaScript in a situation where say you want to list all the values from 0-100 squared. Instead of manually entering each number and then squaring it, a loop can run from 0-100 and square each number.