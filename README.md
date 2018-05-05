# CaesarCode
N = input()
L = len(N)
for i in range(L):
    A = ord(N[i])
    if A in [120,121,122]:
        B =[120,121,122].index(A)
        print(chr(97+B),end="")
    elif A in [88,89,90]:
        B=[88,89,90].index(A)
        print(chr(65+B),end="")
    elif A in [32]:
        print(chr(32),end="")
    else:
        print(chr(A+3),end="")
        
    
