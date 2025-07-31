# func_4
by using functions we are adding a 4 digit number
def dsum(n):
    if n==0:
        return 0
    return n%10 +temp(n//10)
def temp(n):
    return dsum(n)
num=int(input("Enter a 4 digit number:"))
print("sum of digits:",dsum(num))
