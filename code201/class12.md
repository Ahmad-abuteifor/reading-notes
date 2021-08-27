# Charts 
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool 


 **Chart .js**, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page
first you need to download the  **Chart .js**


**Drawing a line chart**
  the first thing we need to do is create a canvas element in our HTML 
 Next, we need to write a script that will retrieve the context of the canvas, 

**Drawing a pie chart**
First, we need the canvas element
 second we need to get the context and to instantiate the chart 
![](https://steemitimages.com/640x0/https://res.cloudinary.com/hpiynhbhq/image/upload/v1514129984/ccmoj2hea1idle17ywfx.png)


# The < canvas> element 
At first sight a < canvas> looks like the < img> element, with the only clear difference being that it doesn't have the src and alt attributes.
 The < canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts 
which are used to create and manipulate the content shown.



using canvas 
1. Drawing shapes with canvas   


The grid or coordinate space. 
Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high.

 Normally 1 unit in the grid corresponds to 1 pixel on the canvas 

2. Drawing paths   
A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color 

 To make shapes using paths
- First, you create the path   
- Then you use drawing commands to draw into the path.  
- Once the path has been created, you can stroke or fill the path to render it.   


3. Drawing a triangle  


![](https://1.bp.blogspot.com/-FrjbToCYscE/YEKKFcURRGI/AAAAAAAAArE/czox5KGYZmsuoT0yJBi2ole9t8_XG1pnwCLcBGAsYHQ/s0/Html%2BJavaScript%2BCanvas%2B2D%2Bgraphics%2Bdrawing.png)


**Applying styles and colors** on the chart 

to make changeing in the color 
use the property strokeStyle or fillStyle

**Transparency**

Drawing text 

The canvas rendering context provides two methods to render text:


using the methods :
- A fillText   
- A strokeText  

**Styling text**
There are some more properties which let you adjust the way the text gets displayed on the canvas: 
the font   
the textalign   
the textbaseline 


