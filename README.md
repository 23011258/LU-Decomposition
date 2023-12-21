# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# STEP1
give input in array
# STEP2
assign array to A.

# STEP3
print L

# STEP4
print U

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.

Developed by: Chandana Yendluri

RegisterNumber: 23011258

from scipy.linalg import lu

import numpy as np

arr = eval(input())

A=np.array(arr)

p,L,U=lu(A)

print(L)

print(U)

```
## OUTPUT:
![image](https://github.com/AkilaMohan/LU-Decomposition/assets/139842204/5ba05ac4-dd9b-404f-8cb8-f6f5ee5dd2b7)

(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.

Developed by: Chandana Yendluri

RegisterNumber: 23011258


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

```

## Output:
![image](https://github.com/AkilaMohan/LU-Decomposition/assets/139842204/cbb12250-1146-40ab-bf3c-3a686d5375d9)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

