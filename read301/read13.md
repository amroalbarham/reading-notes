# CRUD

## Status Codes Based On REST Methods


- **In your own words, describe what each group of status code represents:**


    - ***100’s = informational response – the request was received, continuing process.***
    - ***200’s = successful – the request was successfully received, understood, and accepted.***
    - ***300’s = redirection – further action needs to be taken in order to complete the request.***
    - ***400’s = client error – the request contains bad syntax or cannot be fulfilled.***
    - ***500’s = server error – the server failed to fulfil an apparently valid request.***


- **What is a status code 202?**


    ***Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.***


- **What is a status code 308?**

    ***This tells the client to use another URL to access the resource and not use the current URL anymore***


- **What code would you use if an update didn’t return data to a client?**


    ***204 No Content - A proper code for updates that don't return data to the client.***


- **What code would you use if a resource used to exist but no longer does?**

   ***410 code is an explicit indication that the requested resource used to exist, but it has since been permanently removed and will not be available in the future.***


- **What is the ‘Forbidden’ status code?**


    ***client error status response code indicates that the server understood the request but refuses to authorize it.***
