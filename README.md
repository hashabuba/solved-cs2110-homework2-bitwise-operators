Download Link: https://assignmentchef.com/product/solved-cs2110-homework2-bitwise-operators
<br>
<h1><a name="_Toc4566"></a>1           Objective</h1>

<ol>

 <li>To understand the bitwise operators</li>

 <li>To use bitwise operators to complete tasks</li>

 <li>To understand ASCII</li>

</ol>

<h1><a name="_Toc4567"></a>2           Instructions</h1>

<ol>

 <li>Make sure all 4 files are in the same folder:

  <ul>

   <li>java</li>

   <li>java</li>

   <li>java</li>

   <li>jar</li>

  </ul></li>

 <li>Open a terminal / command prompt and navigate to the folder that all the files are in.</li>

 <li>Run the following command to see your grade for java:</li>

</ol>

java -jar hw2checker.jar -g BitVector.java

<ol start="4">

 <li>It should show all the test cases you are failing and give a 0/45 score.</li>

 <li>Implement one of the functions in java and re-run step 3 until you get full credit for that part of BitVector.java.</li>

</ol>

Now complete all the other methods in each of the 3 files based on their comments. Run the verifier and autograder frequently to avoid errors and to make sure you are using only the allowed operations.

Note: We have included an Examples.java file which shows and explains examples of two methods similar to those used in your assignment, which may be useful if you get stuck or confused at any point.

<h1><a name="_Toc4568"></a>3           How to run the auto-grader &amp; verifier</h1>

<ol>

 <li>Make sure that the jar file is in the same folder as your Bases.java, BitVector.java, and Operations.java files.</li>

 <li>Navigate to this folder in your command line.</li>

 <li>Run the desired command (see below).</li>

</ol>

<h2><a name="_Toc4569"></a>3.1         Commands</h2>

Test all methods and verify that no banned operations are being used (all 3 files):

java -jar hw2checker.jar

<strong>Note: Your grade will be dependent on the output of the above command, as it will both test the output of your methods, and verify that you are not using banned operations. If you get stuck though, you can use some of the below commands to help you debug.</strong>

On Windows and Mac, you can also double click the hw2checker.jar in your file explorer to test and verify all 3 files. The results will be placed in a new file called gradeLog.txt. Any errors with compilation, infinite loops, or other runtime errors will be placed in a new file called errorLog.txt.

Test &amp; verify all methods in a single file (using Bases.java). Useful for when you just want to look at one file at a time. For example:

java -jar hw2checker.jar -g Bases.java

Test all methods in a single file without running verifier (using Bases.java). This means that this will only run the unit tests, and will not check for the use of banned operations. Useful for when you just want to try and get something that works. For example:

java -jar hw2checker.jar -t Bases.java

Verify all methods in a single file without running tests (using Bases.java for example):

java -jar hw2checker.jar -v Bases.java

Any combination of files can also be graded, tested, or verified at the same time. For instance, Bases and Operations can be graded simultaneously as follows:

java -jar hw2checker.jar -g Bases.java Operations.java

<h1><a name="_Toc4571"></a>5           Deliverables</h1>

Please upload the following 3 files the “Homework 02” assignment on Gradescope:

<ol>

 <li>java</li>

 <li>java</li>

 <li>java</li>

</ol>

<h2><a name="_Toc4573"></a>6.1         General Rules</h2>

<ol>

 <li>Starting with the assembly homeworks, any code you write must be meaningfully commented. You should comment your code in terms of the algorithm you are implementing; we all know what each line of code does.</li>

 <li>Although you may ask TAs for clarification, you are ultimately responsible for what you submit. This means that (in the case of demos) you should come prepared to explain to the TA how any piece of code you submitted works, even if you copied it from the book or read about it on the internet.</li>

 <li>Please read the assignment in its entirety before asking questions.</li>

 <li>Please start assignments early, and ask for help early. Do not email us the night the assignment is due with questions.</li>

 <li>If you find any problems with the assignment it would be greatly appreciated if you reported them to the author (which can be found at the top of the assignment). Announcements will be posted if the assignment changes.</li>

</ol>