# The local storage 


**A BRIEF HISTORY OF LOCAL STORAGE HACKS**

In the beginning, there was only Internet Explorer. Or at least,
 that’s what Microsoft wanted the world to think. To that end,  
Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars,
 Internet Explorer
userData allows web pages to store up to 64 KB of data per domain, 
in a hierarchical XML-based structure. 


In **2002**, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading 
name of “Flash cookies.” Within the Flash environment, the feature is properly known as Local Shared Objects. 



In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers. 

 By 2009, dojox.storage could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5 storage that was only implemented in older versions of Firefox. 

INTRODUCING HTML5 STORAGE  
 HTML5 Storage : it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, 

**some browsers support the html5**

![](https://speckyboy.com/wp-content/uploads/2012/03/chart1.png) 

you can use the function 

function supports_html5_storage(   ) {    
  try {    
     r eturn 'localStorage' in window && window[' localStorage' ]  != =  null;  
    } catch ( e) {     
    r eturn false;  
  }
}  


**USING HTML5 STORAGE**
HTML5 Storage is based on named key/value pairs  
The named key is a string. The data can be any type supported by JavaScript, including :
1.  strings  
2. Booleans  
3. integers  
4. floats.



you will need to use functions like parseInt(  ) or parseFloat(  ) v  


**TRACKING CHANGES TO THE HTML5 STORAGE AREA**


If you want to keep track programmatically of when the storage area changes, you can trap the storage event.  
The storage event is fired on the window object whenever setItem( ), removeItem( ), or clear( ) is called and actually changes something.

![](https://image.slidesharecdn.com/html5localstorage-140511235722-phpapp01/95/html5-local-storage-12-638.jpg?cb=1399852926)

The storage event is not cancelable. From within the handle_storage callback function, there is no way to stop the change from occurring.
 It’s simply a way for the browser to tell you, 




