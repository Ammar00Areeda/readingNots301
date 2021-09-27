# APIs
## What does REST stand for?

Is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.

## REST APIs are designed around a **resources** .

## What is an identifer of a resource? Give an example?

A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be.

## What are the most common HTTP verbs?

The most common operations are GET, POST, PUT, PATCH, and DELETE.

## What should the URIs be based on?

resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

## Give an example of a good URI?

example.com/articles/good-uri-design

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

APIs that make a lot of network calls are viewed as low-quality because they cause application performance to suffer. This is due to the fact that each call has data overhead (such as sender information, headers, and authentication), which slows down an application and increases network delay for each request.
## What status code does a successful GET request return?

A successful GET method typically returns HTTP status code 200 .

## What status code does an unsuccessful GET request return?

The method should return 404 .

## What status code does a successful POST request return?

it returns HTTP status code 201 .

