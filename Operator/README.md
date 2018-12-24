# Operator

Operator adalah simbol khusus yang biasa dilibatkan dalam program untuk melakukan suatu operasi
matematika maupun operasi logika


## Assignment Operators

Operator ini berfungsi memberikan sebuah nilai kepada variabel. Dengan menggunakan tanda = (_Sama Dengan_).  
Pemberian nilai ini selalu dimulai dari _Kanan_ ke _Kiri_. Dan tidak bisa sebaliknya.

contoh : 
```cpp  
x = 5;  
```
Pada pernyataan ini memberikan nilai integer 5 kedalam variabel x.  

contoh :   
```cpp  
x = y;  
```

Pada pernyataan ini memberikan nilai pada variabel y kedalam variabel x. Dan nilai yang ada di variabel x tadi hilang dan di gantikan nilai variable y.

## Arithmetic Operators

Operator ini digunakan untuk melakukan sebuah operasi perhitungan atau aritmatika dalam bahasa pemrograman. 
5 Operator Arithmetic pada C++ :

| Operator | Deskripsi   |
| -------- |:-----------:|
|    +     | Penjumlahan |
|    -     | Pengurangan |
|    *     | Perkalian   |
|    /     | Pembagian   |
|    %     | Sisa Bagi   |

Contoh Penggunaan Arithmetic Operator : 

```cpp
int a = 5;  
int b = 2;  

cout << a+b ; // Penjumlahan   
cout << a-b ; // Pengurangan  
cout << a*b ; // Perkalian  
cout << a/b ; // Pembagian  
cout << a%b ; // Sisa Bagi  
```

Output : 

```cpp
7  
3  
10  
2	// karena menggunakan tipe data int, maka ditampilkan 2 saja.  
1	// sisa bagi dari operasi 5:2  
```



## Compound Assignment

Compound Assignment ini merupakan penyederhanaan dari Arithmetic Operator.
Yang biasanya a = a + 1, disederhanakan dengan a += 1.


| Operator |      Keterangan      |        Contoh Penggunaan        |
| -------- | -------------------- | ------------------------------- |
|    +=    | Penjumlahan          | x += y sama dengan, x = x + z   |
|    -=    | Pengurangan          | x -= y sama dengan, x = x - z   |
|    *=    | Perkalian            | x *= y sama dengan, x = x * z   |
|    /=    | Pembagian            | x /= y sama dengan, x = x / z   |


## Increment & Decrement

Operator Increment (++) dan operator decrement(--) digunakan untuk menambahkan(increment)
atau mengurangi(decrement) satu nilai yang tersimpan dalam sebuah variabel.

Contoh :
 
1. Pre Increment (x++) , akan menambahkan nilai 1 sebelum operasi dijalankan. 
2. Post Increment (++x), akan menambahkan nilai 1 sesudah proses lain dijalankan.


## Relational & Comparison Operators

Operator relasi ini akan banyak digunakan dalam suatu statement bersyarat yang menghasilkan
nilai True atau False. Akan sering digunakan untuk menentukan kondisi.

| Operator |          Keterangan     |
| -------- | ----------------------- |
|    ==    |         Sama Dengan     |
|    !=    |     Tidak Sama Dengan   |
|    >     |         Lebih Dari      |
|    <     |         Kurang Dari     |
|    >=    |  Lebih Dari Sama Dengan |
|    <=    | Kurang Dari Sama Dengan |


## Logical Operators

Operator logika ini adalah operator yang digunakan untuk membandingkan dua nilai variabel
atau lebih. Hasil dari operasi ini adalah nilai boolean true atau false.

| Operator |                   Keterangan                   |
| -------- | ---------------------------------------------- |
|    &&    | AND - Jika semua operand bernilai benar (TRUE) |
|          | maka kondisi bernilai benar.                   |          
|    ||    | OR - Jika salah satu operand bernilai benar    |
|          | (TRUE) maka kondisi bernilai benar.            |
|    !     | NOT - Digunakan untuk membalik kondisi. Jika   |
|          | kondisi benar (TRUE) maka akan berubah menjadi |
|          | salah (FALSE), begitu pula sebaliknya.         |


## Conditional Ternary Operator



## Comma Operator



## Bitwise Operators