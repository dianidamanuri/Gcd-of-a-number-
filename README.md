# Gcd-of-a-number-
def getgcd(a,b):
    r=a%b
    if r==0:
        return b
    return getgcd(b,r)
a,b=map(int,input().split())
print(getgcd(a,b))

