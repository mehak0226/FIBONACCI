# FIBONACCI
no=int(input("length of fibonacci series"))
count=2
i=0
j=1
print(i)
print(j)
while(count<=no):
    k=i+j
    print(k)
    j=k
    i=j
    count+=1
