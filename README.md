<!-- Header -->
<h1>Hi, I'm Adam!</h1>


<!-- Brief Introduction -->
<p>I am enrolled at the University of Wisconsin-Parkside, pursuing a Bachelor's of Science in Computer Science. It is my goal to one day work as a software engineer. I am proficient with Java, C++, Python, and Linux OS / Shell Scripting, and basic skills in of C, C#, React, and GoLang.</p>


<!-- Table of Contents -->
<table>
  <tr><th>Table of Contents</th></tr>
  <tr><td><a href="#EducationLink">Education</a></td></tr>
  <tr><td><a href="#CertificationLink">Certifications</a>
    <i>(2 completed, 2 working)</i></td></tr>
  <tr><td><a href="#LinkedInLearningLink">LinkedIn Learning Courses</a>
    <i>(11 courses completed)</i></td></tr>
  <tr><td><a href="#JavaLink">Java Program Portfolio</a>
    <i>(12 projects)</i></td></tr>
  <tr><td><a href="#C++Link">C++ Program Portfolio</a>
    <i>(3 projects)</i></td></tr>
  <tr><td><a href="#PythonLink">Python Script Portfolio</a>
    <i>(12 projects)</i></td></tr>
  <tr><td><a href="#LinuxLink">Linux Shell Script / OS Projects Portfolio</a></td></tr>
  <tr><td><a href="#ConnectLink">Connect With Me</a></td></tr>
</table>
<br>


<!-- Eduction Overview -->
<a id="EducationLink"><h2>🎓 Education:</h2></a>
<h3>University of Wisconsin-Parkside<i>, Kenosha, WI</i></h3>

- B.S., Computer Science (GPA: 3.5)
- Certificates:
    - [UNIX System Administration certificate](https://www.uwp.edu/learn/programs/unixsystemadmin.cfm) | Issued: May 17, 2023
    - [Cyber Security certificate](https://www.uwp.edu/learn/programs/cybersecurity.cfm) | Issued: TBD

<br>


<!-- List of Certifications -->
<a id="CertificationLink"><h2>📜 Certifications:</h2></a>

<h3>Python Institute</h3>

- [PCAP - Certified Associate in Python Programming (Version: PCAP-31-03)](https://pythoninstitute.org/pcep) | Issued: TBD
- [PCEP - Certified Entry-Level Python Programmer (Version: PCEP-30-02)](https://verify.openedg.org/?id=07wC.sTLQ.26eO) | Issued: April 23, 2023

<br>


<!-- LinkedIn Learning Courses -->
<a id="LinkedInLearningLink"><h2>⛓ LinkedIn Learning</h2></a>
- General Knowledge
  - [Agile Foundations](https://www.linkedin.com/learning/certificates/2c4cb999c2b1df9079a5eecca6c521217724936d8b6f1b0667ec3047b496ef74) | Completed: April 21, 2023
  - [Software Design: Modeling with UML](https://www.linkedin.com/learning/certificates/a2024c721bbe2943bb2f43f7d607d363897d2c808608cb35c0d454212a456e5e) | Completed: April 16, 2023
  - [Git Essential Training: The Basics](https://www.linkedin.com/learning/certificates/e0d2fe399ca9084cb7bb979d609108af409cb0f56a484049b2d675e4b342eb68) | Completed: February 18, 2023
- Java
  - [Java: Testing with JUnit](https://www.linkedin.com/learning/certificates/4e9dd22d6d0a0ad8196914514e159292d03f98776a6940bce9e6932096eff7ff?trk=share_certificate) | Completed: February 12, 2023
- C++
  - [Getting Started with C++ (Learning Path)](https://www.linkedin.com/learning/certificates/b2c678f7155c1fbea1dd7ae48d0719e7e68a79d060c00492fb055c380ae77c89) | Completed: February 26, 2023
    - Learning C++
    - C++ Templates and the STL
    - Introducing Functional Programming in C++
    - C++ Best Practices for Developers
    - Code Clinic: C++
    - Web Servers and APIs using C++
    - Nail Your C++ Interview

<br>


<!-- Project Portfolio -->
<h2>👨‍💻 Project Portfolio</h2>

<!-- Java Programs -->
<a id="JavaLink"><h2>Java Programs</h2></a>
<h3>University of Wisconsin-Parkside Projects</h3>

<!-- Data Structures and Algorithm Design projects -->
<h4>Course: Data Structures and Algorithm Design</h4>
<table>
  <tr>
    <th>Project</th>
    <th>Brief Description</th>
    <th>Concepts</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_2DSearchTree">2D Search Tree</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      TwoDTree is a data structure used for storing 2D points that allows<br>
      for efficient range search queries. The tree is built by recursively<br>
      partitioning the plane into smaller rectangles, and each node<br>
      compares points by x or y value depending on the level of the tree.<br>
      Searches for points within a given range are done by recursively<br>
      traversing the tree and only exploring subtrees that might contain<br>
      points in the range.
    </td>
    <td>
      <ul>
        <li>Design/implement 2D tree</li>
        <li>Traverse binary search tree</li>
        <li>Comparator</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_HeapMedian">Find Median of<br>Heap</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Uses two heaps to maintain the median of a stream of integers in<br>
      constant time. The max heap stores the smaller half of the data and<br>
      the min heap stores the larger half. The program inserts the next<br>
      element into the appropriate heap based on its value, and rebalances<br>
      the heaps as necessary to maintain the constraints. The getMedian<br>
      method returns the median of all the data inserted. If the number of<br>
      elements is even, it returns the average of the max from the max heap<br>
      and the min from the min heap. If the number of elements is odd, it<br>
      returns the max from the max heap.
    </td>
    <td>
      <ul>
        <li>Priority queues</li>
        <li>Heaps</li>
        <li>Comparator</li>
        <li>Rebalancing</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_FindMedianUnsortedArray">Find Median of<br>Unsorted Array<br><i>(optimized)</i></a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      The code defines a class called FindMedian that optimizes the search<br>
      of the median element of an unsorted array. The driver class,<br>
      FindMedianTest generates random integer arrays of increasing sizes<br>
      and prints their median and time taken to search the array.
    </td>
    <td>
      <ul>
        <li>Algorithm design</li>
        <li>Recursion</li>
        <li>Array manipulation</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_GenericReverseOrderSorter">Generic Sorter</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      The code defines a generic class called MyIterable that implements<br>
      Iterable interface to iterate over a sorted list of elements. The<br>
      driver class, MyIterableTester, reads input from a file and prints<br>
      sorted arrays of Strings, Integers, and Doubles using the MyIterable<br>
      class.
    </td>
    <td>
      <ul>
        <li>Generic programming</li>
        <li>Implementing interfaces</li>
        <li>Exception handling</li>
        <li>Lists and Collections</li>
      </ul>
    </td>
  </tr>
</table>


<!-- Computer Science 2 projects -->
<h4>Course: Computer Science 2</h4>
<table>
  <tr>
    <th>Project</th>
    <th>Brief Description</th>
    <th>Concepts</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_Synonyms">Synonyms</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      The Synonyms class finds synonyms for a given word by analyzing the<br>
      frequency of occurrences of each word in a corpus of text files using<br>
      cosine similarity between frequency vectors. It stores the descriptor<br>
      vectors for each word in a HashMap and calculates the cosine<br>
      similarity between two words using their respective frequency maps.
    </td>
    <td>
      <ul>
        <li>Nested HashMaps</li>
        <li>Retrieve data from URLs</li>
        <li>Exception handling</li>
        <li>Calculate cosine similarity</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_Recursion">Recursion</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      This program demonstrates the programmer's knowledge of recursion<br>
      with 5 unique recursive methods. The program includes test cases for<br>
      each method, except for the trickyHanoi() method which is<br>
      user-dependent.
    </td>
    <td>
      <ul>
        <li>Recursion</li>
        <li>Unit testing</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_ReaderWriter">Read and Write</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Uses scanner to read text from a source, and< PrintScanner to write<br>
      text to a file.
    </td>
    <td>
      <ul>
        <li>Retrieve data from text file</li>
        <li>Write data to text file</li>
        <li>Exception handling</li>
      </ul>
    </td>
  </tr>
</table>

<!-- Computer Science 1 projects -->
<h4>Course: Computer Science 1</h4>
<table>
  <tr>
    <th>Project</th>
    <th>Brief Description</th>
    <th>Concepts</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_TimeClock">TimeClock</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      The TimeClock class tracks time in hours, minutes, and seconds with<br>
      methods for object creation, comparison, and formatted output.<br>
      Validated user inputs.
    </td>
    <td>
      <ul>
        <li>Object-oriented programming</li>
        <li>Instance variables</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_2DArray">2D Array</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Java program manipulates a 2D array with methods for multiplication,<br>
      negating odd numbers, flattening, reversing, reshaping, and rotating.<br>
      User inputs num for multiplication.
    </td>
    <td>
      <ul>
        <li>2D Arrays</li>
        <li>Input/Formatted output</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_1DArray">1D Array</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      This class processes integer arrays: input custom/test array, find<br>
      lowest/second lowest values, build block array, eliminate duplicates.
    </td>
    <td>
      <ul>
        <li>Arrays</li>
        <li>Input/Formatted output</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_RockPaperScissors_HalloweenEdition">Rock-Paper-<br>Scissors<br>(Halloween<br>Edition)</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      This is a two-player game called the "Boulder, Scroll, Knife, Witch's<br>
      Brew, Monster Game". Each player will be given an element at random,<br>
      and the game will continue until the players decide to stop. The<br>
      summary of the games played will be printed at the end for each<br>
      player.
    </td>
    <td>
      <ul>
        <li>Iteration</li>
        <li>Switch statement</li>
        <li>Methods</li>
        <li>User input</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Java_ElectricBillCalculations">Electric Bill<br>Calculations</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      This Java program calculates the electric bill for a customer based<br>
      on user input of billing period and meter readings. It uses constants<br>
      to calculate different charges and prints the results in a formatted<br>
      manner.
    </td>
    <td>
      <ul>
        <li>Input/Output</li>
        <li>Control structures</li>
        <li>String formatting</li>
      </ul>
    </td>
  </tr>
</table>
<br>


<!-- C++ Programs -->
<a id="C++Link"><h2>C++ Programs</h2></a>
<h3>University of Wisconsin-Parkside Projects</h3>

<!-- Programming Languages -->
<h4>Course: Programming Languages</h4>
<table>
  <tr>
    <th>Project</th>
    <th>Brief Description</th>
    <th>Concepts</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/CPP_CarbonFootprint">Carbon<br>Footprint</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      This C++ program defines three classes: Car, Building, and Bicycle<br>
      that inherit from an abstract class CarbonFootprint, which calculates<br>
      and prints an object's carbon footprint. The main function creates<br>
      objects of each class and calls the getCarbonFootprint method.
    </td>
    <td>
      <ul>
        <li>Interfaces</li>
        <li>Abstract classes</li>
        <li>Virtual functions</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/CPP_BankAccount">Bank Account</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      This C++ project contains three classes that define different types<br>
      of bank accounts: <b>'Account'</b>, <b>'SavingsAccount'</b>, and <b>'CheckingAccount'</b>.<br>
      It includes methods for crediting and debiting accounts, calculating<br>
      interest, and applying transaction fees. The main function<br>
      demonstrates the usage of these classes by creating and manipulating<br>
      instances of each.
    </td>
    <td>
      <ul>
        <li>Inheritance / polymorphism</li>
        <li>Encapsulation</li>
        <li>Virtual classes</li>
        <li>Memory management<br>(using destructor)</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/CPP_RationalNumbers">Rational<br>Numbers</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      This project defines a RationalNumber class with basic arithmetic<br>
      operators (+, -, *, /) and comparison operators (==, !=), and a<br>
      toString method. It also includes a main function to test the<br>
      implementation.
    </td>
    <td>
      <ul>
        <li>Operator overloading</li>
        <li>Header file (.h)</li>
        <li>String manipulation</li>
      </ul>
    </td>
  </tr>
</table>
<br>

  
<!-- Python Programs -->
<a id="PythonLink"><h2>Python Scripts</h2></a>
<h3>University of Wisconsin-Parkside Projects</h3>

<!-- Programming Languages -->
<h4>Course: Programming Languages</h4>
<table>
  <tr>
    <th>Project</th>
    <th>Brief Description</th>
    <th>Concepts</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_CardClass">Card Class</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Creates a Card object with a rank and suit, provides methods to get<br>
      rank, suit, and blackjack value. It can also return a string<br>
      representation of itself.
    </td>
    <td>
      <ul>
        <li>Object-Oriented Programming</li>
        <li>Dictionaries as switch statments</li>
        <li>String formatting</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_SyracuseSequence">Syracuse<br>Sequence</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Computes and prints the Syracuse sequence for a given starting value,<br>
      following the rules of the Syracuse function, and stores it in an<br>
      array.
    </td>
    <td>
      <ul>
        <li>Arrays</li>
        <li>Loops</li>
        <li>Input / Output</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_BodyMassIndex">Body Mass<br>Index<br>Calculator</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Calculates the body mass index based on the user's weight and height<br>
      in pounds and inches. It then outputs a message reflecting whether<br>
      the BMI is above, within, or below the healthy range. 
    </td>
    <td>
      <ul>
        <li>Control Structures</li>
        <li>Data type conversion</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_AcronymBuilder">Acronym<br>Builder</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Converts a user-entered phrase into an acronym.
    </td>
    <td>
      <ul>
        <li>String manipulation</li>
        <li>Loops</li>
        <li>Input / Output</li>
      </ul>
    </td>
  </tr>
</table>

<!-- Course: Introduction to Programming -->
<h4>Course: Introduction to Programming</h4>
<table>
  <tr>
    <th>Project</th>
    <th>Breif Description</th>
    <th>Concepts</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_CupcakeCoffeeOrdering">Cupcake and<br>Coffee<br>Ordering<br>System</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Serves as a simple ordering system for a cupcake shop. The program<br>
      calculates the total cost of the order, andprints ASCII art images of<br>
      the amount of coffee cups and cupcakes ordered.
    </td>
    <td>
      <ul>
        <li>Functions</li>
        <li>Control structures</li>
        <li>Input / output</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_VolumeConverter">Volume<br>Converter</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Converts volume measurements in ounces to gallons and ounces and<br>
      prints the result with appropriate pluralization and formatting.
    </td>
    <td>
      <ul>
        <li>Conditional statements</li>
        <li>Iteration</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_WordAnalyzer">Word<br>Analyzer</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Prompts the user for inputs, manipulates strings, and prints results.<br>
      It performs string slicing, counting, splitting, and replacing<br>
      operations.
    </td>
    <td>
      <ul>
        <li>String manipulations</li>
        <li>List manipulation</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_InteractiveDrawing">Interactive<br>Drawing</a> 
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Generate a square with random colored stripes of a user-defined<br>
      center-location, size, and number of stripes in a graphical window.
    </td>
    <td>
      <ul>
        <li>GUI Programming</li>
        <li>Text fields</li>
        <li>Mouse events</li>
        <li>Itarative drawing</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_LoopDrawing">Loop<br>Drawing</a> 
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Draws 3 sets of graphics in a window using a loop: anchors,<br>
      airplanes, sailboats, and traffic lights. Then draws a user-defined<br>
      amount of circles, at mouse specified locations.
    </td>
    <td>
      <ul>
        <li>GUI Programming</li>
        <li>Graphical objects</li>
        <li>Coordinates</li>
        <li>Iteration</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_SimpleDrawing">Graphic<br>Drawing</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Using the graphics module, draws a picture of a movie theather sign<br>
      promoting their new debut, consisting of a large red rectangle with<br>
      yellow ovals representing lights, an area for text, and a popcorn<br>
      container.
    </td>
    <td>
      <ul>
        <li>Graphics library</li>
        <ul>
          <li>Shapes</li>
          <li>Colors</li>
        </ul>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_LoopPractice">Loop<br>Practice</a> 
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Demonstrates knowledge of iteration through four examples, including<br>
      printing text, looping through a list, taking user input, and<br>
      arithmetic operations in a loop.
    </td>
    <td>
      <ul>
        <li>Iteration</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AdamZieman/Python_AreaRug">Area Rug<br>Calculator</a>
    </td>
    <td>
<!--  123456789012345678901234567890123456789012345678901234567890123456789 -->
      Calculates the dimenstions and cost of an area rug for a given room<br>
      size and predefined cost per square foot.
    </td>
    <td>
      <ul>
        <li>Procedural Programming</li>
        <li>Input / output</li>
      </ul>
    </td>
  </tr>
</table>
<br>

<!-- Linux Project Portfolio -->
<a id="LinuxLink"><h2>Linux Shell Scripts / OS Projects</h2></a>
<h3>University of Wisconsin-Parkside Projects</h3>

<!-- UNIX System Administration -->
<h4>Course: UNIX System Administration</h4>
<table>
  <tr>
    <th>Project</th>
    <th>Brief Description</th>
    <th>Concepts</th>
  </tr>
  <tr>
    <td>
      Create Users
    </td>
    <td>
    </td>
    <td>
      <ul>
        <li></li>
      </ul>
    </td>
  </tr>
</table>

<!-- UNIX Scripting -->
<h4>Course: UNIX Scripting</h4>
<table>
  <tr>
    <th>Project</th>
    <th>Brief Description</th>
    <th>Concepts</th>
  </tr>
  <tr>
    <td></td>
    <td>
    </td>
    <td>
      <ul>
        <li></li>
      </ul>
    </td>
  </tr>
</table>

<br>

<!-- Important Links -->
<a id="ConnectLink"><h2>🤳 Connect with me:</h2></a>
[LinkedIn](https://www.linkedin.com/in/adam-zieman/)
