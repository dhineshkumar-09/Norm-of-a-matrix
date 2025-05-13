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
```
# Register No: 212224220026
# Developed By: DHINESHKUMAR E
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
a="{:.2f}".format(ans)
print(a)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
a="{:.2f}".format(ans)
print(a)
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/bbd65e30-9471-4d5a-b926-e7ef45c5fed1)


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/58d6316f-d41b-4252-9217-8a5007a495e4)


### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/447d7b2a-24fa-468a-a3cb-385630417088)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
