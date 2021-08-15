# APIs:

## What does REST stand for?

Representational state transfer (REST)

## REST APIs are designed around a _

REST is a software architectural style that defines the set of rules to be used for creating web services. Web services which follow the REST architectural style are known as RESTful web services.

##  What is an identifer of a resource? Give an example.

The target of an HTTP request is called a "resource", whose nature isn't defined further; it can be a document, a photo, or anything else. Each resource is identified by a Uniform Resource Identifier (URI) used throughout HTTP for identifying resources.

## What are the most common HTTP verbs?

The primary or most commonly-used HTTP methods are POST, GET, PUT, PATCH, and DELETE. These methods correspond to create, read, update, and delete (or CRUD) operations, respectively. There are a number of other methods, too, but they are utilized less frequently.

## What should the URIs be based on?
The URI comprises: A non-empty scheme component followed by a colon ( : ), consisting of a sequence of characters beginning with a letter and followed by any combination of letters, digits, plus ( + ), period ( . ), or hyphen ( - ).

`>` For example:
![ex](https://css-tricks.com/wp-content/uploads/2010/07/urlbestpractices.jpg)
![ex](https://morethancoding.files.wordpress.com/2011/09/rest-uri-orig1.png)

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation

`>` The reason why chatty APIs are considered poor quality is because requiring multiple network calls will slow down an application. This is because each call contains data overhead (i.e. sender information, headers, authentication) which will slow down an application as well as network latency per each request.

## What are Status Codes with `GIT` and `POST` method? 

1xx: Informational – Request received, continuing process
2xx: Success – The action was successfully received, understood, and accepted
3xx: Redirection – Further action must be taken in order to complete the request
4xx: Client Error – The request contains bad syntax or cannot be fulfilled
5xx: Server Error – The server failed to fulfill an apparently valid request


### What status code does a successful GET request return?
201

### What status code does an unsuccessful GET request return?
400

### What status code does a successful POST request return?
200

### What status code does a successful DELETE request return?
204
