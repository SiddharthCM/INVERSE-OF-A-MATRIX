# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : Import the NumPy library.
### Step 2: Create and store the matrix A.
### Step 3: Compute the inverse of matrix A using np.linalg.inv().
### Step 4: Display the inverse matrix.

## Program:
```python

#Program to find the inverse of a matrix.
#Developed by: Siddharth CM
#RegisterNumber:212225040413
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
inverse=np.linalg.inv(a)
print(inverse)

```

## Output:

![alt text](image.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

