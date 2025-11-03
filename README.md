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
# Register No:25009613
# Developed By:GAUTAM P
# 1-Norm of a Matrix
<img width="913" height="306" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/ff6f2879-c134-409b-9149-b8ef7d630468" />

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
NORM_of_matrix="{:.1f}".format(ans)
print(NORM_of_matrix)



# 2-Norm of a Matrix
<img width="599" height="350" alt="Screenshot 2025-10-15 205333" src="https://github.com/user-attachments/assets/c66e2cab-52ae-4232-bcf4-8518184c695f" />

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
NORM_of_matrix="{:.2f}".format(ans)
print(NORM_of_matrix)



# Infinity Norm of a Matrix
<img width="1102" height="272" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/2b2f0dc7-108a-4dc2-a4fb-e1507b4eb728" />

import numpy as np
matrix=np.array(eval(input()))
infinity_norm=np.linalg.norm(matrix,ord=np.inf)
print(f"{infinity_norm:.2f}")




```
## Output:
### 1-Norm of a Matrix
<br>
<img width="809" height="202" alt="image" src="https://github.com/user-attachments/assets/cf6e5947-8f61-4df8-8b78-11179c62b1dc" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="751" height="360" alt="image" src="https://github.com/user-attachments/assets/8dc88881-968e-4d43-a5be-6724a3227723" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="807" height="248" alt="image" src="https://github.com/user-attachments/assets/2c3c82e0-af74-4cf6-bac6-8d51523e521b" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
