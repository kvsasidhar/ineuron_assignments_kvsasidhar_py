# Assignment 2

## Problem statement:
Write a program which accepts a sequence of comma-separated numbers from console and generate a list. 


```python
list = [] # empty list initialization
string = str(input("enter comma seperated numbers")) # accept comma seperated numbers from user
string = string.split(',') # split the string on ','; this will generate a list of characters

for i in range(0,len(string)):
    list.append(int(string[i])) # type cast each characters to number and add to the list
list
```

    enter comma seperated numbers1,2,3,4,5,6,7,8,9,10
    




    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]



## Problem statement:
Create below pattern using nested for loop in python

<img src = "pattern.png">


```python
n= 4
for i in range(0,n):
    for j in range(0,i+1):
        print('* ',end="")
    print('\r')
for i in range(n-1,0,-1):
    for j in range(0,i):
        print('* ',end="")
    print('\r')
```

    * 
    * * 
    * * * 
    * * * * 
    * * * 
    * * 
    * 


## Problem statement:
Write a Python program to reverse a word after accepting the input from the user. 
    


```python
str1 = input()
str1[::-1]
```

    ineuron
    




    'norueni'




```python

```
