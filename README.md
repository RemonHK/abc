a=(input("3 letras: "))
c=[]
b=len(a)
while b>0:
    c.append([])
    b=b-1
    if b==0:
        break
print(c)
c[0]=a[0]
c[1]=a[1]
c[2]=a[2]
print(c)
d=["0","a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p","q","r","s",
   "t","u","v","w","x","y","z","a"]
e=0
f=d[e]
while c[0]!=f[0]:
    e=e+1
    f=d[e]
    if c[0]==f[0]:
        e=e+1
        f=d[e]
        c[0]=f[0]
        e=0
        f=d[e]
        print(c)
        break
while c[1]!=f[0]:
    e=e+1
    f=d[e]
    if c[1]==f[0]:
        e=e+1
        f=d[e]
        c[1]=f[0]
        e=0
        f=d[e]
        print(c)
        break
while c[2]!=f[0]:
    e=e+1
    f=d[e]
    if c[2]==f[0]:
        e=e+1
        f=d[e]
        c[2]=f[0]
        e=0
        f=d[e]
        print(c)
        break
