# What is OAuth

1. **What is OAuth?**

***Auth doesn’t share password data but instead uses authorization tokens to prove an identity between consumers and service providers. OAuth is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password***

2. **Give an example of what using OAuth would look like.**

    ***The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.***

 3. **How does OAuth work? What are the steps that it takes to authenticate the user?**

    - ***The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.***

    - ***The second site generates a one-time token and a one-time secret unique to the transaction and parties involved. The first site gives this token and secret to the initiating user’s client software.***

    - ***The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).***

    - ***If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.***

    - ***The user approves (or their software silently approves) a particular transaction type at the first website.***

    - ***The user is given an approved access token (notice it’s no longer a request token).***

    - ***The user gives the approved access token to the first website.***

    - ***The first website gives the access token to the second website as proof of authentication on behalf of the user.***

    - ***The second website lets the first website access their site on behalf of the user.***


    - ***OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons)***  


4. **What is OpenID?**

***OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans.***



## Authorization and Authentication flows


### Authorization Code Flow


*Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization Code for a token.*


### Hybrid Flow


*Applications that are able to securely store Client Secrets may benefit from the use of the Hybrid Flow, which combines features of the Authorization Code Flow and Implicit Flow with Form Post to allow your application to have immediate access to an ID token while still providing for secure and safe retrieval of access and refresh tokens. This can be useful in situations where your application needs to immediately access information about the user, but must perform some processing before gaining access to protected resources for an extended period of time.*


### Implicit Flow with Form Post


*As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets. While this is no longer considered a best practice for requesting Access Tokens, when used with Form Post response mode, it does offer a streamlined workflow if the application needs only an ID token to perform user authentication.*          
