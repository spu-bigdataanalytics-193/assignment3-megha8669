In this assignment, I worked on Map Reduce Algorithm. We have a dataset of size 1.6 GB. The data consists of 120 million of records for all commercial flights within the USA from october 1987 to april 2008.

I calculate the number of flights for using map reduce algorithm. First, I downloaded the data and i used lopping each record and and counting each airline's flight. 

Map reduce algorithm requires divide the task in 3 different pieces.

1. Map :- It will work on key & value pairs input.Map takes a set of data and converts it into another set of data, where individual elements are broken down into tuples.

2. Shuffle :- The shuffling is the grouping of the data from various nodes based on the key. It takes a list of outputs coming from"Map function".

3. Reduce :- This task reduce the data from shuffle function.

After completing the reduce phase, the cluster collects the data to form an appropriate result and sends it back. 
