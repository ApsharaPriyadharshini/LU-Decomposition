# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the required libraries and read the matrix elements.
2. Store the matrix in a 2D array.
3. Apply LU Decomposition to obtain L and U matrices.
4. Display the L and U matrices and stop the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Apshara Priyadharshini M
RegisterNumber: 212225040026

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Apshara Priyadharshini M
RegisterNumber: 212225040026

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
![lu decomposition]()
<img width="1237" height="574" alt="image" src="https://github.com/user-attachments/assets/c87856df-1c80-4a15-8d8c-494b3d12c7bd" />
<img width="1250" height="331" alt="image" src="https://github.com/user-attachments/assets/c22b4b7f-38a0-4302-ab8f-e5fec4a0a8d5" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

