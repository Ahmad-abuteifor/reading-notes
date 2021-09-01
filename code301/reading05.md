# Thinking in React


**React** is, in our opinion, the premier way to build big,
 fast Web apps with JavaScript




Break The UI Into A Component Hierarchy
you shoud do  is to draw boxes around every component (and subcomponent)
 in the mock and give them all names. 


One such technique is **the single responsibility principle**: which is  , 


that is, a component should ideally only do one thing. If it ends up growing, 
it should be decomposed into smaller subcomponents.


![](https://reactjs.org/static/9381f09e609723a8bb6e4ba1a7713b46/90cbd/thinking-in-react-components.png)
 the number in the photo 

1. FilterableProductTable (orange): contains the entirety of the example
2. SearchBar (blue): receives all user input
3. ProductTable (green): displays and filters the data collection based on user input
4. ProductCategoryRow (turquoise): displays a heading for each category
5. ProductRow (red): displays a row for each product



**What does it mean to build a ‘static’ version of your application?**

 build a version that takes your data model and renders the UI but has no interactivity. 
It’s best to decouple these processes because building a static version requires a lot of typing and no thinking



**after that  what do you need to add?** 
you need to build components that reuse other components and pass data using props. props are a way of passing data from parent to child


**the three questions about you can ask to determine if something is state**:  
. Is it passed in from a parent via props? If so, it probably isn’t state.  
. Does it remain unchanged over time? If so, it probably isn’t state.  
. Can you compute it based on any other state or props in your component? If so, it isn’t state. 





his is often the most challenging part for newcomers to understand, so follow these steps to figure it out:

For each piece of state in your application:

1. Identify every component that renders something based on that state.  
2. Find a common owner component (a single component above all the components that need the state in the hierarchy).  
3. Either the common owner or another component higher up in the hierarchy should own the state.  
4. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.  

 