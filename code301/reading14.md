# OAuth 




## what is OAuth
OAuth definition
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.


![](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/media/authentication-patterns/oauth.png)

**Give an example of what using OAuth would look like.**

The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.








## How does OAuth work? 
he user then initiates a feature/transaction that needs to access another unrelated site or service

### What are the steps that it takes to authenticate the user?

*The following happens (greatly simplified):*

1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.  
2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.  
3. The first site gives this token and secret to the initiating user’s client software.  
4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).  
5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.  

6. The user approves (or their software silently approves) a particular transaction type at the first website.  
7. The user is given an approved access token (notice it’s no longer a request token).  
8. The user gives the approved access token to the first website.
The first website gives the access token to the second website as proof of authentication on behalf of the user.  

9. The second website lets the first website access their site on behalf of the user.
10. The user sees a successfully completed transaction occurring.
OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).




### What is OpenID?

**OpenID**
 began life in 2005 as a means for logging into the then-popular LiveJournal blogging site but quickly spread to other sites. The idea, in the early days of Web 2.0, was that rather than having multiple logins for multiple website




### What is the difference between authorization and authentication?


 - Authentication, in the form of a key. The lock on the door only grants access to someone with the correct key in much the same way that a system only grants access to users who have the correct credentials.

 - Authorization, in the form of permissions. Once inside, the person has the authorization to access the kitchen and open the cupboard that holds the pet food. The person may not have permission to go into the bedroom for a quick nap. 


![](https://miro.medium.com/max/1080/1*quwFs1fFCvTvLT80e_QHVA.png)


#### What is Authorization Code Flow?
 Authorization code flow is used to obtain an access token to authorize API requests. ... Access tokens while having a limited lifetime, can be renewed with a refresh token. A refresh token is valid indefinitely and provides ability for your application to schedule tasks on behalf of a user without their interaction




### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps  





### What is Implicit Flow with Form Post?
  Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates.





  #### What is Client Credentials Flow?
  
  The Client Credentials flow is a server to server flow. There is no user authentication involved in the process. ... This flow is useful for systems that need to perform API operations when no user is present.




  #### What is Device Authorization Flow?
   instructs the user to review the authorization request on a secondary device, such as a smartphone,




   ### What is Resource Owner Password Flow?
   The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token


hihihihihihi