# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define the fuction circulate
### Step 2: 
Get the list from the user for which it has to be circulated
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the result as after circulating the values
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: YASHWINI M
#RegisterNumber: 23004946
def circulate():
    print()
list=eval(input())
n=int(input())
result=list[n: ]+list[ :n]
print("After circulating the values are:",result)
    
```
## Output:
![output](/outputcirculate.png)

## Result:
Thus circulating of n variables is successfully executed
