# LINQ
+ Stands for Language-Integrated Query, It's a set of technologies based on the integration of query capabilities directly into the C# language.With LINQ, a query is a first-class language construct, just like classes, methods, events.
+ The most visible "language-integrated" part of LINQ is the query expression, It's written in a declarative query syntax so that you can perform filtering, ordering, and grouping operations on data sources with a minimum of code.
+ You can write LINQ queries in C# for SQL Server databases, XML documents, ADO.NET Datasets, and any collection of objects that supports IEnumerable or the generic IEnumerable<T> interface.
+ To write a complete query you should **First** create a data source **Second** define the query expression and **Third** execute the query in a foreach statement.

#
## Introduction to LINQ Queries (C#)
+ A query is an expression that retrieves data from a data source it's usually expressed in a specialized query language
+ This example shows how the three parts of a query operation (Create, define and excute) are expressed in source code:
````markdown
class IntroToLINQ
{
    static void Main()
    {
        // 1. Data source.
        int[] numbers = new int[7] { 0, 1, 2, 3, 4, 5, 6 };

        // 2. Query creation.
        var numQuery =
            from num in numbers
            where (num % 2) == 0
            select num;
        // 3. Query execution.
        foreach (int num in numQuery)
        {
            Console.Write("{0,1} ", num);
        }
    }
}
        
````
#### Data source
+ So here in the example because the data source is an array, it implicitly supports the generic IEnumerable<T> interface. This fact means it can be queried with LINQ.

#### The query 
+ The query in the example returns all the even numbers from the integer array.

#### Query Execution
+ Iterates throw the numbers in **numQuery** and print the numbers.


