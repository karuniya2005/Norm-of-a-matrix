# Norm of a matrix
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
```Python
# Register No:212223240068
# Developed By:KARUNIYA M

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-05-01 174301](https://github.com/karuniya2005/Norm-of-a-matrix/assets/161425769/8d10b2e7-b1e2-4f41-9112-796e837b8fca)


### 2-Norm of a Matrix

![Screenshot 2024-05-01 174344](https://github.com/karuniya2005/Norm-of-a-matrix/assets/161425769/36ac78a1-72ba-4445-9f1a-14d89384a59e)


### Infinity Norm of a Matrix

![Screenshot 2024-05-01 174353](https://github.com/karuniya2005/Norm-of-a-matrix/assets/161425769/b19ff96e-1c4e-4449-8c7d-edf8a37fc98d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
