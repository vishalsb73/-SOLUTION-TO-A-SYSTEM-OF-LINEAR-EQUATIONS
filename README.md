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
import numpy as np 
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
X=np.linalg.solve(A,B)
print(X)
```
## Output:
<img width="1113" height="801" alt="Screenshot 2026-02-05 140137" src="https://github.com/user-attachments/assets/06024970-08bc-4a8c-aacf-947afe8b34c7" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

