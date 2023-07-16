
# Introduction to Databases and ERDs:

## Database Schema
+ A database schema defines how data is organized within a relational database; this is inclusive of logical constraints such as, table names, fields, data types, and the relationships between these entities. Schemas commonly use visual representations to communicate the architecture of the database, becoming the foundation for an organization’s data management discipline. This process of database schema design is also known as data modeling.
+ Why do we use them? => The importance of a database schema lies in its ability to outline the logical layout of a database and keep data organized. It helps users identify which tables, columns, and relationships exist between objects, enabling them to efficiently access, query, or modify data.
+ What do they looks like? => Tits a tables associated with columns, along with any relationships between the tables indicated By keys.

## What are the different types of Database Keys?
+ Primary key => It is a special relational database table column (or combination of columns) designated to uniquely identify each table record A primary key is used as a unique identifier to quickly parse data within the table. **A table cannot have more than one primary key** It must contain a unique value for each row of data, It cannot contain null values and Every row must have a primary key value.
+ Foriegn Key => A FOREIGN KEY is a field (or collection of fields) in one table, that refers to the PRIMARY KEY in another table. The table with the foreign key is called the **child table**, and the table with the primary key is called the referenced or **parent table**.
+ The composite Key => A composite key, in the context of relational databases, is a combination of two or more columns in a table that can be used to uniquely identify each row in the table. Uniqueness is only guaranteed when the columns are combined; when taken individually the columns do not guarantee uniqueness.

## What are Relationships in a relational database? 
+ Database relationships are associations between tables that are created using join statements to retrieve data.
+ **A One-to-One relationship**=>  is like a link between two tables of data in which each record occurs only once in each table. For example, employees and the automobiles they drive may have a One-to-One relationship.
+ **A many-to-many relationship**=> It exists when one or more items in one table can have a relationship to one or more items in another table. For example: Your Order table contains orders placed by multiple customers (who are listed in the Customers table), and a customer may place more than one order.
+ **A 1 to Many**  => A one-to-many relationship exists in a relational database when one row in table A is linked to many rows in table B, but only one row in table B is linked to one row in table A.





