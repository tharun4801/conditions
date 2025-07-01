# if-else statement for number
num=int(input("enter the number:"))
if num%2==0:
    print(num,"is even")
else:
    print(num,"is odd")
OUTPUT:
enter the number: 45
45 is odd
#if-elif else statement for largest number of two a,b
a=int(input("enter the a:"))
b=int(input("enter the b:"))
if a>b:
    print("largest:",a)
elif a<b:
    print("largest:",b)
else:
    print("both are equal")
OUTPUT:
enter the a: 2
enter the b: 2
both are equal

#nested if for checking for the number is both pos and even
num=int(input("enter the number:"))
if num>=0:
    print("positive number")
    if num%2==0:
        print("even")
    else:
        print("odd")
else:
    print("number is negative")
OUTPUT:
enter the number: 56
positive number
even

    
