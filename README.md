# DSA-Semester-Project-706-725
Task Scheduler
Data Structures and Algorithms
Semester Project_ Deliverable 1
Syeda Samreen Fatima 2023706
M. Talha Sheraz 2023725

1.	Project Title: Task Scheduler
A system which manages your tasks based on criteria set by the user themselves, such as deadline, completion time, priority. Program ascertains individuals’ schedules remain free of hassle, confusion and are custom built for ease. It suggests order for tasks specified by user to ensure they reach completion smoothly.

2.	Essential Specifications: 
•	Add task
•	Remove task
•	Set deadline
•	Set priority
•	Concurrency support 
•	Set completion time
•	Mark as complete

3.	Data Structures Selection:
•	Queue: Elements will be ordered by priority determined by user. User will be able to add(insert), remove(pop) and view tasks specified. In C++, ‘priority queue’ class is available in Queue library.
•	Linked List: List of specified tasks will have dynamic memory allocation. Data will be stored as node, which the user will be able to insert, delete, or even access each node (in specified sequence).
•	Concurrency/multi-tasking: Multiple are to be executed in parallel each with its own memory space. C++ library consists of <thread> which allows to create and manage threads. 
How the both of these work together: The priority queue will be used to schedule tasks (highest priority task first), while the circular linked list will store the tasks in a dynamic manner- allowing for easy insertion and deletion.

4.	Algorithmic Approach and Time Complexities:
   
•	Queue: 
a)	Insertion adds a new task to the designed scheduled. Time Complexity = O (log n)
b)	Removal algorithm removes specified tasks from schedule. Time Complexity=O(logn)
c)	View retrieves specified task. Time Complexity = O (log n)
d)	Concurrency support runs multiple time in parallel at the same time. Time Complexity = O (log n) due to priority queue.

•	Linked List:
a)	Insert creates new node at specified position. Time Complexity = O (n)
b)	Delete removes specified tasks, updating all other positions. Time Complexity = O (n) 


5.	Input and Output Design:

INPUT	                          OUTPUT
Add task	                      Confirmation message
Remove task	                    Confirmation message
Display tasks	                  List of schedules and timeline
Invalid input	                  Error message


