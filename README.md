# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as "X" include the package in that variable.
4. After including the package in the "X" variable, print X to obtain LU Decomposition of the matrix.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: ponguru aasrith sairam
RegisterNumber: 23007809
'''
import numpy as np 
from scipy.linalg import lu
matrix=np.array(eval(input()))
P,L,U=lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: ponguru aasrith sairam
RegisterNumber: 23007809
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
# L,U of the matrix
![image](https://github.com/AasrithSairam/LU-Decomposition/assets/139331438/55d3f40c-10fd-40fc-97dd-e4a22c73e8ba)
# LU Decomposition of the matrix
![image](https://github.com/AasrithSairam/LU-Decomposition/assets/139331438/d1db9d56-ecb0-43ec-91be-37360fc8a3e4)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

