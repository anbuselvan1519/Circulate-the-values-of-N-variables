# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function
### Step 2: 
Get the variables from user to enter inside the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
After rotating the variables , store the rotated variables in a seperate list
### Step 6: 
At last , print the list of rotated variables 
## Program:
```
#Program to circulate N values.
#Developed by: Anbuselvan.s
#RegisterNumber:23005959
def circulate():
    list1=eval(input())
    a=int(input())
    l2=[]
    for i in range(a,len(list1)):
        l2.append(list1[i])
    for i in range(a):
        l2.append(list1[i])
    print("After circulating the values are:",l2)    
```
## Output:
![image](https://github.com/anbuselvan1519/Circulate-the-values-of-N-variables/assets/139841744/93e73a8c-746b-48c6-9cf4-dd0013224cc0)

## Result:
Thus the circulate n variables are successfully completed.
