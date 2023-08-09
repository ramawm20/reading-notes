# Roles, Claims and JWT Tokens
## Why this topic Matters ?!
+ The topics of Roles, Claims, and JWT (JSON Web Tokens) are crucial in C# and other programming languages for building secure and flexible authentication and authorization systems in various applications, such as web applications, APIs, and services.

## Claims-based Authorization in ASP.NET Core =>
+ Claims-based authorization is a powerful and flexible approach to managing access control and permissions in ASP.NET Core applications. Unlike traditional role-based authorization, which relies solely on predefined roles, claims-based authorization focuses on individual attributes or claims associated with a user. This approach provides finer-grained control over access to resources and allows for more dynamic and context-aware authorization decisions.

+ Adding claims checks
+Claim based authorization checks:

  1. Are declarative.
  2. Are applied to Razor Pages, controllers, or actions within a controller.
  3. Can not be applied at the Razor Page handler level, they must be applied to the Page.


## Intro to Claims =>
+ The difference between Authentication and Authorisation:
    + First of all, we should clarify the difference between these two dependent facets of security. The simple answer is that Authentication is the process of determining who you are, while Authorisation revolves around what you are allowed to do, i.e. permissions. Obviously before you can determine what a user is allowed to do, you need to know who they are, so when authorisation is required, you must also first authenticate the user in some way.
+ Claims-based authentication
The concept of claims-based authentication can be a little confusing when you first come to it, but in practice it is probably very similar to approaches you are already using. You can think of claims as being a statement about, or a property of, a particular identity. That statement consists of a name and a value. For example you could have a DateOfBirth claim, FirstName claim, EmailAddress claim or IsVIP claim. Note that these statements are about what or who the identity is, not what they can do.   
The identity itself represents a single declaration that may have many claims associated with it. For example, consider a driving license. This is a single identity which contains a number of claims - FirstName, LastName, DateOfBirth, Address and which vehicles you are allowed to drive. Your passport would be a different identity with a different set of claims.


## JWT Authentication =>
+ JSON Web Token (JWT) is a means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS) and/or encrypted using JSON Web Encryption (JWE).    
In simple terms, it is just another way of encoding JSON object and use that encoded object as access tokens for authentication from the server.
