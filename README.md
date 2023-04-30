Download Link: https://assignmentchef.com/product/solved-csce314-homework-3-problem-set
<br>
Below, the exercise problems are from the Haskell Textbook: “Programming in Haskell, 2nd Ed.”, by Graham Hutton. Some problems are modified (with additional requirements) by the instructor. Please read corresponding textbook chapters and the problem statements carefully, paying attention to the requirements. There may be significant penalties for not fulfilling such requirements.

Keep the name and type of each function exactly the same as given in the problem statement and the skeleton code. Also, do not remove or modify the test list or the main function. If you remove or modify those, then you will be penalized for that.

<strong>Problem 1.</strong> Put your full name, UIN, and <em>acknowledgements of any help received </em>in the head comment in your .hs file for this assignment.

<strong>Problem 2. </strong> Chapter 8, Exercise 1. (The function definition for mult is given in appendix A.) Carefully study the recursive type of natural numbers in Section 8.4. Using the definitions of the recursive data type Nat, mult and add, show how 2×2 = 4 proceeds, in the same way as showing how 2 + 1 = 3 proceeds given in Section 8.4 (page 97).

<strong>Problem 3. </strong> [Make sure you read Chapter 16 before attempting this problem.] Chapter 16. Exercise 6, page 247. This problem has two parts. Given the following data type

data Tree = Leaf Int | Node Tree Tree

<ol>

 <li> Given a tree, function leaves counts the number of leaves in the tree, and function nodes the number of internal nodes in the tree. Define leaves and nodes. The function types are as follows.</li>

</ol>

leaves :: Tree -&gt; Int nodes :: Tree -&gt; Int

<ol start="2">

 <li> Prove the following property by induction on trees.</li>

</ol>

leaves t = nodes t + 1

<strong>Problem 4. </strong> Chapter 8, Exercise 9. Study Section 8.7 carefully before attempting this problem.