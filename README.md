n=input()
r=0
c=len(n)
while n:
    s=n%10
    r=r*10+s**c
    n=n//10
if(n==r):
    print("True")
else:
    print("False")# palindrome
