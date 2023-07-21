<!-- Header -->
<h1>Hi, I'm Adam!</h1>


<!-- Brief Introduction -->
I'm enrolled at the University of Wisconsin-Parkside, pursuing a Bachelor's of Science in Computer Science, 'UNIX System Administration' certificate, and 'Cyber Security' certificate. Additionally, I have obtained the 'Certified Entry-Level Python Programmer' and woring towards the 'Certified Associates in Python Programming'. It is my goal to one day work as a software engineer! <br><br>


<!-- Table of Contents -->
<h3>Table of Contents:</h3>
<a href="#EducationLink">Education</a> <br>
<a href="#CertificationLink">Certifications</a> <br>
<a href="#JavaLink">Java Projects</a> <br>
<a href="#GoLink">Go Projects</a> <br><br>



<!-- Eduction Overview -->
<a id="EducationLink"><h2>🎓 Education:</h2></a>
<h3>University of Wisconsin-Parkside</h3>

- [Computer Science, B.S.](https://www.uwp.edu/learn/programs/computersciencemajor.cfm) | Graduation: December 2024
  - Cumulative GPA: 3.5
  - Honors: Dean's List
- Certificates:
    - [UNIX System Administration certificate](https://www.uwp.edu/learn/programs/unixsystemadmin.cfm) | Issued: May 17, 2023
    - [Cyber Security certificate](https://www.uwp.edu/learn/programs/cybersecurity.cfm) | Issued: December 20, 2023

<br>



<!-- List of Certifications -->
<a id="CertificationLink"><h2>📜 Certifications:</h2></a>

<h3>Python Institute</h3>

- [PCAP - Certified Associate in Python Programming (Version: PCAP-31-03)](https://pythoninstitute.org/pcep) | Issued: May 23, 2023
- [PCEP - Certified Entry-Level Python Programmer (Version: PCEP-30-02)](https://verify.openedg.org/?id=07wC.sTLQ.26eO) | Issued: April 23, 2023
- Certified Scrum Developer | Issued: July 18, 2023

<br>



<!-- Project Portfolio -->
<h2>👨‍💻 Project Portfolio</h2>



<!-- Java Project Portfolio -->
<a id="JavaLink"><h2>Java Projects</h2></a>

<h3><a href="https://github.com/AdamZieman/Java_WordLadder">Graph-based Word Ladder</a></h3>

Finds the shortest path between two words by changing one letter at a time. It reads a dictionary of words from a file and creates a graph where each node represents a word, and edges connect words that differ by one letter. <br><br>

<h3><a href="https://github.com/AdamZieman/Java_Synonym_Comparison_Tool">Synonym Comparison Tool</a></h3>

Utilizes natural language processing techniques to find the closest synonym for a given word based on a list of word choices. To achieve this, the program uses the cosine similarity between frequency vectors for the words to determine the synonym. <br><br>

<h3><a href="https://github.com/AdamZieman/Java_DesignImplementation2DCoordinateBST">Design and Implementation: 2-D BST of Coordinates</a></h3>

A data structure that enables the storage and search of points in two-dimensional space. It is implemeneted as a binary tree, where the nodes are partitioned based on their coordinates. The partitioning is done based on a comparator that alternates between comparing the x- and y-coordinates of the points on each level. <br><br>

<h3><a href="https://github.com/AdamZieman/Java_HeapMedian">Find Median of Heap</a></h3>

Uses two heaps to maintain the median of a stream of integers in constant time. The max heap stores the smaller half of the data and the min heap stores the larger half. The program inserts the next element into the appropriate heap based on its value, and rebalances the heaps as necessary to maintain the constraints. The getMedian method returns the median of all the data inserted. If the number of elements is even, it returns the average of the max from the max heap and the min from the min heap. If the number of elements is odd, it returns the max from the max heap. <br><br>

<h3><a href="https://github.com/AdamZieman/Java_FindMedianUnsortedArray">Find Median of Unsorted Array <i>(optimized)</i></a></h3>

Optimizes the search of the median element of an unsorted array. The driver class, generates random integer arrays of increasing sizes and finding their median and the time taken to search the array. <br><br>




<!-- Go Project Portfolio -->
<a id="GoLink"><h2>Go Projects</h2></a>

<h3><a href="https://github.com/AdamZieman/Go_CLI_ToDo_List_Manager">CLI To-Do List Manager</a></h3>

From the command line, a user can manage a todo list by adding a task, deleteing a task, or clearing all tasks. The task list is stored in the program as a slice, and on the system in the file "tasks.txt". User input is read using bufio and manipulates the task list using a switch statement. The Task type is a struct with an ID and name. The program outputs the current task list and available commands to the user.
