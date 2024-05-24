# Ex No:07 Norm of a matrix
### DATE:
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
#Developed by:JAIKANTH B
#RegisterNumber: 2305002010

#program to find infinity norm of a matrix.

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

#program to find 2-norm of a matrix.

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

#Program to find infinity-norm of a matrix.

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-24 170424](https://github.com/jaikanth25/Norm-of-a-matrix/assets/155935294/10ce45fd-f9a8-4311-98f8-ca93b285c143)

### 2-Norm of a Matrix
![Screenshot 2024-05-24 170618](https://github.com/jaikanth25/Norm-of-a-matrix/assets/155935294/033e2621-7eb3-4f84-9f59-d092f2ce141d)

### Infinity Norm of a Matrix
![image](https://github.com/jaikanth25/Norm-of-a-matrix/assets/155935294/b346de90-bd0a-4fcd-9d91-1b6863f237bb)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
