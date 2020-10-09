Task1 contains func-ptr.c file which implemenats a program that sorts the content of a input file with qsort. 
The input file contains process ids with corresponding priority and arrival time. 
The content is sorted based on priority in descending order. 

However, if two priority values are equal, arrival time is considered as the second condition. The smaller arrival time with equal priority comes first. 
The comparison function in the program returns an integer value less than, equal to, or greater than zero, if the first argument is less than, equal to, or greater than the second argument. 


The program prints the content of the sorted file based on arrival time and priority.

You can run task1 ./task1/qsort test1.csv