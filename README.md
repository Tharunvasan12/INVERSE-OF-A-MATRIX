# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equation and assign in np.array()
### Step 3: using the np.linalg.inv(),we can find the solution
### Step 4: End the program

## Program:
Developed by:Tharunish vasan.T

Register number:24001333
```
import numpy as np

# Define the matrix
matrix = np.array([
    [2, 1, 1],
    [1, 1, 1],
    [1, -1, 2]
])

# Check if the matrix is square
if matrix.shape[0] != matrix.shape[1]:
    print("Matrix must be square to compute the inverse.")
else:
    # Calculate the determinant
    determinant = np.linalg.det(matrix)
    
    if determinant == 0:
        print("The matrix is singular and does not have an inverse.")
    else:
        # Calculate the inverse
        inverse = np.linalg.inv(matrix)
        
        print(inverse)
```
## Output:![Screenshot 2024-12-04 083458](https://github.com/user-attachments/assets/b397751b-a95f-4174-852c-deb74332f672)

## Result:
Thus the inverse of given matrix is successfully solved using python program

