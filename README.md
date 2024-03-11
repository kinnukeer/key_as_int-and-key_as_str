# key_as_int-and-key_as_str
#key as int
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
print(d)

#key as str
d={}
n=int(input())
for i in range(n):
  k,v=input().split()
  d[k]=int(v)
print(d)
