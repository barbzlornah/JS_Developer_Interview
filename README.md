# JS_Developer_Interview
Interview JS

============================================================

Problem 1

============================================================


Input is an array of Integers which denotes the stock value of company X.

Ex : [1,5,6,7,34,10]

In this case :

1 is the stock value of company X on Day 0.

5 is the stock value of company X on Day 1.

...
10 is the stock value of a comany X on Day 5.

You need to find the day where I can buy the stock and day where I can sell the stock to get the max profit :
In the above case, If I buy the stock at Day 0 (i.e when the value is 1) and sell on Day 4 (when the value is 34). 
I get the max profit. Profit = 34-1 = 33.
If there is a test case in which any profit is not possible, Print -1.
Test Cases :

[200, 1,5,6,7,34,10]

[1,5,6,7,34,10,300]

[10,1,5,6,7,34,10,20]

[10,7] // Output -> -1. Profit not possible.

[7,10]

[1] //profit should be 0 in this case. You buy and sell on the same day.

============================================================

Problem 2

============================================================

Flatten this array out : [1,2,[3,4,[5,6],7,[8,9]]]

Output should be 1,2,3,4,5,6,7,8,9

Please don't use any library functions for this problem.


