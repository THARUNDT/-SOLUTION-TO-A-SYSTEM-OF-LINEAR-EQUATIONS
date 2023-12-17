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
~~~
#Program to find the solution for the given linear equations.
#Developed by: THARUN D
#RegisterNumber:23013993
import numpy as np
A = np.array([[1,3],[2,5]])
B=np.array([5,-3])
le=np.linalg.solve(A,B)
print(le)
~~~

## Output:
![Screenshot 2023-12-17 094139](https://github.com/THARUNDT/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/144871537/cc9b3c66-bae0-4774-ae0c-a8b874b57848)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

