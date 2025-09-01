# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy and lu method from scipy.linalg module to use built-in functions for calculation
2. Prepare the list of values from the givem matrix and convert it into an array using np.array()
3. Using lu(),lu_solve find the LU decomposition and the solution to the given matrix
4. Display the result of LU decomposition and the solution to the matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find L and U matrix using LU decomposition.
Developed by: Ashqar Ahamed S.T
RegisterNumber: 212224240018
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
p,L,U = lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Ashqar Ahamed S.T
RegisterNumber: 212224240018
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
l,p = lu_factor(a)
x=lu_solve((l,p),b)
print(x)

*/
```

## Output:
LU Decomposition:
<img width="1334" height="948" alt="image" src="https://github.com/user-attachments/assets/ee29e845-cea8-4340-b0b4-f615e888a8a5" />

Using LU to solve:
<img width="1070" height="883" alt="image" src="https://github.com/user-attachments/assets/fbdffdf9-1392-4b82-978f-3786a0491331" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

