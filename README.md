# 2-3-2020
Assignment -1
A=[]
m=int(input('enter number of rows:'))
n=int(input('enter number of columns:'))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    A.append(row)
print(A)
B=[]
m=int(input('enter number of rows:'))
n=int(input('enter number of columns:'))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    B.append(row)
print(B)
result=[[0,0],[0,0]]
for i in range(m):
    for j in range(n):
        result[i][j]=A[i][j]-B[i][j]
print('resultant matrix is:')
for i in range(m):
    for j in range(n):
        print(result[i][j],end=' ')
    print()
