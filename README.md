# EIGENVALUES-AND-EIGENVECTORS
## Developed by : Dharshan V
## Register Number: 212224240035
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : First, import numpy as np loads the NumPy library so you can use its functions.
### Step 2: The next line creates a 3×3 matrix A using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Finally, the print() statement displays the eigenvalues and eigenvectors on the screen.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Dharshan V
#RegisterNumber: 212224240035
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigenvalues,eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
<img width="1249" height="857" alt="Screenshot 2025-08-25 094917" src="https://github.com/user-attachments/assets/df7c19ff-2837-4ff8-befe-deb42697722b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
