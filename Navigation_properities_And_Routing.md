# Navigation Properties and Routing
## Why this topic matters?!
+ Navigation properties and routing in ASP.NET (C#) is essential for building efficient, user-friendly, and maintainable web applications. It allows developers to work with data more effectively, organize their codebase, and provide a better user experience, ultimately leading to the success of the application.

## Routing with MVC:
+ The ASP.NET Routing module is responsible for mapping incoming requests to particular MVC controller actions, When you create a new ASP.NET MVC application, the application is already configured to use ASP.NET Routing. ASP.NET Routing is setup in two places: 
   1. First, ASP.NET Routing is enabled in your application's Web configuration file.
   2. Second, and more importantly, a route table is created in the application's Global.asax file.
+ In general it's a process of mapping the browser request to the controller action and return response back.

## Routing with core :
+ **Routing** is responsible for matching incoming HTTP requests and dispatching those requests to the app's executable endpoints. Endpoints are the app's units of executable request-handling code. Endpoints are defined in the app and configured when the app starts. The endpoint matching process can extract values from the request's URL and provide those values for request processing. Using endpoint information from the app, routing is also able to generate URLs that map to endpoints.
+ **Routing concepts:**   
The routing system builds on top of the middleware pipeline by adding the powerful endpoint concept. Endpoints represent units of the app's functionality that are distinct from each other in terms of routing, authorization, and any number of ASP.NET Core's systems.
+ **URL matching:**    
Is the process by which routing matches an incoming request to an endpoint.
Is based on data in the URL path and headers.
Can be extended to consider any data in the request.
+ **Route template precedence and endpoint selection order:**     
Route template precedence is a system that assigns each route template a value based on how specific it is. Route template precedence:

   1. Avoids the need to adjust the order of endpoints in common cases.
   2. Attempts to match the common-sense expectations of routing behavior.
+ **URL generation:**     
Is the process by which routing can create a URL path based on a set of route values.
Allows for a logical separation between endpoints and the URLs that access them.
+ **Route constraint reference**    
Route constraints execute when a match has occurred to the incoming URL and the URL path is tokenized into route values. Route constraints generally inspect the route value associated via the route template and make a true or false decision about whether the value is acceptable. Some route constraints use data outside the route value to consider whether the request can be routed. For example, the HttpMethodRouteConstraint can accept or reject a request based on its HTTP verb. Constraints are used in routing requests and link generation.
