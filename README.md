# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:import numpy package
### Step 2:get the input matrix
### Step 3:find the solution of system of linear equation
### Step 4:print the result

## Program:
```python
#Program to find the solution for the given linear equations.
#Developed by:Rajesh A 
#RegisterNumber:22008551
import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B = np.array([-9,4,-1])
sol = np.linalg.solve(A,B)
print(sol)
```

## Output:
![output1](linear.png)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

