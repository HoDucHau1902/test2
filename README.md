name="Ho Duc Hau"
print(f'Plaintex: {name}')
import string
abc=list(string.ascii_lowercase)
p=17 
q=23
n=q*p
e=5
kq=[]
for i in name:
    if i in abc:
        kq+=[pow(abc.index(i),e,n)]
print(f'Ciphertext: {kq}')
