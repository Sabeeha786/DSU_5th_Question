# DSU_5th_Question
Please submit your answer here.
Q1: Write a Python Program to check whether a number is palindrome or not.
Q2: What is your name?
//code
n=int("input any number")
temp=n
rev=0
while(n>0):
  dig=n%10
  rev=rev* 10+dig
  n=n/10
if(temp==rev):
  print("the no is palindrome")
else:
  print("no not a palindrome")
//sabeeha tabassum

