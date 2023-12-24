# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user 
4. print result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:Chandana Yendluri
RegisterNumber: 23011258
'''
from scipy.linalg import lu
import numpy as np 
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```

'''Program to solve a matrix using LU decomposition.
Developed by: Chandana Yendluri
RegisterNumber: 23011258
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np 
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```

## Output:
![Screenshot 2023-12-24 151905](https://github.com/23011258/LU-Decomposition/assets/139842204/ea0350f5-9e91-481b-a0fc-9ce2e1be4fd0)

![Screenshot 2023-12-24 151922](https://github.com/23011258/LU-Decomposition/assets/139842204/132170d0-452a-408d-baae-7060b7bb1558)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

