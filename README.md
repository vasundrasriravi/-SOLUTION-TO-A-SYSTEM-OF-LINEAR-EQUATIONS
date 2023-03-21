# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by:vasundra sri.R 
#RegisterNumber:212222230168
import numpy as np
A=np.array([[1,-3] ,[3,1]])
B=np.array([0,10])
s=np.linalg.solve(A,B)
print(s)

```
## Output:
![solve](https://user-images.githubusercontent.com/119393983/226619129-6b93b72e-ff73-4278-b59f-e6449e64ba8f.png)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

