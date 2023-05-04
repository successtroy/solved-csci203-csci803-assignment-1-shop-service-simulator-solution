Download Link: https://assignmentchef.com/product/solved-csci203-csci803-assignment-1-shop-service-simulator-solution
<br>
You must write a program which models the operation of a shop using Discrete Event simulation:

The shop has several servers, each of which has a different level of efficiency. This is measured by a time multiplier <em>e<sub>i </sub></em>which differs for each server <em>s<sub>i</sub></em> and works as follows:

If server <em>i</em> with efficiency <em>e<sub>i</sub></em> serves customer <em>j</em> with service time <em>t<sub>j</sub></em> the actual time taken to serve the customer is:  <em>e<sub>i </sub></em>x <em>t<sub>j</sub></em>.

For example, if server 5 has an efficiency of 1.2 and customer 7 has a service time of 5.0 then server 5 takes a time of 6.0 to serve customer 7.

<strong>The input file contains the following information. </strong>

<ol>

 <li>The number of servers. You may assume a maximum of 20 servers.</li>

 <li>For each server: the efficiency of the server.</li>

 <li>Arrival records consisting of the arrival time and service time of each customer.</li>

</ol>

<strong>Your program should: </strong>

<ol>

 <li>Read the name of the text file from the console.</li>

 <li>Read the information related to each server.</li>

 <li>Read and process the customer arrival data.</li>

</ol>

<strong>Note: </strong>

<ol>

 <li>There is a single queue of customers.</li>

 <li>Each customer will be served by the server with the best available efficiency (the smallest value) from the available idle servers.</li>

 <li>The servers are all initially idle.</li>

 <li>Customers must be served in the order in which they arrive.</li>

 <li>You should not attempt to read in all the arrival data at the start of the simulation.</li>

</ol>

At the end of the simulation, when the last customer in the file has been served, your program should print out the following information:

<ol>

 <li>The number of customers served.</li>

 <li>The time at which the last customer completed service.</li>

 <li>The greatest length reached by the queue.</li>

 <li>The average length of the queue.</li>

 <li>The average time spent by a customer in the queue. (If a customer is served immediately, their queue time is 0.0).</li>

 <li>For each server:

  <ol>

   <li>The number of customers they served</li>

   <li>The time they spent idle.</li>

  </ol></li>

</ol>

You must choose appropriate data structures and algorithms to accomplish this task.

Note: A sample input file “test.txt” is provided for you to test your program. A larger text file may be used for final assessment.

<strong>You must submit two files: </strong>

<ol>

 <li>Your program source file ass2.<em>ext</em> where .ext will be one of .c, .cpp, .java and .py</li>

 <li>A report in file report2.pdf containing an explanation of the data structures and algorithms you have used and your reasons for using them.</li>

</ol>

<strong>submit -u <em>user </em>-c CSCI203 -a 2 ass2.<em>ext </em>ass2.pdf</strong>

where: <em>user</em> your unix userid and <em>ext</em> is the appropriate extension of your program.

Note:             All programs submitted must compile and run on banshee. The following commands will be used to test your program.

C              gcc ass2.c -o ass2

ass2

C++        g++ ass2.cpp -o ass2 ass2

Java       javac ass2.java java ass2

Python python ass2.py

It is your responsibility to ensure that your program compiles and runs correctly.


