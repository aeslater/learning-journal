[Home](README.md)
## Learning Journal Notes
# Operators & Loops
---
### Loops

* [For loops](https://www.w3schools.com/js/js_loop_for.asp) run a specified number of times, usually using a counter inside to determine when to stop. Give the counter an initial value and increment `++` each time.
* [While loops](https://www.w3schools.com/js/js_loop_while.asp) continue to run while a specified condition is true. The return statement can send a value back to the main code, ends the loop, and continues running the main code.
* Do while loops are the same as while loops except it will run at least once even if the condition is false. 

Some example code that will write the numbers 0 through 9 is shown below. Every time the loop runs, the `i++` operator adds one to the value of i.

`var i;`

`for (var i = 0; I < 10; i++) {`

`   document.write(i);`

`}`

### Comparison Operators

Make these into flashcards:

`==		IS EQUAL TO`

`!=		IS NOT EQUAL TO`

`===		STRICT EQUAL TO`

`!==		STRICT NOT EQUAL TO`

`>		GREATER THAN`

`<		LESS THAN`

`>=		GREATER THAN OR EQUAL TO`

`<=		LESS THAN OR EQUAL TO`

`&&		LOGICAL AND`

`||		LOGICAL OR`

`!		LOGICAL NOT`

`++     INCREMENT`

`--     DECREMENT`


### Truth Tables
A truth table compares conditions for a given operator (such as `==` or `>`) to show which pairs of conditions would return a value of true. See [here](https://algassert.com/visualization/2014/03/27/Better-JS-Equality-Table.html) for an example of a truth table for `==`. Below are the first three comparisons in the first row.

`(true == true)` returns a value of `true`

`(true == false)` returns a value of `false`

`(true == 1)` returns a value of `true`

