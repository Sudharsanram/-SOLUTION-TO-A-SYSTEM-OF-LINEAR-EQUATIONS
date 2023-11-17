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
#Developed by: SUDHARSAN RAM M
#RegisterNumber: 212222110048
import numpy as np
A=np.array([[1,3], [2,5]])
b=np.array([5,-3])
soln=np.linalg.solve (A,b)
print(soln)
```

## Output:

![image](https://github.com/Sudharsanram/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119393980/e721b7fc-a812-4e57-bb2b-4811df127e6a)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

