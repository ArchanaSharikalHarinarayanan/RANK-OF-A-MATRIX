# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by:Allen Joveth P
#RegisterNumber:23009582
import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
Rank of a matrix

![image](https://github.com/ArchanaSharikalHarinarayanan/RANK-OF-A-MATRIX/assets/139422287/7dd33cb2-bd6d-4de1-a855-06b467879804)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

