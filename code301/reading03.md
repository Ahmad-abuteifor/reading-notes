# the Spread Operator  

The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
  

JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments. 

**What can … do?**
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React
- Combining objects
- Converting NodeList to an array 



**Examples**

1. the spread operator can quickly combine two arrays, an operation known as array concatenation:   
![](https://miro.medium.com/max/1400/1*iw1eXPviushS2_qBA5iyzg.png)


2.  the spread operator can add an item to an another array with a natural, easy-to-understand syntax:  
![](https://laravelnews.imgix.net/images/php-spread-operator-arrays.png?ixlib=php-3.3.1)



3.  useful for combining the properties and methods on objects into a new object:   
 
const  objectOne = {  hello: "🤪"  }
const objectTwo = {  world: "🐻"  }
const objectThree = {  ...objectOne, ...objectTwo, laugh: "😂"  }
console.log(  objectThree  ) // Object { hello: "🤪", world: "🐻", laugh: "😂"   }
const objectFour = {  ...objectOne, ...objectTwo,  laugh: ( ) =  > {  console .log("😂".repeat(5))  }  } 
objectFour.laugh(  ) //   😂😂😂😂😂







## How to Pass Functions Between Components  

first we have to make function and in side of it we can pass in an object 

about the increment function 
The Increment(  ) function determines the next node at the same level. 
You can also increase the level of a node by one at a specified level.


by using state and props we can pass methos from parent to childe 



about the map and the react 



The map() method creates a new array populated with the results of calling a provided function on every element in the calling array. 
map calls a provided callbackFn function once for each element in an array, in order, and constructs a new array from the results   

by using the map() and in side of it the parameter for the index you can acsses to the index that you want 




**List Component**
![](https://daveceddia.com/images/render-a-list.png)

“key” is a special string attribute you need to include when creating lists of elements 

 


**Keys**
Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity 


The best way to pick a key is to use a string that uniquely identifies a list item among its siblings 
