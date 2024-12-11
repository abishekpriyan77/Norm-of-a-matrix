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
# Register No:
# Developed By:
# 1-Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
...








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
norm="{:.2f}".format(ans)
print(norm)




```
## Output:
### 1-Norm of a Matrix
![Screenshot (199)](https://github.com/user-attachments/assets/41aaaedf-ecaa-4635-8296-87883f005307)


### 2-Norm of a Matrix
![Screenshot (200)](https://github.com/user-attachments/assets/90e9eb70-9b5f-46d6-8f1a-bcf7df2051ee)


### Infinity Norm of a Matrix

![Screenshot (201)](https://github.com/user-attachments/assets/98050b2e-3f9e-4115-b8a2-5daaed54e2a2)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
