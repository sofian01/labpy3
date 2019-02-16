# labpy3

LATIHAN 1 "Program menampilkan n bilangan acak lebih < 0.5"

==>> Alur algoritma :

```
1. import random memanggil file random
2. n = int(input("masukkan nilai n : ")) input variabel n, tipe data integer
3. for i in range(n) : looping for, dengan jumlah perulangan sebanyak n
4. a=random.uniform(0.0,0.5) variabel a berisikan random angka dari 0.0 sampai 0.5
5. print ("data ke : ", i, "=> ", a) print data ke : i = index looping a = angka random sesuai syarat nomer 4
6. print("Selesai") print Selesai di luar looping
7. tampilkan hasil kelayar
```

==>> Kode python program :

```
print('|-----------------------------------------------|')
print('|PROGRAM MENAMPILKAN N BILANGAN ACAK LEBIH < 0.5|')
print('|-----------------------------------------------|')
print('')

import random

n = int(input("Masukan nilai N : "))
for i in range(n) :
    a=random.uniform(0.0,0.5)
    print ("Data ke : ", i, "=> ", a)
    
print("Selesai")
```

==>> Flowchart latihan1 :


![flowlat1](https://user-images.githubusercontent.com/43899109/52889329-f9b6f400-31b1-11e9-80da-4783dc6c7eca.jpg)


==>> Hasil screenshoot program :


![sslatihan1](https://user-images.githubusercontent.com/43899109/52889691-ae054a00-31b3-11e9-85cd-95ff605e8d6b.jpg)


LATIHAN 2 "Program menampilkan bilangan terbesar"


==>> Alur algoritma :

```
1. a=1 //variable a diisi 1, agar bisa masuk ke syarat while max=0 //variable max diisi 0
2. while a!=0 : looping while dengan syarat a bukan 0
3. if x > max : max = a proses if untuk mencari nilai terbesar
4. a = int(input("Masukan bilangan : ")) input nilai a dengan tipe data integer
5. if a == 0 : break jika inputan a diisi angka 0 maka break alias berhenti looping
6. print("Bilangan terbesar adalah : ",max) print nilai terbesar, variabel max
```

==>> Kode python proram :

```
print ('|-------------------------------------|')
print ('|PROGRAM MENAMPILKAN BILANGAN TERBESAR|')
print ('|-------------------------------------|')
print ('')

a=1
max=0
while a!=0:
    if a>max:
        max=a
    a=int(input('Masukkan bilangan :'))
    if a==0:
         break
        
print ('Nilai terbesarya adalah :',max)
```

==>> Flowchart latihan2 :


![flowlat2](https://user-images.githubusercontent.com/43899109/52889776-2704a180-31b4-11e9-99d2-047d6af3a17c.jpg)


==>> Hasil screenshoot program :


![sslatihan2](https://user-images.githubusercontent.com/43899109/52889802-397edb00-31b4-11e9-9176-12b4929bf618.jpg)


LATIHAN 3 ( Program 1 ) "Program menghitung laba pengusaha"


==>> Alur algoritma :

```
1. x=100000000 modal 100,000,000, variable x
2. sum=0 variable untuk menjumlah total laba
3. y=0 variable untuk masa bulan
4. lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2] 
	*variable untuk jumlah laba perbulan, 
 	dipisahkan dengan koma, tipe data integer
5. for i in lb : looping for indexs i, dengan mengambil data dari lb
6. sum=sum+i rumus untuk menghitung total laba perbulan
7. y+=1 masa bulan, tiap looping menambah 1
8. print("laba bulan ke-", y ,"sebesar :", i ) print : y = ambil masa bulan, i = ambil dari data yg ada di dalam lb
9. print("Total laba adalah :", sum) print total laba
10. tampilkan hasil kelayar 
```

==>> Kode python program :

```
x=100000000
sum=0
y=0
lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]
print('Modal awal seorang pengusaha        :',x)
for i in lb :
    sum=sum+i
    y+=1
    print('Laba bulan ke-', y ,'sebesar            :', i)

print('Total laba yang didapat adalah      :', sum)
```

==>> Flowchart program 1 :


![flowprogram1](https://user-images.githubusercontent.com/43899109/52889967-fbce8200-31b4-11e9-85f8-af522a2133ba.jpg)



==>> Hasil screenshoot program 1 :


![ssprogram1](https://user-images.githubusercontent.com/43899109/52889970-fbce8200-31b4-11e9-8865-6634c6099f42.jpg)
