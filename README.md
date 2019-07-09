# Armstrong-Number
a=input("enter a no.")
n=len(a)
b=[]
sum=0
def finds(x):
    y=int(x)
    return pow(y,n)
for i in range(len(a)):
    for j in range(1,2):
        b.append(finds(a[i]))

print(b)
for z in range(len(b)):
    sum=sum+b[z]
if sum==(int(a)):
    print("%d is a amstrong no."%sum)
else:
    print("%d is not an amstrong no."%sum)
