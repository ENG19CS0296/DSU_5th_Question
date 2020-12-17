# DSU_5th_Question
Please submit your answer here.
Q1: Write a Python Program to check whether a number is palindrome or not.
Q2: What is your name?

Q1: 
'''
Write a Python Program to check whether a number is palindrome or not.
'''

n=int(input("Enter number:"))
temp=n
r=0
while(n>0):
    d=n%10
    r = r * 10+d
    n = n//10
if r == temp:
  print("Palindrome")
else:
  print("Not palindrome")
  
Q2: Shishira S
