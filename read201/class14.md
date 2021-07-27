# Transforms 

With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size,

**Transform Syntax**
The actual syntax for the transform property is quite simple, including the transform property followed by the value 

![](https://www.w3.org/TR/css-transforms-1/examples/origin1.svg)


**2D Transforms**
Two-dimensional transforms work on the x and y axes,  

known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis 


**2D Rotate** 

 provides the ability to rotate an element from 0 to 360 degrees 

 Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.   



![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQAgq09hKbPXszjt7fCNQblevcIMlj_f1J4wQ&usqp=CAU)

**2D Scale**
Using the scale value within the transform property allows you to change the appeared size of an element



*2D Translate*
The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change 
the position of an element on the horizontal axis 
while using the translateY value will change the position of an element on the vertical axis.



Transform Origin

As previously mentioned, 
the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the transform-origin property may be used. 




# Transitions
for a transition to take place, an element must have a change in state, and different styles must be identified for each state 
The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.




*Transitional Property*
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s
 different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions. 


**Transition Duration**
The duration in which a transition takes place is set using the transition-duration property. 
![](https://daqxzxzy8xq3u.cloudfront.net/wp-content/uploads/2019/07/15114208/css-transition-illustration.jpg)



some of the animation 
![](https://miro.medium.com/max/1000/0*z-NzK5spBWCM5gp_.jpg)

