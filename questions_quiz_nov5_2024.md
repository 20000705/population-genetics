# Query

Generate 80 questions on data containers: vectors, deques, binary trees, adaptors (stacks, queues), set, maps, unordered containers, asymptotic complexity. Feel free to add code to these questions (delineated by 
cpp ...
). I am only interested in the questions for training purposes. 

## Reply

Certainly! Here are 80 questions focused on data containers in C++, covering vectors, deques, binary trees, adaptors, sets, maps, unordered containers, and asymptotic complexity.

---

### Vector
1. What are the main characteristics of `std::vector` in terms of memory allocation and element access?
2. How does `std::vector` handle resizing when it reaches its capacity?
3. Write a code snippet to initialize a vector with integers 1 to 5.
   ```cpp
   std::vector<int> vec = {1, 2, 3, 4, 5};
   ```
4. How can you add an element to the end of a vector? Show an example.
5. What is the time complexity of accessing an element by index in a `std::vector`?
6. Explain the difference between `push_back()` and `emplace_back()` in vectors.
7. Write a code snippet that removes all even numbers from a vector.
8. How can you get the current capacity of a vector?
9. Describe the difference between `size()` and `capacity()` in a vector.
10. When would a `std::vector` reallocation occur? What implications does it have on performance?

### Deque
11. What are the main characteristics of `std::deque` and how does it differ from `std::vector`?
12. How can you add elements to both the front and back of a `std::deque`? Show examples.
13. Write code to initialize a deque with integers 1 to 5.
   ```cpp
   std::deque<int> dq = {1, 2, 3, 4, 5};
   ```
14. What is the time complexity of inserting at the beginning of a `std::deque`?
15. How would you access the third element in a `std::deque`?
16. Explain when a `std::deque` might be preferred over a `std::vector`.
17. How would you remove elements from both ends of a deque?
18. Write a code snippet that clears all elements from a `std::deque`.
19. What happens if you try to access an element outside the bounds of a `std::deque` using `at()`?
20. Describe the underlying storage structure of `std::deque`.

### Binary Tree (Custom Implementation)
21. Write a class template for a simple binary tree node that stores an integer.
22. How would you implement an in-order traversal in a binary tree? Write a sample function.
23. What is the difference between a binary search tree and a general binary tree?
24. Write a recursive function to insert a value into a binary search tree.
25. What is the time complexity of searching for an element in a balanced binary search tree?
26. Explain how you would delete a node in a binary search tree.
27. Describe the three types of depth-first traversal in binary trees.
28. Write code for a pre-order traversal of a binary tree.
29. What are the advantages and disadvantages of using a binary search tree?
30. How does a balanced binary tree improve search efficiency?

### Stack (Adaptor)
31. How can you implement a stack in C++ using `std::stack`?
32. Show how to push and pop elements in a `std::stack` with integers.
33. What happens when you try to pop an element from an empty stack?
34. Write a code snippet to check if a stack is empty.
35. Describe a scenario where using a stack is more appropriate than a queue.
36. What is the time complexity of `top()` in `std::stack`?
37. How can you initialize a stack with elements from a `std::deque`?
38. Explain the LIFO property of a stack with an example.
39. Write a function that uses a stack to reverse a string.
40. Describe the internal container used in `std::stack` and how it affects performance.

### Queue (Adaptor)
41. How can you implement a queue in C++ using `std::queue`?
42. Show how to enqueue and dequeue elements in a `std::queue`.
43. What is the time complexity of `front()` in `std::queue`?
44. Write a code snippet to check if a queue is empty.
45. Describe the FIFO property of a queue with an example.
46. What underlying containers can be used in `std::queue`?
47. Explain a real-world scenario where a queue would be the preferred container.
48. Write code to simulate a basic queue operation using `std::queue`.
49. How does the `std::priority_queue` differ from `std::queue`?
50. What would you use to implement a double-ended queue that supports both stack and queue operations?

### Set
51. What is the difference between `std::set` and `std::unordered_set`?
52. Write a code snippet to insert and erase elements in a `std::set`.
53. Explain why elements in a `std::set` are unique.
54. What is the time complexity of finding an element in a `std::set`?
55. How does `std::multiset` differ from `std::set`?
56. Write code to find the lower bound of a value in a `std::set`.
57. Describe a situation where `std::set` is more useful than `std::vector`.
58. What would happen if you try to insert a duplicate value in a `std::set`?
59. Write a function to merge two `std::set` containers.
60. How does `std::set` maintain order among its elements?

### Map
61. What are the main characteristics of `std::map`?
62. Write a code snippet to insert key-value pairs into a `std::map`.
63. How would you iterate over a `std::map` to print all key-value pairs?
64. Explain the difference between `std::map` and `std::unordered_map`.
65. How does `std::multimap` differ from `std::map`?
66. Write code to find an element by key in a `std::map`.
67. What is the time complexity of inserting a key-value pair in `std::map`?
68. Explain how `std::map` ensures that keys are unique.
69. How would you retrieve the value associated with a key in `std::map`?
70. Describe a use case where `std::map` is preferable to `std::unordered_map`.

### Unordered Containers
71. What are unordered containers in C++?
72. List and describe the unordered associative containers available in C++.
73. Explain how `std::unordered_set` is implemented internally.
74. Write code to insert elements into an `std::unordered_set`.
75. What is the average time complexity for finding an element in `std::unordered_map`?
76. How does `std::unordered_map` handle hash collisions?
77. Why would you choose an unordered container over an ordered one?
78. What is the primary drawback of using an unordered container?
79. Write code to demonstrate the use of `std::unordered_map` with custom hash function.
80. Describe the importance of hashing in unordered containers.

--- 

These questions provide a well-rounded understanding of various data containers and complexities in C++, along with practical coding exercises.
