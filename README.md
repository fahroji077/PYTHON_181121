# PYTHON_181121

1.
2.
3.
4. PROGRAM 

```y
judul = "MENCARI BILANGAN NGENAP"
print(judul.rjust(40))
print("-"*50)

bil = []

banyak = int(input("masukkan bilangan : "))

for i in range(banyak):
    masukan = int(input("masukan bilangan : "))
    bil.append(masukan)

print("\nbilangan genap : ")
for i in bil:
    if i % 2 ==0:
        print(i)
 ```
 ![image](https://user-images.githubusercontent.com/93015185/142428185-cae52db4-b75e-45b8-93d9-c5d27dc07b85.png)

6. PROGRAM MENCARI BILANGAN TERBESAR

```y
a = int(input('masukkan nilai a : '))
b = int(input('masukkan nilai b : '))
c = int(input('masukkan nilai c : '))


if a > b and a > c :
    print('yang terbesar',a)
elif b > a and b > c :
    print('yang terbesar', b)
else :
    print('yang terbesar', c)
```
![image](https://user-images.githubusercontent.com/93015185/142427850-bb821d67-390a-44ae-944c-171bf5bb80e4.png)
