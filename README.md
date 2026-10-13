# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"   
import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B = np.linalg.matrix_rank(A)
print(B)
```

## Output:
<img width="1391" height="675" alt="{B589D879-3DED-42BA-A642-A0DD07FDCD29}" src="https://github.com/user-attachments/assets/ae1644be-633b-46e1-9b59-b48528783bbb" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

