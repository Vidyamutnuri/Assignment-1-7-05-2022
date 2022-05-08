# Assignment-1-7-05-2022
Assignment-1
n=int(input())
l=[]
d={}
for i in range(n):
    x=int(input())
    l.append(x)
for i in l:
    if i%2==1:
        d[i]='yes'
    else:
        d[i]='no'
print(d)
