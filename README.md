# Hackerrank-Js-Challenge

<p align="center">
  <img src="hack.png">
  </p>


# I am working on the 10 days of javascript challenge to get expertise on Js 👨‍💻 ✨



# Day-0

## Task : Variables named firstInteger,firstDecimal and firstString are declared for you in the editor
<ol>
<li> Convert to an integer (Number type), then sum it with and print the
  result on a new line using console.log .</li>
<li> Convert to a floating-point number (Number type), then sum it with
  and print the result on a new line using console.log .</li>
<li> Print the concatenation of and on a new line using console.log . Note
  that must be printed first.</li>
  </ol>
  
  
###  Input Format

Data Type Parameter Description
string The string representation of an integer you must sum with .
string The string representation of a floating-point number you must sum with
.
string A string of one or more space-separated words you must append to .
Output Format
Print the following three lines of output:
1. On the first line, print the sum of and the integer representation of .
2. On the second line, print the sum of and the floating-point representation of
.
3. On the third line, print concatenated with . You must print
before .


# Day-1  Arithmetic Operators

## Task

Complete the following functions in the editor below:
1. getArea(length, width): Calculate and return the area of a rectangle having sides and .
2. getPerimeter(length, width) : Calculate and return the perimeter of a rectangle having sides
and .
The values returned by these functions are printed to stdout by locked stub code in the editor.

# Day-1 Functions

## Task

Implement a function named factorial that has one parameter: an integer,n . It must return the value of
n!(i.e. n factorial).
Input Format
Locked stub code in the editor reads a single integer,n , from stdin and passes it to a function named
factorial.
Constraints
Output Format
The function must return the value of n! .

# Day-1 Let and Const

## Task

1. Declare a constant variable,PI , and assign it the value Math.PI. You will not pass this challenge
unless the variable is declared as a constant and named PI (uppercase).
2. Read a number,r, denoting the radius of a circle from stdin.
3. Use PI and r to calculate the and of a circle having radius .
4. Print area as the first line of output and print perimeter as the second line of output

# Day-2 Conditional Statements: If-Else

## Task 

Complete the getGrade(score) function in the editor. It has one parameter: an integer, score, denoting the number of points Julia earned on an exam. It must return the letter corresponding to her Grade. 

# Day-2  Conditional Statements: Switch

## Task

Complete the getLetter(s) function in the editor. It has one parameter: a string, , consisting of lowercase English alphabetic letters (i.e., a through z). It must return A, B, C, or D depending on the following criteria:

If the first character in string s is in the set {a,e,i,o,u} , then return A.
If the first character in string s is in the set {b,c,d,f,g}, then return B.
If the first character in string s is in the set {h,j,k,l,m} , then return C.
If the first character in string s is in the set {n,p,q,r,s,t,v,w,x,y,z} , then return D.

# Day-2 Loops

## Task

Complete the vowelsAndConsonants function in the editor below. It has one parameter, a string, , consisting of lowercase English alphabetic letters (i.e., a through z). The function must do the following:

1.>First, print each vowel in s on a new line. The English vowels are a, e, i, o, and u, and each vowel must be printed in the same order as it appeared in .
2.>Second, print each consonant (i.e., non-vowel) in s on a new line in the same order as it appeared in .

# Day-3 Arrays

## Task

Complete the getSecondLargest function in the editor below. It has one parameter: an array,nums , of n numbers. The function must find and return the second largest number in nums .


# Day-3 Try, Catch, and Finally

## Task

Complete the reverseString function; it has one parameter,s . You must perform the following actions:

Try to reverse string s using the split, reverse, and join methods.
If an exception is thrown, catch it and print the contents of the exception's message on a new line.
Print s on a new line. If no exception was thrown, then this should be the reversed string; if an exception was thrown, this should be the original string.


# Day-3 Throw

## Task

Complete the isPositive function below. It has one integer parameter,a. If the value of a is positive, it must return the string YES. Otherwise, it must throw an Error according to the following rules:

If  is a ,0 throw an Error with message= Zero Error.
If  is a negative, throw an Error with message=Negative Error.


# Day-4 Create a Rectangle Object

## Task

Complete the function in the editor. It has two parameters: a and b. It must return an object modeling a rectangle that has the following properties:

length    : This value is equal to a.
width     : This value is equal to b.
perimeter : This value is equal to 2(a+b).
Area      : This value is equal to a*b

# Day-4 Count Objects

## Task

Complete the function in the editor. It has one parameter: an array,a , of objects. Each object in the array has two integer properties denoted by x and y . The function must return a count of all such objects o in array a that satisfy o.x==o.y 

# Day-4 Classes

## Task

Create a Polygon class that has the following properties:

A constructor that takes an array of integer values describing the lengths of the polygon's sides.
A perimeter() method that returns the polygon's perimeter.
Locked code in the editor tests the Polygon constructor and the perimeter method.

Note: The perimeter method must be lowercase and spelled correctly.


# Day-5 Inheritance

## Task

We provide the implementation for a Rectangle class in the editor. Perform the following tasks:

Add an area method to Rectangle's prototype.
Create a Square class that satisfies the following:
1. It is a subclass of Rectangle.
   It contains a constructor and no other methods.
2. It can use the Rectangle class' area method to print the area of a Square object.
   Locked code in the editor tests the class and method implementations and prints the area values to STDOUT.

# Day-5 Template Literals

## Task

The code in the editor has a tagged template literal that passes the area and perimeter of a rectangle to a tag function named sides. Recall that the first argument of a tag function is an array of string literals from the template, and the subsequent values are the template's respective expression values.


# Day-5 Arrow Functions

## Task

Complete the function in the editor. It has one parameter: an array,nums . It must iterate through the array performing one of the following actions on each element:

If the element is even, multiply the element by 2 .
If the element is odd, multiply the element by 3 .
The function must then return the modified array.


# Day-6 Bitwise Operators

## Task
 Bitwise '&' binary operation is there
 
 

# Day-6 JavaScript Dates

## Task

Given a date string,date string , in the format MM/DD/YYYY, find and return the day name for that date. Each day name must be one of the following strings: Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, or Saturday. For example, the day name for the date 12/07/2016 is Wednesday.

# Day-7 Regular expression I

## Task
Complete the function in the editor below by returning a RegExp object, , that matches any string  that begins and ends with the same vowel. Recall that the English vowels are a, e, i, o, and u.

# Day-7 Regular expression II
## Task
Complete the function in the editor below by returning a RegExp object, , that matches any string  satisfying both of the following conditions:

String  starts with the prefix Mr., Mrs., Ms., Dr., or Er.
The remainder of string  (i.e., the rest of the string after the prefix) consists of one or more upper and/or lowercase English alphabetic letters (i.e., [a-z] and [A-Z]).

# Day-7 Regular expression III
## Task
Complete the function in the editor below by returning a RegExp object,re , that matches every integer in some string s .

# Day-8 Create Button
## Task
Complete the code in the editor so that it creates a clickable button satisfying the following properties:

The button's id is btn.
The button's initial text label is . After each click, the button must increment by . Recall that the button's text label is the JS object's innerHTML property.
The button has the following style properties:
A width of 96px.
A height of 48px.
The font-size attribute is 24px.

# Day-8 Button Container
## Task
We want to create nine buttons enclosed in a div, laid out so they form a 3*3  grid. Each button has a distinct label from 1 to 9, and the labels on the outer buttons must rotate in the clockwise direction each time we click the middle button.


# Day-9 Binary Calculator
## Task

Implement a simple calculator that performs the following operations on binary numbers: addition, subtraction, multiplication, and division.


----------------------------------------------------------------------------------------------------------------------------------------

# JS Resources 
<ul>
  <li>http://codekirei.com/posts/currying-with-arrow-functions/  Use of Arrow Function(=>)</li>
  <li>https://stackoverflow.com/questions/27678052/usage-of-the-backtick-character-in-javascript USe of Backtick(`)</li>
  
</ul>  
