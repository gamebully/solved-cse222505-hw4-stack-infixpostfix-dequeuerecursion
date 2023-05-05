Download Link: https://assignmentchef.com/product/solved-cse222_505-hw4-stack-infixpostfix-dequeuerecursion
<br>
<strong>Q1:</strong>

Convert the infix expressions given below to prefix and postfix, then evaluate them. Show your work step by step.

<ol>

 <li>i) A + (( B – C * D ) / E ) + F – G / H ii) ! ( A &amp;&amp; ! (( B &lt; C ) || ( C &gt; D ))) || ( C &lt; E )</li>

</ol>

Write your solution by latex or word and upload it as a <em>StudentNumber.pdf</em> file.

Note: Before evaluation, you must assign values to variables.

<strong>Q2:</strong>

Implement a Deque class which implements Deque interface and can extend AbstractCollection.

Deque is a queue that supports adding or removing items from both ends of the data structure. To implement it, your class should keep two linked list. One for the elements in the deque and the other to keep the nodes removed. You should use a removed node, if any available, when a new node is needed instead of creating a new node. With this type of operation you can save time for constructing new nodes and garbage collection the nodes that are not used anymore.

You are not allowed to use any class in Collection hierarchy as a member. So, you need to define your own Node class to build a linked list. Note that you need to implement all required methods and Iterator class.

Write a Main class to test each method in your class.

<strong>Q3: Recursive functions</strong>

Define each of the following problem recursively:

<ul>

 <li>Identify the base case (or base cases) that stops the recursion</li>

 <li>Define the smaller problem (or problems)</li>

 <li>Explain how to combine solutions of smaller problems to get the solution of original problem</li>

</ul>

Write recursive methods for the problems.

<ol>

 <li>Reversing a string. For example, if the input is “this function writes the sentence in reverse”, then the output should be “reverse in sentence the writes function this”.</li>

 <li>Determining whether a word is elfish or not. A word is considered elfish if it contains the letters: e, l, and f in it, in any order. For example, whiteleaf, tasteful, unfriendly, and waffles are some elfish words.</li>

 <li>Sorting an array of elements using selection sort algorithm.</li>

 <li>Evaluating a Prefix expression</li>

 <li>Evaluating a Postfix expression</li>

 <li>Printing the elements of an array on the screen as in the example below.</li>

</ol>

Input:

<table width="93">

 <tbody>

  <tr>

   <td width="26">1</td>

   <td width="26">2</td>

   <td width="26">3</td>

   <td width="15">4</td>

  </tr>

  <tr>

   <td width="26">5</td>

   <td width="26">6</td>

   <td width="26">7</td>

   <td width="15">8</td>

  </tr>

  <tr>

   <td width="26">9</td>

   <td width="26">10</td>

   <td width="26">11</td>

   <td width="15">12</td>

  </tr>

  <tr>

   <td width="26">13</td>

   <td width="26">14</td>

   <td width="26">15</td>

   <td width="15">16</td>

  </tr>

  <tr>

   <td width="26">17</td>

   <td width="26">18</td>

   <td width="26">19</td>

   <td width="15">20</td>

  </tr>

 </tbody>

</table>

Output:  1 2 3 4 8 12 16 20 19 18 17 13 9 5 6 7 11 15 14 10

<strong>RESTRICTIONS:</strong>

<ul>

 <li>Use only specified data types</li>

 <li>Can be only one main class in each question</li>

 <li>Don’t use any other third part library</li>

</ul>

<strong>GENERAL RULES:</strong>

<ul>

 <li>For any question firstly use course news forum in Moodle, and then the contact TA.</li>

 <li>You can submit assignment one day late and will be evaluated over twenty percent (%40).</li>

</ul>

<strong>TECHNICAL RULES:</strong>

<ul>

 <li>Use given CSE222-VM to develop and test your Homeworks (your code must be working on CSE222-VM), CSE222-VM download link will be given on Moodle.</li>

 <li>Implement <a href="https://www.google.com.tr/search?q=clean+code+standart&amp;oq=clean+code+standart&amp;aqs=chrome..69i57j0.3015j0j4&amp;sourceid=chrome&amp;es_sm=122&amp;ie=UTF-8">clean code standards</a> in your code; o Classes, methods and variables names must be meaningful and related with the functionality.</li>

</ul>

o Your functions and classes must be simple, general, reusable and focus on one topic. o Use standard <a href="https://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html">java code name conventions</a><a href="https://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html">.</a>

<strong>REPORT RULES:</strong>

<ul>

 <li>Add all <a href="http://www.oracle.com/technetwork/articles/java/index-137868.html">javadoc</a> documentations for classes, methods, variables …etc. All explanation must be meaningful and understandable.</li>

 <li>You should submit your homework code, Javadoc and report to Moodle in a</li>

</ul>

“studentid_hw3.tar.gz” file.

<ul>

 <li>Use the given homework format including selected parts from the table below:</li>

</ul>

<strong>GRADING :</strong>