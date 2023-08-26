# Why this topic matters?

The **Model-View-Controller (MVC)** architectural pattern is a popular way to design and develop web applications. It separates the application logic into three distinct layers: the model, the view, and the controller. This separation of concerns makes applications easier to develop, test, and maintain.

In this module, we will be learning about the basics of MVC. We will learn about the different components of MVC and how they work together. We will also learn about some of the benefits of using MVC.

### What is MVC?

The **Model-View-Controller (MVC)** is an architectural pattern that separates an application into three main logical components: the *model*, the *view*, and the *controller*. Each of these components is built to handle specific development aspects of an application. MVC is one of the most frequently used industry-standard web development frameworks to create scalable and extensible projects.

### What are the three components of MVC?

**Model**

The Model component corresponds to all the data-related logic that the user works with. This can represent either the data being transferred between the View and Controller components or any other business logic-related data. For example, a Customer object will retrieve customer information from the database, manipulate its data, and update it back to the database or use it to render data.

**View**

The View component is used for all the UI logic of the application. For example, the Customer view will include all the UI components such as text boxes, dropdowns, etc., that the end user interacts with.

**Controller**

Controllers act as an interface between Model and View components to process all the business logic and incoming requests. They manipulate data using the Model component and interact with the Views to render the final output. For example, the Customer controller will handle all interactions and inputs from the Customer View, update the database using the Customer Model, and also be used to view the Customer data.

### What are Tag Helpers?

**Tag Helpers** enable server-side code to participate in creating and rendering HTML elements in Razor files. For example, the built-in `ImageTagHelper` can append a version number to the image name. Whenever the image changes, the server generates a new unique version for the image, ensuring clients receive the current image rather than a cached one. Many built-in Tag Helpers exist for common tasks such as creating forms, links, loading assets, and more. Additional Tag Helpers are available in public GitHub repositories and as NuGet packages. Tag Helpers are authored in C# and target HTML elements based on element names, attribute names, or parent tags.

### Bootstrap:

**Bootstrap** is a free, open-source front-end development framework for creating websites and web apps. Designed for responsive development of mobile-first websites, Bootstrap provides a collection of syntax for template designs. As a framework, Bootstrap includes the basics for responsive web development, allowing developers to insert code into a pre-defined grid system. Bootstrap is built on Hypertext Markup Language (HTML), cascading style sheets (CSS), and JavaScript. Web developers using Bootstrap can build websites much faster without spending time worrying about basic commands and functions.
