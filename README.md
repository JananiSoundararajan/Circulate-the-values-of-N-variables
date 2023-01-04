# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the n values from the user
### Step 2: 
Circulate the value of n variables
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be circulated
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: JANANI.S
#RegisterNumber: 22008491
a=eval(input())
b=int(input())
def circulate():
    for n in range(b+1):
        c=a[n:]+a[:n]
    return c 
print("After circulating the values are:",circulate())    
  ``` 
## Output:
![output](exp02output.png)
## Result:
Thus the program to circulate the n variables is successfully executed.