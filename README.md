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
4. print the variable 'X'
## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: G.Lahari sindhu
#RegisterNumber: 212223240038
import numpy as np
from scipy .linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: G.Lahari sindhu
#RegisterNumber: 212223240038
# To print X matrix (solution to the equations)
import numpy as np
from scipy .linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
p=lu_solve((lu,piv),b)
print(p)
```
## Output:
![image](https://github.com/user-attachments/assets/cbd878cf-23d2-4254-8c44-88f00efd24ae)
![image](https://github.com/user-attachments/assets/d5cbcc40-33db-44d4-b5b0-7b6d75247fd4)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

