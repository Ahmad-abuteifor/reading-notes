# THE Functions
Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function

**Type of Functions : **  
-Function declarations  
-Function expressions  

---------

**A function declaration** (also called a function statement) consists of the function keyword, followed by:

1.The name of the function.  
2.A list of parameters to the function, enclosed in   parentheses and separated by commas.     
3.The JavaScript statements that define the function, enclosed in curly brackets,  

  **example :** 

  function square(number) {  
  return number * number;  
}  



**Function expressions**  
Such a function can be **anonymous**; it does not have to have a name. For example, the function square could have been defined as

const square = function(number) { return number * number }  
var x = square(4) // x gets the value 16  


**Calling functions**  
Calling the function actually performs the specified actions with the indicated parameters. For example, if you define the function 

**Function Invocation**
The code inside the function will execute when "something" invokes (calls) the function:  

**Function Return**
When JavaScript reaches a return statement, the function will stop executing.


var x = myFunction(4, 3);     
function myFunction(a, b) {
  return a * b;             }
the value will be (12)


![js fun](https://cdn.programiz.com/cdn/farfuture/NdxxeWlRfoHMPgdcWPkeVy1wN9MwAgoqoYqZkFQDMFQ/mtime:1591592059/sites/tutorial2program/files/javascript-function-example1.png)


![js2 fun](https://cdn.programiz.com/cdn/farfuture/b4h4Zo5ZYxj-EyfQyao-J5TqbKEefFgqqusPGLWPFS0/mtime:1591786573/sites/tutorial2program/files/javascript-return-statement.png)