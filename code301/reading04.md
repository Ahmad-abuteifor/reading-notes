# React form 


Controlled Components:
it is a component that renders form elements 
and controls them by keeping the form data in the component's state.   
 

in a controlled component, the form element's data is handled by the React component (not DOM) and kept in the component's state
  

![](https://miro.medium.com/max/1400/1*Dak77-LzpJgk5prToaQJLw.png) 

**Uncontrolled Inputs**
q.2 yeah its neeed becouse React doesn’t track the input’s state. HTML input elements naturally keep track of their own state as part of the DOM,     

The most basic way of working with forms in React is to use what are referred to as “uncontrolled” form inputs. What this means is that React doesn’t track the input’s state
   
 HTML input elements naturally keep track of their own state as part of the DOM, and so when the form is submitted we have to read the values from the DOM elements themselves.   

In order to do this, React allows us to create a “ref” (reference) to associate with an element, giving access to the underlying DOM node   



![](https://d33wubrfki0l68.cloudfront.net/943efcba371cf87a8170b3c49370124d055a5b97/557fa/assets/images/controlled-vs-uncontrolled-cover.png)
**target what the user intering**
It can sometimes be tedious to use controlled components,
 because you need to write an event handler for every way your data can change and pipe all of the input state through
 a React component. This can become particularly annoying when you are converting a preexisting codebase to React, or integrating a React application with a non-React library.  


##  ternary operator 

The conditional (ternary) operator is the only JavaScript operator that takes three operands: a condition followed by a question mark (?), 


 **Use the ternary operator** to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms. 

![](https://www.examtray.com/sites/default/files/styles/wordpress_800x460/public/2019-06/java-ternary-operator-explained.jpg?itok=y-yNVuZl)
q2 .
condition  ? console.log(true);  :  console.log(false);  