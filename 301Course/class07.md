# REST:

    ***Representational state transfer:*** is a software architectural style that was created to guide the design and development of the architecture for the World Wide Web. REST defines a set of constraints for how the architecture of an Internet-scale distributed hypermedia system, such as the Web, should behave.

    The REST architectural style emphasises the scalability of interactions between components, uniform interfaces, independent deployment of components, and the creation of a layered architecture to facilitate caching components to reduce user-perceived latency, enforce security, and encapsulate legacy systems.

   REST has been employed throughout the software industry and is a widely accepted set of guidelines for creating stateless, reliable web services.


### Who is Roy Fielding?

    Roy Thomas Fielding (born 1965) is an American computer scientist, one of the principal authors of the HTTP specification and the originator of the Representational State Transfer (REST) architectural style. He is an authority on computer network architecture and co-founded the Apache HTTP Server project.

### Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

    Nearly every website nowadays seems to greet you with a Chatbot. They range from simple programs with limited conversational capabilities, to intelligent, conversationally capable bots thanks to advances in Natural Language Processing (NLP) and Deep Learning.

### What is the HTTP protocol that Fielding and his friends created?

    The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypermedia information systems. It is a generic, stateless, protocol which can be used for many tasks beyond its use for hypertext, such as name servers and distributed object management systems, through extension of its request methods, error codes and headers. A feature of HTTP is the typing and negotiation of data representation, allowing systems to be built independently of the data being transferred.

### What does a GET do?

    * GET is used to request data from a specified resource.
    * GET is one of the most common HTTP methods.
    * GET requests can be cached
    * GET requests remain in the browser history
    * GET requests can be bookmarked
    * GET requests should never be used when dealing with sensitive data
    * GET requests have length restrictions
    * GET requests are only used to request data (not modify)

### What does a POST do?

    * POST is used to send data to a server to create/update a resource.
    * POST requests are never cached
    *POST requests do not remain in the browser history
    * POST requests cannot be bookmarked
    * POST requests have no restrictions on data length

### What does PUT do?

    * PUT is used to send data to a server to create/update a resource.

    >> The difference between POST and PUT is that PUT requests are idempotent. That is, calling the same PUT request multiple times will always produce the same result. In contrast, calling a POST request repeatedly have side effects of creating the same resource multiple times.

### What does PATCH do?

    * PATCH method is a request method supported by the Hypertext Transfer Protocol (HTTP) protocol for making partial changes to an existing resource.
    * PATCH method provides an entity containing a list of changes to be applied to the resource requested using the HTTP Uniform Resource Identifier (URI).



![http](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview/fetching_a_page.png)