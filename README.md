Download Link: https://assignmentchef.com/product/solved-cse015-discrete-mathematics-laboratory-3
<br>
<h1>Introduction</h1>

In this lab we continue to practice our Python programming skills by adding further functionality to our library of propositional logic tools.

<h1>Consistency of System Descriptions</h1>

Write a Python program that asks the user to enter a system description as a series of propositions. Determine whether or not the description is consistent and print a message to that effect. Your user experience should be along the lines of the following:

Enter a proposition: p and q

Would you like to enter more (Y/N): Y

Enter a proposition: p -&gt; q Would you like to enter more (Y/N): N Your description is consistent.

Save your program in a file and upload it under the appropriate CatCourses assignment page.

<h1>Descriptive System Descriptions</h1>

Extend the functionality of your program from the last question by allowing the user to assign a meaning to all the propositional variables. If the user has entered a consistent description, your program should also outline the conditions that satisfy consistency. For example:

Enter a proposition: -p

Would you like to enter more (Y/N): Y

1

Enter a proposition: -q

Would you like to enter more (Y/N): Y

Enter a proposition: p &lt;-&gt; q

Would you like to enter more (Y/N): N

Your propositions contain the following variables: [’p’, ’q’]:

Enter meaning of p: John is a Knight

Enter meaning of q: James is a Knight Your description is consistent when:

It is not the case that John is a Knight

It is not the case that James is a Knight

Save your program in a file and upload it under the appropriate CatCourses assignment page.

Hint: To get a list of all the variables used in the propositions the user enters, simply make a truth table for the propositions. Say your truth table is called myTruthTable, then the list of variables occurring in all the propositions is myTruthTable.vars

2