# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
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
A = np.array([[6,2,3],[3,1,1],[10,3,4]])
B = np.linalg.inv(A)
print(B)
```
## Output:
![OUTPUT](./images/assignment2.png)

## Result:
Thus the rank for the given matrix is successfully solved by using a python program.
