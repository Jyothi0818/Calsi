 operator=input("enter an operator(+ - * /): ")
a=int(input("enter A value:"))
b=int(input("enter B value :"))
if operator =="+":
    result=a+b
    print(result)
elif operator =="-"  :
    result=a-b
    print(result)
elif operator =="*" :
    result=a*b
    print(result)
elif operator=="/" :
   result=a/b
   print(result)

   print(f"The result is {result}")   
else :
   print(f"The {operator} is invalid!")   
