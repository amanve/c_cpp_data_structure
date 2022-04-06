# Data Structure

1. List as Abstract Data Type
   - store a given number of elements of a given data-type
   - write/modify element at a position
   - read element at a position
   - Arrays - int i[10]; i[2]=5; print i[2];

   - empty list has size 0
   - insert
   - remove
   - count
   - read/modify
   - data type specification

   - int A[MAXSIZE];
   - int end = -1;
   - insert(2) //insert at index
   - insert(4)
   - insert(5) ...
   - remove(0)
   - remove(3)

   - when array is full, create a new larger array, copy previous array into the new array
   - free the memory for the previous array
   - NOT RECOMMENDED - costly

   - 1. Access - Read / write element at an index - constant time - O(1)
   - 2. Insert - T ∝ n; n O(n)
   - 3. Remove - O(n)
   - 4. Add - O(n)

2. Linked List
