# Instagram
# cook your dish here
a=int(input())
for i in range(a):
    x,y=map(int,input().split())
    if x>(y*10):
        print("YES")
    else:
        print("NO")
