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
# Register No:Annapureddy kavya
# Developed By:212225240011
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix)) 



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np  
matrix=eval(input()) 
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix)) 




# Infinity Norm of a Matrix


import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))


```
## Output:
### 1-Norm of a Matrix
<img width="829" height="261" alt="image" src="https://github.com/user-attachments/assets/c033dbdc-969a-4e39-9b70-7eb52dc21de7" />
<img width="863" height="755" alt="image" src="https://github.com/user-attachments/assets/385562f5-a5c5-4c63-86e6-454d1b60ae3f" />

### 2-Norm of a Matrix
<img width="828" height="230" alt="image" src="https://github.com/user-attachments/assets/675bdcdd-b3f0-4840-a69d-e7cc8c4720a6" />
<img width="834" height="851" alt="image" src="https://github.com/user-attachments/assets/bbcc6394-cfb1-44aa-9386-8a39db2a248b" />


### Infinity Norm of a Matrix
<img width="820" height="193" alt="image" src="https://github.com/user-attachments/assets/2acd6008-6bca-423c-817c-668164a2fa39" />
<img width="828" height="849" alt="image" src="https://github.com/user-attachments/assets/8c4a370f-0213-473c-a336-cf03e3bf35e6" />
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
