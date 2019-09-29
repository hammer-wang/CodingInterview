# Introduction:
This is a study plan I complied when I was preparing for the coding interviews of Google and Facebook for interns. I only had less than 2 weeks to prepare for the Google interview, and 1 month to prepare for the Facebook interview. As an undergraduate, I studied optoelectronics. Though I took Introduction to Computer Science and C++ Programming in my freshman year,  I’ve never taken a rigorous data structure and algorithms before. So, this plan is friendly to beginner to intermediate level interviewees who want to crack the coding interview in a short amount of time. Please feel free to use this study plan to boost your own preparation for Python coding interview. If you find this plan helpful, please star this repo.

Disclaimer: I’m a machine learning PhD, and I code everyday for my research projects. So, this plan may not be suitable for complete beginners.

## Table of contents
- Goals
- Estimated time to prepare
- High-level strategies
- Steps of interview
- Everyday plan
- Highly Frequent Interview Topics:
- Data Structures and Algorithms in Python
- Knowledge Checklist
- Google Topics:
- Additional Resources

## I. Goal:
Before Google Interview:
- Read the python data structure and algorithms at least once
- Finish the top 100 favorite problems on LeetCode
- Finish Google top 50 problems on LeetCode
- Finish top 100 highly frequent questions on LeetCode
- Do at least 2 Google mock interviews on LeetCode before the actual interview

Before Facebook Interview:
- Finish Facebook top 50 problems on LeetCode
- Do the top 100 highly frequent questions at least twice
- Do at least 2 Facebook mock interview on Leetcode before the actual interview
- Read the python data structure and algorithms twice

## II. Estimated Time to Prepare (Sep 29th):
	Min/Max hrs before Google ([Oct 7th, Oct 11th] : 71hrs/99hr
	Hrs before Facebook (Oct 28th): ~160 hrs

## III. High-level Strategies:
- Schedule time to study and practice.
- Prioritize breadth over depth.
- Set aside time to review what you’ve practiced.
- Remember your goal: aim for confidently solving two questions while thinking aloud in 35 minutes.
- Practice coding the way you’ll code during your tech screen.
- Practice coding solutions to medium and hard problems in less than 15 mins each.
- Provide the most efficient solution and find and fix the bugs.
- Practice talking through the problem space and possible solutions before you dive in, talk through the decisions out loud as you code.

## IV. Steps of interview:
- Ask questions to classify the question
- Think out loud
- Speaking about time and space complexity
- Optimize the solution
- Test cases

## V. Everyday plan
I’m a PhD student in Machine Learning and I generally have to spend >60 hrs working on my research projects every week. I have to prepare for the Google interview within 10 days so I have to allocate a large chunk of time everyday before the interview. I made this plan considering the load of my research tasks. You can modify the plan based on your daily work and how far away is your interview.

### Starting date: Sep 28h
### Before Google interview (any day between Oct 7th - Oct 11th)
- Sleep 5-6 hrs everyday, make sure I have at least 16 hrs working and preparing
- Devote at least 7 hrs every day preparing (6:30-9am, 8pm-12:30am) on weekdays
- Devote at least 12 hrs preparing on weekends

### After Google interview, before Facebook interview (Oct 28th):
- Devote at least 3.5 hrs everyday preparing on weekdays (6:30-7:30am, 10pm-12:30am)
- Devote at least 6 hrs preparing on weekends (6:30-10:00 am, 10pm -12:30am)


### VI. Highly Frequent Interview Topics:
According to LeetCode, below are the most frequently asked topics, ranked in terms of the frequency from high to low.
- Array
- Dynamic programming
- Math
- String
- Tree
- Hash Table
- Depth-first search
- Binary search
- Greedy
- Two pointers
- Breadth-first search
- Stack
- Backtracking
- Design
- Graph
- Linked list
- Sort
- Bit manipulation
- Heap
- Union find
- Sliding window
- Divide and conquer
- Trie
- Recursion
- Segment tree
- Ordered map
- Queue
- Minimax
- Binary indexed tree
- random
- Topological sort
- Geometry
- Line sweep
- Rejection sampling
- Reservoir sampling
- Binary search tree
- memorization
- Rolling Hash
- Suffix array

## VII. Data Structures and Algorithms in Python
While preparing for the coding interview, I found that reading the book Data Structures and Algorithms in Python (DSAP) is immensely helpful. You can find the free pdf version with this link: https://doc.lagout.org/programmation/python/Data%20Structures%20and%20Algorithms%20in%20Python%20[Goodrich,%20Tamassia%20&%20Goldwasser%202013-03-18].pdf

Progress track:
- [] chapter 1. Python primer
- [] chapter 2. Object-oriented programming
- [] chapter 3. Algorithm analysis
- [] chapter 4. Recursion
- [] chapter 5. Array-based sequences
- [] chapter 6. Stacks, Queues, and Deques
- [] chapter 7. Linked Lists
- [] chapter 8. Trees
- [] chapter 9. Priority Queues
- [] chapter 10. Maps, Hash Tables, and Skip lists
- [] chapter 11. Search Trees
- [] chapter 12. Sorting and selection
- [] chapter 13. Text Processing
- [] chapter 14. Graph algorithms
- [] chapter 15. Memory management and B-trees

## VIII. Knowledge Checklist

### Data structures
- [] arrays and strings
- [] linked lists
- [] stacks and queues
- [] hash table: a data structure that maps keys to values for highly efficient lookup. Lookup time is normally O(1).
- [] Trees
- [] Trie
- [] Graphs BFS
- [] Graphs DFS
- [] Heaps (min heaps and max heaps), use array to implement, heapify
- [] priority queues
- [] red and black trees

### Dynamic programming
- []

### Backtracking
- []

### Search Algorithm
- [] linear search
- [] binary search
- [] jump search
- [] interpolation search
- [] exponential search
- [] sublist search
- [] fibonacci search

### Sorting algorithms
- [] quicksort
- [] merge sort
- [] heapsort (heap sort basically is just heapify and remove, iteratively)
- [] insertion sort
- [] counting sort
- [] radix-sort
- [] bubble sort
- [] selection sort
- [] shell sort
- [] introsort
- [] bucket sort
- [] topological sort

### NP-complete problems
- [] definition
- [] traveling salesman
- [] knapsack problem

### Other concepts:
- [] hash code function

## IX. Google Topics:
- Time and space complexity
- Arrays
- Binary search
- string
- Bit manipulation
- Two pointers
- Linked list
- Stacks and Queues
- Backtracking
- Hashing
- Heaps and Maps
- Tree
- Dynamic programming
- Greedy algorithm
- Graph data structure and algorithms
- Sorting: quicksort and merge sort (merge sort can be highly useful in situations where quicksort is impractical, heapsort, - insertion-sort, radix-sort)
- Most famous classes of NP-complete problems: traveling salesman and knapsack problem. What does NP-complete mean?
Trees, basic tree construction, traversal and manipulation algorithms, hash tables, stacks, arrays, linked lists, priority queues
Hash tables are the most important data structure known to mankind. (should be able to implement one with only arrays) Know the O()characteristics of the standard library implementation for hashtables and maps in the chosen language.
Trees: tree construction, traversal, manipulation, binary trees. N-ary trees, trie-trees. Balanced binary tree, red/black tree, splay tree or an AVL tree. Know how to implement them. BFS and DFS. Know the difference between inorder, poster, and preorder.
Min/Max heaps. Understand the application and O() characteristics. Probably won’t implement, but it’s important to know when it makes sense to use one.
- Graphs: three representations. Objects and pointers, matrix, adjacency list. Basic graph traversal algorithms, breadth-first and depth-first search. Know the computational complexity, tradeoffs and how to implement them in real code.
Recursion.
- Divide and conquer
- hashset/hashmap/hashtable/dictionary
- Operating systems: You should understand processes, threads, concurrency issues, locks, mutexes, semaphores, monitors and how they all work. Understand deadlock, livelock and how to avoid them. Know what resources a process needs and a thread needs. Understand how context switching works, how it's initiated by the operating system and underlying hardware. Know a little about scheduling. The world is rapidly moving towards multi-core, so know the fundamentals of "modern" concurrency constructs.
Math: Some interviewers ask basic discrete math questions. This is more prevalent at Google than at other companies because counting problems, probability problems and other Discrete Math 101 situations surrounds us. Spend some time before the interview refreshing your memory on (or teaching yourself) the essentials of elementary probability theory and combinatorics. You should be familiar with n-choose-k problems and their ilk – the more the better.
- Distributed systems and parallel programming
- How search works
- Scalable web architecture and distributed system

## X. Additional Resources
- LeetCode [Coding problem website]
- HackerRank [Coding problem website]
- Data Structures and Algorithms [Book]
- Cracking the Coding Interview [Book]

## XI. Daily Notes

### Template: Date (Day)
Morning:
- Study new concepts
- Practice 2-3 related coding problems on LeetCode

Afternoon:
- Study new concepts
- Practice 2-3 related coding problems on LeetCode

Evening:
- Review the concepts learned in the previous day
- Practice 1-2 coding problems related to the concepts learned in the previous day
- Review the concepts learned in the morning and afternoon on the same day
- Practice 2-3 coding problems related to the concepts learned on the same day

### 2019-09-28 (Saturday)
Morning:
- Study recursion
- Practice related coding problems

Afternoon:
- Study queues, stacks, and deque (Chapter 6, DSAP)
- Practice 2-3 related coding problems on LeetCode

Evening:
- Review the concepts learned in the previous day
- Practice 1-2 coding problems related to the concepts learned in the previous day
- Review the concepts learned in the morning and afternoon on the same day
- Practice 2-3 coding problems related to the concepts learned on the same day

### 2019-09-29 (Sunday)
Morning:
- Study singly-linked lists (Sec 7.1, DSAP), trees (chapter 8, DSAP), priority queues (Sec 9.1 - Sec 9.2, DSAP)
- Practice related coding problems

Afternoon:
- Study and Maps and Hash tables (Sec 10.1-10.2, DSAP), binary search tree (Sec 11.1, DSAP), balanced search tree (Sec 11.2, DSAP),
Practice 2-3 related coding problems on LeetCode

Evening:
- Study merge sort and quick-sort (Sec 12.1 - 12.3, DSAP)
- Practice 2-3 related coding problems on LeetCode
- Study data structures for graphs and graph traversals (Sec 14.1 - 14.3, DSAP)
- Practice 2-3 related coding problems on LeetCode
- Review stacks, queues, deques.


