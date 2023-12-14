# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package and scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as 'X' include the package in the variable.
4. print the variable 'X'.

## Program:
(i) To find the L and U matrix

~~~
/*
Program to find L and U matrix using LU decomposition.
Developed by: lakshmi mounika
RegisterNumber: 23004124
*/

from scipy.linalg import lu
import numpy as np
arr = eval(input())
A = np.array(arr)
P,L,U = lu(A)
print(L)
print(U)

~~~
(ii) To find the LU Decomposition of a matrix
~~~
/*
Program to solve a matrix using LU decomposition.
Developed by: lakshmi mounika
RegisterNumber: 23004124
*/


# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr = eval(input())
constant = eval(input())
A = np.array(arr)
B = np.array(constant)
result = lu_factor(A)
solution = lu_solve(result,B)
print(solution)
~~~

## Output:
![Screenshot 2023-12-14 182337](https://github.com/mounika2005/LU-Decomposition/assets/145633112/157deb1c-0030-4000-9146-a569a340c2c4)
![Screenshot 2023-12-14 182310](https://github.com/mounika2005/LU-Decomposition/assets/145633112/981e049d-cb20-4d4a-95de-76f8c3fd759c)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

