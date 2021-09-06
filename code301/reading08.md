# rest 


**What is REST?**
Roy Fielding proposed Representational State Transfer (REST) as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP.




**REST APIs are designed around**
a around resources, which are any kind of object, data, or service that can be accessed by the client


##### What is an identifer of a resource? Give an example.  

1. the URI for a particular customer   
2. web APIs use JSON as the exchange format   




##### the most common operations are 
1. GET  
2. POST  
2. PUT  
3. PATCH  
4. DELETE.
 


**What should the URIs be based on??**
parameterized URI paths,  



**good url**
1. https://adventure-works.com/orders //  



**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**
 "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request. 





 ##### What status code does a successful GET request return?

 A successful GET method typically returns HTTP status code 200 (OK).
 
 
 #### What status code does an unsuccessful GET request return?

 
  If the resource cannot be found, the method should return 404 (Not Found).




**What status code does a successful POST request return?**
  If a POST method creates a new resource, it returns HTTP status code 201 (Created).


  **What status code does a successful DELETE request return?**
  If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content),





  for writing my name: 
  1. ^ means start of the string, 
  2.  $ means end of the string.
3. […]  is a character class

