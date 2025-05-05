# cs-140-introduction-to-computer-science-lab-3-solved
**TO GET THIS SOLUTION VISIT:** [CS 140 Introduction to Computer Science Lab #3 Solved](https://www.ankitcodinghub.com/product/cs-140-introduction-to-computer-science-lab-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;8570&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS 140 Introduction to Computer Science Lab #3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="product-description">For this lab, students will work individually. If questions arise, try to see if those around you are able to answer them, chances are one of your fellow students has encountered your problem and has figured out how to solve it. Ask the instructor for help as a last resort.

Try your best to complete the following programs today in class. If you cannot complete them all, make sure you complete them prior to the next class. Submit all files together in one .zip file to blackboard.

Exam.java Pattern.java FileIO.java PrimeChecker.java MultiplicationLearner.java

Lab Objectives

 Be able to write Java programs with

o Decision Structures

o Input Validation

o Loops and Nested Loops

o Sentinel Values

o File Input and Output

o Random Numbers

 Be able to test and debug a program

Task #1 Exam

(1) Rewrite the following program and use a for-loop to replace the while-loop.

(2) Add statements to verify whether the user input is either 0 or 1. If not, display an appropriate error message and ask the user to enter again until ten correct input values are processed.

//analysis of examination results import java.util.Scanner;

public class Exam { public static void main(String[] args) { Scanner keyboard = new Scanner(<a href="http://system.in/" target="_blank" rel="nofollow noopener">System.in</a>); int passes=0, failures=0, students=0, result; while (students&lt;10) { System.out.print(“enter result (1=pass, 0=fail): “); result = keyboard.nextInt(); if (result==1) passes++; else failures++; students++; } System.out.println(passes + ” passed\n” + failures + ” failed”); if (passes &lt; 5) System.out.println(“Raise tuition”); } }

Task #2 Pattern

Write a complete Java program using nested-for loops to produce the following pattern:

1 2 3 4 5 6 1 2 3 4 5 1 2 3 4 1 2 3 1 2 1

Task #3 File Input and Output

Write a complete Java program that asks the user for the names of three files. The first file should be opened for reading and the other two files should be opened for writing. The program should read the contents of the first file, change all characters to uppercase, and store the results in the second file at the same time append the results to the third file. At the end, the second file will be a copy of the first file, except that all the characters will be uppercase. If we run the program several times, the third file will hold the contents of all input files that your program has processed. Use any text editor to create several input files that can be used to test the program. Ex: Suppose inFile1.dat contains Monday, Tuesday and inFile2.dat contains Wednesday, Thursday, and Friday.&nbsp;tadiaz@fluffy&nbsp;~ $ java FileIO enter input filename: inFile1.dat enter output filename: outFile enter another output filename (append): appFile check your output files — outFile, appFile&nbsp;tadiaz@fluffy&nbsp;~ $ cat outFile MONDAY TUESDAY&nbsp;tadiaz@fluffy&nbsp;~ $ cat appFile MONDAY TUESDAY&nbsp;tadiaz@fluffy&nbsp;~ $ java FileIO enter input filename: inFile2.dat enter output filename: outFile enter another output filename (append): appFile check your output files — outFile, appFile&nbsp;tadiaz@fluffy&nbsp;~ $ $ cat outFile WEDNESDAY THURSDAY FRIDAY&nbsp;tadiaz@fluffy&nbsp;~ $ cat appFile MONDAY TUESDAY WEDNESDAY THURSDAY FRIDAY

Task #4 Prime Checker

A prime number is a number that is only evenly divisible by itself and 1. For example, the number 5 is a prime because it can only be evenly divided by 1 and 5. The number 6, however, is not a prime because it can be divided evenly by 1, 2, 3, and 6.

Write a static boolean method named isPrime, which takes an integer as an argument and returns true if the argument is a prime number, or false otherwise. Demonstrate the method in a complete program.

Task #5 Educational Learning Tools (Challenge)

Computers are playing an increasing role in education. Write a program that will help an elementary school student learn multiplication. Use random number generator to produce two positive one-digit integers. It should then type a question such as:

How much is 6 times 7?

The student then types the answer (if they enter -1 the program will end). Your program checks the student’s answer. If it is correct, print one of the following messages randomly and then ask another multiplication question.

Very good! Excellent! Nice work! Keep up the good work!

If the answer is wrong, print one of the following messages and then let the student try the same question again repeatedly until the student finally gets it right. The main purpose for varying the computer’s dialogue is to hold the student’s attention.

No. Please try again. Wrong. Try once more. Don’t give up! No. Keep trying.</div>
<div class="ui divider"></div>
<div class="ui middle aligned grid product-share">
<div class="four wide column"></div>
</div>
