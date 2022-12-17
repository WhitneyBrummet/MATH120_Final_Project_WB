# MATH120_Final_Project_WB
Necessary text files: 
- https://projecteuler.net/problem=42
- https://projecteuler.net/problem=22

This repository holds the final project of Math 120 where I answered the following set of questions:

Set 1: Problem 22
- What is the total of all the name scores in the file?
- What is the highest-scored name? 
- Is the highest-scored name the longest name?
- What is the lowest-scored name?
- Is the lowest-scored name the shortest name? 
- Is my name in the list?
- What is the score of my name? 

I used a class reader to read text files and seperate the names into a list.
I used a for loop to find my name and the score of my name
I used 2 for loops to find the longest and shorest names
I used a for loop to translate the name list to a list of scores

Set 2: Problem 36
 - What is the total of all the palandrome numbers below 1,000,000?
 - How long does it take to run this code?
 - What is the highest palindrome number? 
 - What numbers are also palindrome numbers in base 8?

I used a function to find all the palindromic numbers below a specified number
I used the time built in function to calculate how long the function took to process and to build the graph
The function returned a list so to find the highest palindrome number I just returned the last element of the list
I added another if else condition to handle palindromes in base 8

Set 3:
- How many words in this file have an alphabetical score that equals a triangle number?
- How many words in this file have an alphabetical score that equals a hexagonal number?
- What word has the largest score?
- What word that equals the largest triangle number?

I used a class reader to read text files and seperate the words into a list
I used a for loop to translate the list into scores
I used a class and methods to determine if the scores were triange or hexagonal numbers
