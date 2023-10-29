# data-structures-and-algorithms
The list of data structures and algorithms

## 1. Data Structure Introduction
**What is data structure?**
- Data structure is a way to store and organize data so that it can be used efficiently.
- As per name indicates itself that organizing the data in memory.
- The data structure is not any programming language like C, C++, Java, Python, etc. It is set of algorithms that we can
use in any programming language to structure data in memory.

Data structures classify into primitive data structure (int, pointer, char, float, double) and non-primitive data
structure (linear, non-linear).

Linear data structure means the arrangement of data in the sequential manner such as arrays, linked list, stacks, and
queues. In this data structure, one element is connected to only one another element in a linear form.

Non-linear data structure means when one element is connected to the "n" number of elements such as trees and graphs.

```
Algorithms ==> Abstract data types ==> Set of rules
```
To structure the data in memory, variety number of algorithms are proposed, and all these algorithms are known as
**Abstract Data Types**. An abstract data types (ADT) tell what is to be done and data structure tells how is to be done?.
ADT gives us the blueprint while data structure provides the implementation part.

What is **Data**? Data can be defined as the elementary value/ collection of values.
For example: student's name, id are the data about the student.

What is **Record**? Record can be defined as collection of various data items. For example: student entity: name, address,
course and marks and be grouped together to a form record.

What is **File**? File is a collection of various records of one type of entity. For example: if there are 60 employees
in class, then there will be 20 records in related file where record contains info of employees.

What is **Attribute and Entity**? An entity represents class of certain objects. It contains various attributes, each
attribute represents particular property of that entity.







## 1. Basics

### 1.1 Array

#### 1.1.1 Introduction
Arrays hold values of the same type at contiguous memory locations. In an array, we're usually concerned about two 
things - the position/ index of an element and the element itself. These arrays have advantages and disadvantages:

##### Advantages:
- Store multiple elements of the same type with one single variable name.
- Access elements are fast based on the index.

##### Disadvantages:
- Add/ Remove elements into/ from the middle of an array is quite slow because the remaining elements need to be shifted 
to accommodate the new/missing element. A special case if the position is added/ removed at the end of the array.
- In some languages where the array size is fixed, it cannot change its size after initialization. If the total number
elements exceed the size of array, a new array has to be allocated and the existing elements have to be copied over. The
act of creating a new array and transferring elements to a new array takes O(n) time.

#### 1.1.2 Common terms
Common terms when you deals with problems involving arrays:
- Subarray: A range of contiguous values within an array. An example is that given an array [2, 3, 4, 1, 5, 6], 
[3, 4, 1] is a subarray while [3, 4, 6] is not a subarray.
- Subsequence: A sequence that can be derived from the given sequence by deleting some or no elements without changing 
the order of the remaining elements. Take an example: given an array [2, 3, 4, 1, 5, 6]. We can see [3, 4, 5] is a
subsequence but [3, 2, 1] is not a subsequence.

#### 1.1.3 Time complexity
- Access: O(1)
- Search: O(n) -- Search (sorted array): O(log(n))
- Insert: O(n) -- Insert(at the end): O(1)
- Remove: O(n) -- Remove (at the end): O(1)


### 1.2 String

#### 1.2.1 Introduction

A string is a sequence of characters. 

Common data structures for looking up strings:
- Trie/Prefix Tree
- Suffix Tree

Common string algorithms:
- Rabin Karp for efficient searching of substring using a rolling hash
- KMP for efficient searching of substring

#### 1.2.2 Time Complexity
It is quite similar array operations:
- Access: O(1)
- Search: O(n)
- Insert: O(n)
- Remove: O(n)

##### Operations involving another string
We assume the another string is of length m.
- Find substring: O(n.m). This is the most naive case. There are more efficient algorithms for string searching such as 
the KMP algorithm.
- Concatenating strings: O(n + m)
- Slice: O(m)
- Split (by token): O(n + m)
- Strip (remove whitespaces): O(n)

#### Techniques
Many string questions fall into one of these points:

##### Counting characters
We will need to count the frequency of characters in a string. The most common way of doing that is by using a hash 
table/ map in our language. 

If you need to keep a counter of characters, a common mistake is to say that the space complexity required for the 
counter is O(n). The space required for a counter of a string of latin characters is O(1) not O(n). This is because the
upper bound is the range of characters, which is usually a fixed constant of 26. The input set is just lowercase Latin
characters.

##### String of unique characters



## 2. Data Structures
