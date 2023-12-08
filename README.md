# Blood-Bank-Management-System
 Problem statement :An application to communicate between the donors and the blood bank and hospitals.

 MOTIVATION OF THE PROJECT:

The project was aimed to be a real life application and what better than having one related to the medicinal field.
The application can be used during blood donation camps wherein searching for a particular donor is an excel sheet becomes tedious work .

FEATURES :
       
 1)The application contains two portals, one for the user and the other for the hospital side .

2)Covers major areas in the city which includes two regions .

> PCMC
>PMC

3)Quick action when in need of blood during times of urgency .

4)Find blood groups easily

5)Find nearby hospitals

6)A questionnaire to check whether the person  is fit to be a donor.

7)A fun awareness quiz about the need and developments in Blood donation camps.

8)A chat bot for help for any confusion and doubts regarding upcoming events.

9)A frequently asked questions section that clears out the doubts 

DATA STRUCTURES  :

1)Queue 

Use of queue data structures for the queuing of the donors after successful registration and donation of blood.
The queue data structures is based on first in , first out method.As the blood has a life of 120 days queue becomes an important data structures here.

Why queues ?

1.Orderly processing

2.Versatility in operations

3.Space and time complexity 
 Queues often have constant time complexity

2)Binary trees

Binary trees are basically non linear data structures which can have minimum 0 nodes and at most 2 nodes .They are of four types and here we have a perfect binary tree for the locations of the hospital.


In the binary tree , our root node is the city of Pune.

The left side of Pune is the PMC area whereas the right side is the PCMC area.

The PMC is further divided into two sections:South and North Pune .

South Pune has two main blood bank centres  in the locations NIBM and Katraj which are on the left and right side of the node respectively.

North Pune has the two main blood bank centres  at the locations Dhanori and Shivaji Nagar .
 
Why use Binary trees ?

1.Stores ordered data 
  The ordered data is stored in a balance and helps in traversals during     operations that include searching ,deletion,etc
  
2.Efficient searching and data retrieval

3.Efficient memory management and allocation.

3)Hashmaps 
HashMap in Java is a data structure that stores key-value pairs. It uses a hashing technique to store elements and provides constant-time performance for basic operations like get and put if the hash function disperses the elements properly among the buckets.We have used hashmaps in the frequently asked questions sections where the hashmap takes key as the question input strings and the value contains the answers to the questions.
The following are the reasons for using hashmaps:

1.Has fast data retrieval

2.Key-value storage 
  Hence,association of unique keys in the questions
  
3.Efficient searching
  Has the search time complexity of O(n)
  
4.Can be optimised according to the uniqueness

LEARNINGS :

The application consists of two main parts: the donor and then server side i.e the hospitals or the blood bank . Integration of both the classes together and how the process would take place if happening in reality helped us to think critically and also understand the real life scenarios which were executed using non linear data structure binary trees.
The questionnaire section helped us understand the systematic order and the criteria on how the actual process takes place .


