Implementation of a generic vector that's supposed to store elements which contain two arrays of chars and 2 different sizes of ints. This is done using a header for each element which will contain information about the types of ints used and the size in bytes of the element. It includes operations for adding a new element at the end, adding it at a certain index, removing an element at a certain index, printing information about an element found at a certain index and printing the whole vector.

Types of ints that can be stored:

- type 1 = 2 int8_t
- type 2 = int16_t and int32_t
- type 3 = 2 int32_t

Usage:
- to append an element: insert type string1 int1 int2 string2
- to add at a certain index: insert_at index type string1 int1 int2 string2
- to remove an element found at a certain index: delete_at index
- to print an element found at a certain index: find index
- to print all elements: print
- stop the program: quit
