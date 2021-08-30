**What are component lifecycle events?**

React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. 

 ![](https://miro.medium.com/max/2000/0*0saPKFiTUk6W3FYp)

Mounting :
hen an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor  

Updating:
Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.
  

Unmounting:
The final phase of the lifecycle if called when a component is being removed from the DOM.  



render(  )
Render is the only required method in a class component. It will examine this.props and this.state when called. The render function should not modify the component state because it would cause a lot of bugs by changing the state every time it rerenders. I also should not directly interact with the browser.


componentDidMount()
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here  


the  render will be the first 

shouldComponentUpdate()  
The default behavior in react is to rerender after every state change. Setting shouldComponentUpdate() to false allows you to prevent this from happening. This is in order to optimize performance.





props and state 

the big difference tate is internal and controlled by the component itself while props are external and controlled by whatever renders the component 

we can render it whenever there is a change in their state or props. 

in the props you cant change the component have to chANGE IT out side   