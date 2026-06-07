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
#Program to find the eigen values and eigen vectors.
#Develop by: POOJA A
#RegisterNumber: 212225040300
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
const=np.array([-9,4,-1])
result=np.linalg.solve(matrixA,const)
print(result)
~~~


## Output:
<img width="724" height="264" alt="image" src="https://github.com/user-attachments/assets/6c3d5dbe-65f9-4355-ae0a-0670d4a052ca" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

