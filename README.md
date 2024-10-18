java c
COMP2013
Data Structures and Algorithms
Programming Assignment 1
Deadline: 10:00am, 28th  OCT, 2024
Instructions
Submit the soft-copy of your program to Learn@PolyU
You can only submit one program file (either C++ or Java or Python), and the filename must follow the format below.
Language
Filename format
Filename example
C++
mainStudentID.cpp
main10987654d.cpp
Java
mainStudentID.java
main10987654d.java
Python
mainStudentID.py
main10987654d.py
Section 1: Problem
Problem description:
You need exactly m truck drivers to transport goods from a source location to a destination. All m truck drivers will depart from the source at the sametime. Each truck driver may take a different amount of time to reach the destination. There are n candidate drivers available, and you need to select m drivers from this pool. The driving time for each candidate driver from the source to the destination is given in an array A of size n, where each element represents the driving time in hours  (a positive real number). For example, if A=[2.3, 3, 2.5, 7], it means there aren=4 candidate drivers with driving times of 2.3 hours, 3 hours, 2.5 hours, and 7 hours respectively. Your objective is to select m drivers so that the difference between the maximum and minimum driving times among the selected drivers is minimized.
Input: Array A with n elements, m
Output: The minimum difference value
Note: You cannot use existing libraries to directly call off-the-shelf heap, queue, sorting, stack algorithms, but you can implement them when needed. Except these algorithms, you can use existing libraries when necessary, in your program.
Examples for the problem

Input
Output
Example 1
A=[2.3, 3, 2.5, 7], m=2
0.2
Example 2
A=[3, 4.3, 6.4, 5.2, 7.1], m=3
1.9
Section 2: Input and Output Format
Your program should read a test file in “.txt” containing the driving times of n drivers. The format of test files is illustrated by examples “file1.txt” and “file2.txt” below.
Your program should output on the screen a single value that is the minimum difference.
Here are samples of the input file and the output of your program.

Sample input file “file1.txt”
The output onscreen (stdout in C++)
4
2
2.3 3
2.5 7
0.2


Sample input file “file2.txt”
The output onscreen (stdout in C++)
5
3
3
4.3 6.4 5.2 7.1
1.9

The format of the input file is as follows:
the 1st line shows the number of candidate drivers n,
the 2nd line shows the number of drivers needed m,
each subsequent line shows the driving time of a c代 写COMP2013 Data Structures and Algorithms Programming Assignment 1C/C++
代做程序编程语言andidate drivern is integer in the range [1, 10000000].m is integer in the range [1, 10000000].Each driving time is in range (0, 200]
We will run your program by a command line like:
Language
Command line
C++ (after compilation)
./main StudentID input123.txt
Java (after compilation)
java main StudentID input123.txt
Python
python main StudentID.py input123.txt
where the argument “ input123.txt” is an example of the input filename.
Your program should only output the result number.
Please follow the above output format and DO NOT print any extra information.
Your program should pass all possible inputs, including those maybe invalid
-    You need to create testcases to debug and test your program’s correctness.
Section 3: Hints
•   Use alarge enough integer type (e.g., long) to prevent “integer overflow” in counting.
•   A simple program is to use nested for-loops. Its time complexity is O(n2). It is acceptable for small input file but too slow for large input file.
•   Some programming tricks can be used to speedup your program by a constant factor.
Section 4: Grading Criteria
(4.1) Naming conventions, compilation and execution commands
Before submission, rename your program tomainStudentID.cpp,   e.g., main10987654d.cppOR      mainStudentID.java,  e.g., main10987654d.javaOR      mainStudentID.py,     e.g., main10987654d.py
[C++ and Java only] Make sure that you can compile your program using the command:
g++ main StudentID.cpp -o main StudentID
OR      javac main StudentID.java
o No marks will be given if your program cannot be compiled.
We will run your program by a command line like:
./main StudentID input123.txt
OR      java main StudentID input123.txt
OR      python main StudentID.py input123.txt
where the argument “ input123.txt” is an example of the input filename.
Make sure that you can execute the above commands on the COMP apollo server successfully (see Appendix about how to connect to apollo server).
Otherwise, no marks will be given. The current versions on apollo are as follows:
g++ (GCC) 4.8.5,      javac 1.8.0_20,           Python 2.7.5
(4.2) Test files for grading
Total marks:  100%
Your program will be graded by using 10 test files.
The running time of your program will be measured on the COMP apollo server.
For each test file,
if your program can produce the correct output within 1 minute,
then you get +10 marks.
If you use off-the-shelf heap, queue, sorting, stack algorithms in existing libraries, 20 marks will be deducted.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
