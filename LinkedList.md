# Big O: Analysis of Algorithm Efficiency
## Big O(oh) notation is used to describe the efficiency of an algorithm or function it describe the Worst Case of efficiency an algorithm can have in performing it’s job we should consider 4 keys in order to analyze these factors:
+ Input Size:
The size of the parameter values that are read by the algorithm not just the number of it also consider the size of each one, The greater it's size, the greater the complexity.

+ Units of Measurement: To quantify the Running Time in our analysis, we will consider: First the time that the function takes from the start to the end second The number of operation executed and also the number of basic operation .And for the Memory Space consider : The amount of space needed to hold the: code for the algorithm, the input data.,  output data and working space during the calculation.

+ Orders of Growth: The Order of Growth represents the increase in Running Time or Memory Space. Constant Complexity means that no matter what inputs are thrown at algorithm, it always uses the same amount of time or space, Logarithmic Complexity represents a function that sees a decrease in the rate of complexity growth, Linear Complexity, the size of inputs ‘n’ will directly determine the amount of Memory Space used and Running Time length.
4.Worst Case, Best Case, Average Case:
Even though Big O describes the Worst Case for algorithm efficiency, we can still think about Best and Average cases This case runs the longest for all possible inputs of n.
Worst Case:  This case runs the longest for all possible inputs of n.
Best Case :This case runs the quickest for all possible inputs of n.
Average Case: The average case makes a typical assumption about the possible inputs of size ‘n’ and how they might affect efficiency. It's NOT the best case and worst case averaged together.


# Linked lists:
+ It's sequence of nodes that are connected to each other and each one of these nodes refer to the next node. We have 2 types of it :
1.Singly linked list: It has only one reference to the next node
2.Doubly linked lists: Refers to the both the next and previous node.
When we traverse the linked list we will use the next not for or foreach The best way is to use While().