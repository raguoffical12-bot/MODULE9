
### EX: 9.4       TOEPLITZ MATRIX
### Aim: To Write a Python Program to check whether the given matrix is Toeplitz Matrix.


### Algorithm:
STEP 1: Start.

STEP 2: Create a variable r and c for rows and columns.

STEP 3: Get the value of r and c from user.

STEP 4: Define a function to create the matrix.

STEP 5 : Using the formula check for TOEPLITZ MATRIX .

STEP 6: Print the result.

STEP 7 : Stop.


### Program:
```
reg no:212223070021
name:Ragunandhan S
def create_matrix(n,m):
        M=[]
        for i in range(n):
                row=[]
        for j in range(m):
            x=int(input())
            row.append(x)
        M.append(row)
      return M
def print_matrix(M):
    for i in range(len(M)):
         for j in range(len(M[0])):
               print(M[i][j], end=' ')
     print()
def isThoeplitz(M):
#Type your code here
for i in range(len(M)):
      for j in range(len(M[0])):
             if i>0 and j>0 and M[i][j]!=M[i-1][j-1]:
                return False
       return True
n,m = input().split()
A = create_matrix(int(n),int(m))
print("A=",A)
if isThoeplitz(A):
      print(A,"is a Toeplitz Matrix")
 else:
       print(A,"is not a Toeplitz Matrix") print_matrix(A)
```
### Output:
![image](https://github.com/user-attachments/assets/50989d28-3a25-4e2a-bdf4-129d865426ff)

### Result: Thus, the given program is implemented and executed successfully.
