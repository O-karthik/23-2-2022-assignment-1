# 23-2-2022-assignment-1
l=[]

s=0

n=int(input("enter range"))



for i in range(n):

    x=int(input("enter elements"))

    l.append(x)

max=min=l[0]

for i in range(1,n):

    if(l[i]>l[0]):

        max=l[i]

    if(l[i]<min):

            min=l[i]

print("maximum is" ,max)

print("minimum is",min)
