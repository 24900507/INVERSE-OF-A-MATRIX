# INVERSE-OF-A-MATRIX
## Devoloped by: AKASH G
## Register Number : 212224100004
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Find the determinant of the matrix. If it is 0, the matrix has no inverse.
### Step 2: Find minors and cofactors for every element of the matrix.
### Step 3: Make the adjoint by taking the transpose of the cofactor matrix.
### Step 4: Divide the adjoint by the determinant to get the inverse.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: AKASH G
#RegisterNumber: 212224100004

import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
A_inv=np.linalg.inv(A)
print(A_inv)
```
## Output:

<img width="1110" height="673" alt="Screenshot 2025-08-19 at 7 01 44 PM" src="https://github.com/user-attachments/assets/3e3e1c3f-ce68-472c-bae0-7773ef26c0f3" />
<img width="1080" height="275" alt="Screenshot 2025-08-19 at 7 02 07 PM" src="https://github.com/user-attachments/assets/6ea75ad7-0f0b-4808-b95e-fc5db6021097" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

