# program-53
import math
a=float(input("enter the first coefficient:"))
b=float(input("enter the second coefficient:"))
c=float(input("enter the third coefficient:"))
if(a!=0.0):
d=(b*b)-(4*a*c)
if(d==0.0):
print("the roots are real and equal")
r=-b/(2*a)
print("the roots are",r,"and",r)
elif(d>0.0):
print("the roots are real and distinct")
r1=(-b+(math.sqrt(d)))/(2*a)
r2=(-b-(math.sqrt(d)))/(2*a)
print("the root1 is:",r1)
print("the root2 is:",r2)
else:
print("the root are imaginary:")
rp=-b/(2*a)
ip=math.sqrt(-d)/(2*a)
print("the root1 is:",rp,"+",ip)
print("the root2 is;",rp,"-",ip)
else:
print("not a quardartic equation")
Output:
enter the first coefficient:1
enter the second coefficient:4
enter the third coefficient:7
the root are imaginary:
the root1 is: -2.0 + 1.7320508075688772

the root2 is; -2.0 - 1.7320508075688772
