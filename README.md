x=int(input("enter the first number"))
c=str(input("+,-,*,/"))
y=int(input("enter the second number"))

if c=="x":
    print("the sum of x and y",x+y)
elif c=="-":
    print("the diffrence of c and y is",x-y)
elif c=="*":
    print("the product of x and y is",x*y)
elif c=="/":
    print("the division of x and y is",x/y)
elif c==("**"):
    print("the exponent of x and y is",x**y)
else:
    print("invalid operation")

