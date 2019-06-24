# basic-programcls


*************************salary increment by holding a single value*****************
n=list(map(int,input().split()))
m=min(n)
while True:
    x=n.index(len(n)):
    for i in range(len(n))):
        if i!=x:
            m[i]+=1
    if len(set(n)==1):
        print(n[0]-m)
        break

**************************bubble sort**********************

a=list(map(int,input().split()))
for i in range(len(a)):
    for j in range(len(a)-1):
        if(a[j]>a[j+1]):
            a[j],a[j+1]=a[j+1],a[j]
for i in range(len(a)):
    print(a[i],end=" ")
    
o/p:
    5 7 2 8 1
    1 2 5 7 8 
    
   *******************selection sort********************
a=list(map(int,input().split()))
for i in range(len(a)):
    min=i
    for j in range(i+1,len(a)):
        if(a[j]<a[min]):
            min=j
    a[i],a[min]=a[min],a[i]
for i in range(len(a)):
    print(a[i],end=" ")
        

o/p:
5 7 2 8 1
1 2 5 7 8 

**********************merge sort***********************




















