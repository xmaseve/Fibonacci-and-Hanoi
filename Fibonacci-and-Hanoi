# -*- coding: utf-8 -*-



def fi(x):
    a = 1
    b = 1
    while (x-2) > 0:
        a, b = b, a+b
        x -= 1
    return b
    
def f2(x):
    if x == 1 or x == 2:
        return 1
    else:
        return f2(x-1) + f2(x-2)

def hanoi(n,x,y,z):
    if n == 1:
        print x, '->', z
    else:
        hanoi(n-1, x, z, y)
        print x, '->', z
        hanoi(n-1, y, x, z)
hanoi(4,'x','y','z')


    



        
