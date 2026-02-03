# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
we have to intialise program using import numpy to perform mathematical calculation
### Step 2: 
The input from the user is stored in the variable a
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
end of the program
## Program:
```python
#Program to find the rank of a matrix.
#Developed by:PON SARAVANA PANDIAN B
#RegisterNumber:212225230207
#The number of linear independentrows or columns in a matrix
#is known as its rank
import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
rank=np.linalg.matrix_rank(a)
print(rank)
```
## Output:
<img width="926" height="635" alt="Screenshot 2026-02-03 181616" src="https://github.com/user-attachments/assets/63a4796e-ce26-4454-8301-4c24a6c91965" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

