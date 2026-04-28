# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program and input the square matrix. 
### Step 2: Find the determinant of the matrix.
### Step 3: Check determinant ≠ 0 (otherwise inverse not possible). 
### Step 4: Compute inverse using suitable method (e.g., linalg.inv())
### Step 5: Display the inverse matrix and stop

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: TEJASHREE SS
#RegisterNumber: 212224100058
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
b=np.linalg.inv(A)
print(b)

```
## Output:
<img width="1369" height="876" alt="Screenshot 2026-04-28 140006" src="https://github.com/user-attachments/assets/7cc0ee0e-85c8-46e2-bde7-5456e5075553" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

