# check-prime-or-not
#Python program to check whether a number is Prime or not

n=int(input("Enter the number:"))
if n>1:
    if (n%2)==0:
        print("This is not prime number")
    else:
        print("This is prime number")
else:
    print("This is not prime number")
    
