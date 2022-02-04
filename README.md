# START23C-
 CHFPROFIT
 
for i in range(int(input())):
    x,y,z=map(int,input().split())
    y1=x*y
    z1=x*z
    print(z1-y1)
    
    
    #  AVGOF3
    
    for i in range(int(input())):
    n=int(input())
    p,q,r=0,0,0
    n1=n*3
    if n1%2==0:
        p=1
        q=(n1//2)-1
        r=(n1//2)
    else:
        p=1
        q=(n1//2)-1
        r=(n1//2)+1
    print(p,q,r)
