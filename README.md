# data-structures-and-algorithms
The list of data structures and algorithms

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


## 2. Data Structures
