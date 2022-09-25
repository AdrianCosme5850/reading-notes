# Linked list data structure  

## Overview  

A linked list is a dynamic linear sequence of data values.  
dynamic means that the list can be made bigger after it is created.  
Non-dynamic would be defined beforehand and unchangeable.  
Most languages beside Javascript use non-dynamic arrays, and therefore need linked lists to create dynamic arrays.  
Head is the start of a linked list.  
Tail is the end of the array.  
Node is where the individual data values are contained.  
Next is where the node keeps information on where the next value is in the linked list  
singly moves one way and doubly can move both ways.  
current is what node is being read.  
The tail does have a next value, but it points to null.  
Linked lists are very efficient and linear progress of memory.  
You can have various datatypes in your linked lists.  
A doubly linked list needs previous values. The head element needs a previous value that leads to null.  
Traversal is to read every value from beginning to end.  

## Big O Notation  

A standardised rubric to determine if an algorithim is efficient.  
How many times an operation is performed.  
Quick reference used to say how efficient an algorithim is.  
For analyizing the worst case of efficieny  

every algorithim has inputs. An input is any value we didn't create.  
based on two things: run time and space  

Rates of growth  represents how much the algorithm grows.  
0(1) is constant  
0(log(n)) logarithmic
0(n) is a linear rate of growth.  
0(n^2) is quadratic growth  
0(2^n) is exponential  
input grows at the same rate that the value does.