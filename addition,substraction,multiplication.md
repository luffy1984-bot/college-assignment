import numpy as np
A=np . array([[1,2,],
              [3,4]])
B=np . array([[5,6,],
              [7,8]])  
c=A+B
print('matrix A:')
print(A)

print('matrix B:')
print(B)

print('addition of two Matrices:')
print(c)

c=A-B

print('substraction of two matrices:')
print(c)

c=A@B

print('multiplication of two matrices:')
print(c)
