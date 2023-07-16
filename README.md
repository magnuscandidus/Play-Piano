# Play-Piano
for _ in range(int(input())):
    a,b=map(int,input().split())
    count=0
    if(a>b):
        a,b=b,a
    while(a%3!=0 and b%3!=0):
        # Will do something here
        count+=1
        b=abs(a-b)
    print(count)
