**100’s:** 

These codes act as a receipt for the header part, as they inform the client that it has been received, and that the server will attempt processing the transmission demand. 

<br>

200’s: These codes inform the client that its request was accepted.

<br>

300’s : These codes inform the client that the data it’s trying to reach have been relocated, or are not at the requested location.

<br>

400’s: These are error codes that indicate that the request made by the client is invalid, which can be caused by a number of reasons such as incorrect input.

<br>

500’s: These codes indicate that an error has occurred with the request on the server’s side and can be caused due to the server being overloaded, or a certain request that triggered the error.

<br>

Status code 202 means that the client’s request meets all validation criteria, but wasn’t necessarily successful.

<br>

Status code 308 means that the server has information on the location of the moved data, and is able to redirect the client to it.

<br>

Code 204

Code 410

Code 403

<br>

<hr>

<br>

## What is middleware?

Middleware is software that provides common services and capabilities to applications outside of what’s offered by the operating system. Data management, application services, messaging, authentication, and API management are all commonly handled by middleware.

<br>

## What does app.use(express.json()) do?

express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app.

<br>

## What is the difference beween PUT and PATCH?

PUT is a method of modifying resource where the client sends data that updates the entire resource . PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

<br>

## How do you make a defalut value in a schema?

Your schemas can define default values for certain paths. If you create a new document without that path set, the default will kick in.

<br>

## What does a 500 error status code mean?

The HTTP status code 500 is a generic error response. It means that the server encountered an unexpected condition that prevented it from fulfilling the request. This error is usually returned by the server when no other error code is suitable.