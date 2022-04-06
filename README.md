# mini-calculator-using-python
a=input("enter a number")
print("........operators are +,-,*,/,%........")
o=input("enter using operator")
b=input("enter a number")


a=int(a)
b=int(b)

if o=='+':
   print(a+b)
         
elif o=='-':
     print(a-b)
         
elif o=='*':
     print(a*b)
         
elif o=='/':
     print(a/b)
         
elif o=='%':
           print(a%b)
        
else:
    print("Invalid Error")
