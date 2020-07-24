[Home](README.md)
## Learning Journal Notes
# Programming with JavaScript
---
### What can you do with JavaScript?
A script is a series of instructions that a computer will follow to achieve a goal. With JavaScript, you can:

* Access page content
* Modify page content
* Program rules the browser will follow
* React to events triggered by user or browser

Note: It is important and helpful to spend time designing your script before writing the code. Sketch out the tasks in a flowchart.

Each instance of an object can have its own properties, events, and methods.  Properties have names and values. Events are used to trigger a specific section of code. Methods can be questions that tell you something about an object or instructions that change the values of an object’s properties. 

Expressions assign a value or calculate a value to a and assign it to a variable.  Operators create a single value from one or more values; this can be done by performing basic math, combining strings, and comparing values.
Functions are groups of statements to perform a task that can be called and used later and multiple times. 

Example of creating / declaring a function:

`function getSize(width, height, depth) {
   var area = width * height;
   var volume = width * height * depth;
   var sizes = [area, volume];
   return sizes;
}
var areaOne = getsize(3, 2, 3)[0];
var volumeOne = getSize(3,2,3)[1];`	

The function used above returned more than one value using an array. The `return` keywork is used to return a value to the code that called the function.

