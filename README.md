# 400M-race
# cook your dish here
t = int(input())
for i in range(t):
    a = list(map(int, input().split()))
    b = ['alice', 'bob', 'charlie']
    print(b[a.index(min(a))])
