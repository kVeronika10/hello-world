a=float(input())
b=float(input())
c=float(input())
k=float(input())
if b==0 or a==0 or a+b+c*(k-a/b**3)==0:
    print ("ошибка")
else:
    print (abs((a**2/b**2+c**2*a**2)/(a+b+c*(k-a/b**3))+c+(k/b-k/a)*c))
