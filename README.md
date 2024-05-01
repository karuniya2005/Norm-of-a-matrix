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
# Register No:KARUNIYA M
# Developed By:212223240068

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

![Screenshot 2024-05-01 174301](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/161425769/2d699e86-a938-47ac-b8c6-708a6f6dcbca)


### 2-Norm of a Matrix

![Screenshot 2024-05-01 174344](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/161425769/39d86199-84a7-4378-99f9-31bcbe2be0b4)


### Infinity Norm of a Matrix

![Screenshot 2024-05-01 174353](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/161425769/9ec425b4-6799-433a-8807-bee567e1c157)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
