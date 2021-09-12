# Status Codes Based On REST Methods



### Status ClassesPermalink

**group  100**:
they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client  


**group  200**:

They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending



**group  300**:

 They tell the client that the resource they are requesting isn’t available at the expected location anymore


**group  400**:

 Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server




![dsd](https://www.outsystems.com/blog/-/media/images/blog/posts/handling-http-status-codes-consuming-rest/handling-http-status-codes-12.png?h=687&w=750&updated=20190628134420)

 ### What is a status code 202?
If the update is done asynchronous, this code can be used. It should include an URL to access the updated resource or an URL to check if the update has been succeeded





### What is a status code 308?

 This is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future. 



 **What code would you use if an update didn’t return data to a client?**

 we can use *204*






**Forbidden’ status code is**
 The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.









### What does app.use(express.json()) do?
express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app.





### What is the difference between PUT and PATCH?
The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.



**How do you make a defalut value in a schema?**
my  schemas can define default values for certain paths. If i  create a new document without that path set, the default will kick in.



**What does a 500 error status code mean?**

Internal Server Error:server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request






**What is the difference between a status 200 and a status 201?**

- 200
The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed.


- 201 
A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).