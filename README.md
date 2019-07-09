# Armstrong-Number

a=input("enter a no.") # variable taking input
n=len(a)
b=[]
sum=0
def finds(x):  # method to find the value of individual varible
    y=int(x)
    return pow(y,n)
for i in range(len(a)):
    for j in range(1,2):
        b.append(finds(a[i]))      # Calling the find() method

print(b)
for z in range(len(b)): 
    sum=sum+b[z]
if sum==(int(a)):            # loop to check wheather the no. is armstrong or not
    print("%d is a amstrong no."%sum)
else:
    print("%d is not an amstrong no."%sum)
