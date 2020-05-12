# Little-Monk-and-Balanced-Parentheses
https://www.hackerearth.com/practice/data-structures/stacks/basics-of-stacks/practice-problems/algorithm/little-monk-and-balanced-parentheses/


PROBLEM STATEMENT:-

Given an array of positive and negative integers, denoting different types of parentheses. The positive numbers xi denotes opening parentheses of type xi and negative number -xi denotes closing parentheses of type .

Open parentheses must be closed by the same type of parentheses. Open parentheses must be closed in the correct order, i.e., never close an open pair before its inner pair is closed (if it has an inner pair). Thus,[1,2,-2,-1]  is balanced, while [1,2,-1,-2] is not balanced.

You have to find out the length of the longest subarray that is balanced.

Input Format:-

First line contains an input N , denoting the number of parentheses. Second line contains N space separated integers.

Output Format:-

Print the length of the longest subarray that is balanced.

SAMPLE INPUT :-

5
1 -1 2 3 -2

SAMPLE OUTPUT:-

2

Explanation:-

The longest subarray that is balanced is (1,-1). (2,3,-2)  is not balanced as 3 is not balanced.
