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
# Register No:212224100024
# Developed By:Jayaharshini s
# 1-Norm of a Matrix
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat, 1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat, 2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat, np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br><img width="985" height="933" alt="Screenshot 2025-09-18 090508" src="https://github.com/user-attachments/assets/caa75383-261c-4d09-8478-fec277e2c6d6" />

<br>

### 2-Norm of a Matrix
<br>
<br><img width="950" height="960" alt="Screenshot 2025-09-18 090521" src="https://github.com/user-attachments/assets/7c768e6c-8737-4ec6-b457-13e337c112ee" />

<br>

### Infinity Norm of a Matrix
<br>
<br><img width="819" height="942" alt="Screenshot 2025-09-18 090531" src="https://github.com/user-attachments/assets/74056360-7fe1-4536-abb7-27aefbe7cf81" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
