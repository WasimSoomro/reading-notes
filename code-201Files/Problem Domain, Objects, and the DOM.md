# Problem Domain, Objects, and the DOM
## JavaScript Object Basics
### How would you describe an object to a non-technical friend you grew up with?
Objects are a way to organize information when coding, and by using objects you can identify and change certain properties of that object with propeties and methods. 
### What are some advantages to creating object literals?
You can write out all the object contents as you're creating the object. It is also easier since it is less code. 
### How do objects differ from arrays?
They are similar as objects are sometimess called associative arrays but they are still different. Informaiton in arrays is accessed with brackets whereas with objects oyu can use .notation or brackets. Objects are key-value pairs. Arrays are also ordered. 
### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
"For example, if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation."
### Evaluate the code below. What does the term this refer to and what is the advantage to using this?
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
The this refers to the identifying the current code the object is being written inside. It helps when using constructors. 
## Introduction to the DOM
### What is the DOM?
The DOM is "the data representation of the objects that comprise the structure and content of a document on the web." It is "a programming interface for web documents." 
### Briefly describe the relationship between the DOM and JavaScript.
The "DOM is not part of the JavaScript language, but is instead a Web API used to build websites." The DOM is independent of any programming language. 
