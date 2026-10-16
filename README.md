# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
#Program to find the inverse of a matrix.
#Developed by: SHUBHAM KUMAR
#RegisterNumber:26013866

import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[6, 2, 3],[3, 1, 1],[10, 3, 4]])

r = np.linalg.inv(A)

print(r)


<img width="1137" height="737" alt="Exp 03 CR Inverse of a matrix" src="https://github.com/user-attachments/assets/8c76c144-03f2-4d9a-a0f6-5097a8bd4c0d" />

## Output:<img width="762" height="177" alt="Exp 03 CR Inverse of a matrix  result" src="https://github.com/user-attachments/assets/14876d5d-698e-4acd-97f3-d97bbf724818" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

