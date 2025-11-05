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
# Register No:25017135
# Developed By: dilip kumar
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
noem_of_matrix="{:.2f}".format(ans)
print(noem_of_matrix)





# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
noem_of_matrix="{:.2f}".format(ans)
print(noem_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
noem_of_matrix="{:.2f}".format(ans)
print(noem_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1127" height="217" alt="image" src="https://github.com/user-attachments/assets/033095e2-b567-4aa1-87f1-0dfc1e74e382" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1062" height="260" alt="image" src="https://github.com/user-attachments/assets/fad20e66-42e4-4aae-92d0-cc600c098cca" />


### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1102" height="205" alt="image" src="https://github.com/user-attachments/assets/bb55e063-0345-4439-a19f-79ef006be055" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
