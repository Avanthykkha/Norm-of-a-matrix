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
# Register No: 24006077
# Developed By:
# 1-Norm of a Matrix

import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,1)
norm_of_matrix= "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,2)
norm_of_matrix= "{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat= np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix= "{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-02 111709](https://github.com/user-attachments/assets/0e2798c3-4941-42d7-8836-6673b009ce37)


### 2-Norm of a Matrix
![Screenshot 2024-12-02 111856](https://github.com/user-attachments/assets/82119f89-2065-45f6-91e4-22fea2bbb1ee)


### Infinity Norm of a Matrix
![Screenshot 2024-12-02 112006](https://github.com/user-attachments/assets/e96d83bd-25a2-4119-b370-b5a195daa097)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
