# day-3
A=list(map(int,input().split()))
A.sort()
m=max(A)
for i in range(1,m+2):
    if i not in A:
        print(i)
        break
