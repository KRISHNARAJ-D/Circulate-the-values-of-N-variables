# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
First step is to define the function
### Step 2: 
get l,n inputs from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
finally print the result 
## Program:
```
#Program to circulate N values.
#Developed by: KRISHNARAJ-D
#RegisterNumber:22005130
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:s
!['OUTPUT'](/Screenshot%20from%202022-12-24%2014-39-08.png)

## Result:
By this program we able to circulate the values of n-variables
