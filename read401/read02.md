## Express

- **What’s the difference between PUT and PATCH?**

    *The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.*

- **Provide links to 3 services or tools that allow you to “mock” an API for development like json-server**

   * Postman
   * Stoplight
   * Mocky.io
   * Killgrave


- **Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?**

    *apiDocjs: Inline Documentation for RESTful web APIs. It creates a documentation from API annotations in your source code. It includes a default template which uses handlebars, Bootstrap, RequireJS and jQuery for the output of the generated apidata.js and apiproject.js as a html-page; Swagger Inspector: Test and Document Your APIs With Ease. It is a free cloud-based API testing and documentation tool to simplify the validation of any API and generate its corresponding OpenAPI documentation. apiDocjs and Swagger Inspector can be primarily classified as "API" tools.*



- **Compare and contrast SOAP and ReST**

    + *SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State * Transfer.*
    + *SOAP is a protocol whereas REST is an architectural pattern.*
    + *SOAP uses service interfaces to expose its functionality to client applications while REST uses Uniform Service locators to access to the components on the hardware device.*
    + *SOAP needs more bandwidth for its usage whereas REST doesn’t need much bandwidth.*
    + *SOAP only works with XML formats whereas REST work with plain text, XML, HTML and JSON.*
    + *SOAP cannot make use of REST whereas REST can make use of SOAP.*



**Document the following Vocabulary Terms** 


   - **Web Server:** is computer software and underlying hardware that accepts requests via HTTP, the network protocol created to distribute web pages, or its secure variant HTTPS.

   - **Express:** is a back end web application framework for Node.js, released as free and open-source software under the MIT License. It is designed for building web applications and APIs. It has been called the de facto standard server framework for Node.js

   - **Routing:** refers to how an application’s endpoints (URIs) respond to client requests.
   
   - **WRRC:** web request/response cycle traces how a user's request flows through the app.


**An introduction to NodeJS and Express**

  ***Node (or more formally Node.js) is an open-source, cross-platform runtime environment that allows developers to create all kinds of server-side tools and applications in JavaScript. The runtime is intended for use outside of a browser context (i.e. running directly on a computer or server OS). As such, the environment omits browser-specific JavaScript APIs and adds support for more traditional OS APIs including HTTP and file system libraries.***


**What is NPM?**

***npm is the world's largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well.***

  **npm consists of three distinct components:**    

 - **the website**
 - **the Command Line Interface (CLI)***
- **the registry**


**What is TDD?**

**Test-driven development” refers to a style of programming in which three activities are tightly interwoven: coding, testing and design .**

***It can be succinctly described by the following set of rules:***

- **write a “single” unit test describing an aspect of the program**
- **run the test, which should fail because the program lacks that feature**
- **write “just enough” code, the simplest possible, to make the test pass**
- **“refactor” the code until it conforms to the simplicity criteria**
- **repeat, “accumulating” unit tests over time**

      
**CI/CD**


***Ontino integration(CI) is the code and practice philosophy which encourages development teams to make minor changes and often check in repositories for version controls. Since most current apps need to create code on many platforms and tools, the team requires a system that can integrate and validate its modifications.***