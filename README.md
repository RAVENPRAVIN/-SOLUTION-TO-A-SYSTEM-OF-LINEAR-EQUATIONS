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
```python
#Program to find the solution for the given linear equations.
#Developed by: PRAVIN KUMAR A.
#RegisterNumber: 23007430
import numpy as np
A= np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B= np.array([-9,4,-1])
result= np.linalg.solve(A,B)
print(result)
```

## Output:
![output](https://github.com/RAVENPRAVIN/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/146820534/cd88fc40-15ba-45bc-9a28-847122100ef5)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

