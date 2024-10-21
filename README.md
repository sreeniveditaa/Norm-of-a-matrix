# DATE :
# EX NO. 7 :Norm of a matrix
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
# Register No: 212223230213
# Developed By: SREE NIVEDITAA SARAVANAN
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
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
![Screenshot 2024-10-21 164258](https://github.com/user-attachments/assets/fb04feeb-93a7-47b5-8c84-ab8e1ee301cb)
![Screenshot 2024-10-21 164311](https://github.com/user-attachments/assets/9a6a023c-2690-4a7c-a1cc-af072e17b13a)


### 2-Norm of a Matrix
![Screenshot 2024-10-21 164321](https://github.com/user-attachments/assets/fafdfe35-9a9f-4080-87ee-3e7a19bcc819)
![Screenshot 2024-10-21 164330](https://github.com/user-attachments/assets/79f26197-ee80-4948-ab7a-456849054a12)


### Infinity Norm of a Matrix
![Screenshot 2024-10-21 164338](https://github.com/user-attachments/assets/84c7231c-14dd-4fcf-be76-4fa83b36d808)
![Screenshot 2024-10-21 164346](https://github.com/user-attachments/assets/4dbccc66-54f7-4747-8390-05f0e9b8c6e5)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
