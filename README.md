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
# Register No: 25017564
# Developed By: G.SANTHIYA
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print(norm)

# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: G.SANTHIYA
RegisterNumber: 25017590
'''
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")

# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,np.infty)
print(norm)

```
## Output:
### 1-Norm of a Matrix
<img width="1493" height="682" alt="Screenshot 2026-02-09 184511" src="https://github.com/user-attachments/assets/1f92e84c-e3ba-4305-b156-43d884e7a90f" />
<img width="1454" height="386" alt="Screenshot 2026-02-09 184522" src="https://github.com/user-attachments/assets/0fb9b2b1-c1de-4cb8-ab65-886d9ed6242b" />
### 2-Norm of a Matrix
<img width="1488" height="749" alt="Screenshot 2026-02-09 184532" src="https://github.com/user-attachments/assets/59dd8806-ea22-4f1a-9cbc-f9fb4c4e7a45" />
<img width="1471" height="430" alt="Screenshot 2026-02-09 184547" src="https://github.com/user-attachments/assets/a20f3e7c-81e3-4969-b2e1-51d77b4dc1b5" />
### Infinity Norm of a Matrix
<img width="1493" height="619" alt="Screenshot 2026-02-09 184558" src="https://github.com/user-attachments/assets/e57b47de-b158-4f20-8624-6ec904b4c68f" />
<img width="1490" height="372" alt="Screenshot 2026-02-09 184606" src="https://github.com/user-attachments/assets/5f3c3bc0-04b5-4222-bf5d-962f0f2d60a2" />
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
