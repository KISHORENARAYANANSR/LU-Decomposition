# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. Print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: KISHORE NARAYANAN S R
RegisterNumber: 212223110023
*/
import numpy as np
from scipy.linalg import lu
matrix = np.array(eval(input()))
P,L,U = lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: KISHORE NARAYANAN S R
RegisterNumber: 212223110023
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu,piv),B)
print(X)
```

## Output:
![lu decomposition]()
![Screenshot 2024-04-16 203551](https://github.com/KISHORENARAYANANSR/LU-Decomposition/assets/148202102/04f417dd-a009-4143-9ea4-8e80ba7dc4d4)
![Screenshot 2024-04-16 203606](https://github.com/KISHORENARAYANANSR/LU-Decomposition/assets/148202102/0c2bfe2a-b139-440a-a61d-bab389168d53)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

