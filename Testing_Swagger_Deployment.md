# Testing and Swagger and Deployment
## Why this topic matters :
+ All are important in C# Testing is essential for ensuring the quality of your code , Swagger is a tool that can help you document your APIs. This is important because it makes it easier for other developers to understand how to use your APIs. Swagger can also be used to generate client code for your APIs, which makes it even easier for other developers to use them and Deployment is the process of getting your code into production. 

## Swagger
+ Swagger (OpenAPI) is a language-agnostic specification for describing REST APIs. It allows both computers and humans to understand the capabilities of a REST API without direct access to the source code.

+ OpenAPI vs. Swagger=> Swagger and OpenAPI are essentially the same thing. Swagger is the original name of the specification, but it was renamed to OpenAPI in 2016.

+ OpenAPI specification (openapi.json) => The OpenAPI specification is a document that describes the capabilities of your API. It includes information such as the API's endpoints, the request and response payloads, and the HTTP verbs that are supported.

## Testing Controllers
+ Unit tests involve testing a part of an app in isolation from its infrastructure and dependencies. When unit testing controller logic, only the contents of a single action are tested, not the behavior of its dependencies or of the framework itself.   
Set up unit tests of controller actions to focus on the controller's behavior. A controller unit test avoids scenarios such as filters, routing, and model binding. Tests that cover the interactions among components that collectively respond to a request are handled by integration tests

