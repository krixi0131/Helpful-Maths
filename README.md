# Helpful-Maths
a=str(input())
b=[]
for i in range(len(a)):
    if a[i]!="+":
        b.append(a[i])
b.sort()
print(b[0],end="")
for i in range(1,len(b)):
    print("+"+b[i],end="")
