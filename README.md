fact=1
def factorial(num):
    global fact
    fact=1
    for i in range(1,num+1):
        fact*=i
    return fact
num=int(input("enetr a number"))
if num<0:
    print("cannot derive fact for -ve numbers:")
else:
    factorial(num)
    print(f"factorial of {num} is",fact)
