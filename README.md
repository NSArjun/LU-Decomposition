# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. Print the variable 'X'

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: ARJUN N S
#RegisterNumber: 212223230020

import numpy as np
from scipy.linalg import lu
matrix = np.array(eval(input()))
P,L,U = lu(matrix)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: ARJUN N S
#RegisterNumber: 212223230020

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu,piv),B)
print(X)
```

## Output:

(i) To find the L and U matrix
![image](https://github.com/NSArjun/LU-Decomposition/assets/148233801/ff1d9648-3557-4a67-b9d6-3afbad72c460)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/NSArjun/LU-Decomposition/assets/148233801/cd412e89-3b02-4b3d-b66a-7a5bc68dbae7)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

