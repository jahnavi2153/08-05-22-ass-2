# 08-05-22-ass-2
#Write a program to store yes for perfact square keys and no for other from 1 to 1000
l=[]
d={}
n=int(input())
for i in range(n):
    x=int(input())
    l.append(x)
y=1 
for i in l:
    if i<=1000:
        if 1000==i*i:
           d[i]='Yes'
        else:
           d[i]='No'
print(d)
