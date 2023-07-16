# Entity Framework and APIs
## Why this topic matters ??
+ It allow the developers to work with data at a higher level of abstraction. Entity Framework allows you to develop and maintain data-oriented apps with less code than traditional applications. This combination of EF and APIs allows developers to build robust and scalable applications efficiently using C# and ASP.NET frameworks.

## MVC with EF :
+ First MVC (Model-View-Controller) is a software architectural pattern commonly used in web application development. When combined with Entity Framework (EF), MVC provides a powerful framework for building robust and maintainable applications that interact with databases. The Model:  the model represents the data and business logic of an application, View: The view in MVC represents the user interface or the presentation layer of an application and The controller in MVC handles user interactions, coordinates the model and view, and processes incoming requests.
Entity framework is an Object Relational Mapping (ORM) framework that offers an automated mechanism to developers for storing and accessing the data in the database.

+ By combining MVC with Entity Framework, developers can benefit from the separation of concerns provided by the MVC pattern, where the model represents the data and logic, the view focuses on the user interface, and the controller handles the application flow. EF simplifies the data access layer by providing a high-level abstraction over database operations, allowing developers to work with C# objects and LINQ queries instead of writing raw SQL.
+ This combination of MVC and EF promotes a structured and modular approach to building applications, making them more maintainable, testable, and scalable. It also enables developers to leverage EF's features, such as database independence, automatic migrations, and caching, to streamline the development process and improve overall application performance.
## Entity Framework Core:
+ Entity Framework (EF) Core is a lightweight, extensible, open source and cross-platform version of the popular Entity Framework data access technology, It can serve as an object-relational mapper . With EF Core, data access is performed using a **Model** which made up of entity classes and objects , Instances of your entity classes are retrieved from the database using Language Integrated Query **(LINQ)** and the Data is created, deleted, and modified in the database using **instances** of your entity classes


## Data Seeding :
+ Data seeding is the process of populating a database with an initial set of data it done with 3 ways =>
1. Model seed data
2. Manual migration customization
3. Custom initialization logic


