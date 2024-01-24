Java Program for User Input and Number Analysis

Description:

This Java program allows users to input a specified number of integers, and it performs various analyses on the input data. It categorizes the numbers into two ArrayLists, one for even numbers and another for odd numbers. Additionally, the program identifies the index of the first number with the smallest distance to its neighboring number.

Key Features:

User Input:
Prompt users to input the desired number of integers, and then take user input for the specified count.

Categorization:
Categorize input numbers into two separate ArrayLists—one for even numbers and another for odd numbers.

Display Categorized Lists:
Present the ArrayLists containing even and odd numbers for user inspection.

Finding Index with Smallest Distance:
Implement a function named findIndexWithSmallestDistance, which calculates the index of the initial number with the smallest distance to its neighboring number in the ArrayList.

How to Utilize:

Compile:
Compile the Java source file using a Java compiler.

bash
Copy code
javac UserInputAnalysis.java
Run:
Execute the compiled Java program.

bash
Copy code
java UserInputAnalysis
Input Gathering:
Follow the on-screen instructions to specify the number of inputs and enter the corresponding integer values.

Results Display:
The program will exhibit the categorized lists of even and odd numbers, along with the index of the number with the smallest distance.

Function Details:

input()
Captures user input, categorizes numbers, and displays the results.

findIndexWithSmallestDistance(ArrayList<Integer> numbers)
Identifies the index of the initial number with the smallest distance to its neighboring number in the provided ArrayList.






