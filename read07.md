### Express Routing
Routing refers to how an application’s endpoints (URIs) respond to client requests, for more declaration:
Routing is where an Express application responds to a client request from a URL or path and a specific HTTP request method, like GET or POST.

### Middleware functions
Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.
We can use Middleware functions for:

- Execute any code.
- Make changes to the request and the response objects.
- End the request-response cycle.
- Call the next middleware function in the stack.

If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.
Server testing verifies that the services you need to develop your apps are working as intended.

### Test Pyramid
The testing pyramid is a concept that helps you to balance your tests better. also, it delivers a graphical representation of a best-case test scenario.
1. Units. 1.Integration. 1.Acceptance.
