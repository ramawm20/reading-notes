# Data Transfer Objects (DTOs):
+ A DTO is an object that defines how the data will be sent over the network. It's an object that carries data between processes. The motivation for its use is that communication between processes is usually done resorting to remote interfaces (e.g., web services), where each call is an expensive operation. So we use it **To transfer data between the client and the server**.
+ It is a design pattern used to transfer data between layers or modules of an application. It is a simple, lightweight object that typically contains only properties to hold data and does not have any business logic or behavior associated with it.
#
# How to use it ?
+ It is usually an instance of a POCO (plain old CLR object) class used as a container to encapsulate data and pass it from one layer of the application to another. You would typically find DTOs being used in the service layer to return data back to the presentation layer. The biggest advantage of using DTOs is decoupling clients from your internal data structures.
+ So it make the life easier when especially with APIs, MVC applications, and also messaging patterns such as Message Broker. A DTO is a great choice when you would like to pass a lightweight object across the wire — especially when you’re passing your object via a medium that is bandwidth-constrained.
