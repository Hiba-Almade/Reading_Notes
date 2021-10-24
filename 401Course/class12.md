# Spring request:


#### RequestMapping - HTTP method

`>` The HTTP method parameter has no default. So, if we don't specify a value, it will be assigned to any HTTP request.

`>` RequestMapping can narrow the mapping further by specifying a request header.

`>` We can assign a request based on the address it accepts via the @RequestMapping headers

#### RequestMapping with path variables

`>` Parts of the mapping URI can be bound to variables via the PathVariable annotation.

`>` If the method parameter name matches the path variable name exactly, this can be simplified by using PathVariable without a value.

`>` MultiplePathVariable: A more complex URI may need to map multiple parts of a URI to multiple values.


#### RequestMapping with request parameters

`>` @RequestMapping allows easy assignment of URL parameters using the @RequestParam annotation.

> Visit Spring Initializr to create a new project with the required dependencies.