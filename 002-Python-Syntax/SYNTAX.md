# PYTHON SYNTAX

## Eksekusi Program Python

Untuk mengeksekusi program Python kita dapat menggunakan perintah pada terminal / commandline.
Pastikan terminal / command line sudah berada pada direktori yang diinginkan.

> C:\directory\folder python file.py

## Python Indentation

- Indentasi mengacu pada spasi yang berada diawal baris kode.
- Indentasi merupakan hal yang sangat penting untuk bahasa pemrograman Python, bukan hanya sebatas kode dapat mudah untuk dibaca.
- Indentasi pada Python menunjukan dimana letak sebuah blok kode.

```
if 5 > 2:
  print("Five is Greater than Two!")
```

_Kode akan eror jika tidak diberi indentasi_

```
if 5 > 2:
print("Five is Greater than Two!") --> ERROR
```

**Begitupun jika memiliki 2 statement lebih yang hendak dieksekusi**

```
if 5 > 2:
  print("Five is Greater than Two!")
  print("That is True!")
```

```
if 5 > 2:
  print("Five is Greater than Two!")
     print("That is True!") --> ERROR
```

## Python Variables

Variabel pada Python dibuat ketika nilai sudah ditetapkan

```
x = 5
y = "Hello World"
```

_Python merupakan bahasa pemrograman yang tidak memiliki 'keyword' atau 'command' untuk membuat sebuah variabel_

## Python Comments

Comments (Komentar) merupakan bagian penting dalam bahasa pemrograman.
Komentar dapat difungsikan sebagai catatan yang dibuat programer untuk tujuan dokumentasi.
Komentar memiliki perilaku berbeda dari kode yang dituliskan, dimana komentar tidak akan ikut dieksekusi oleh interpreter ketika kode dijalankan.
Untuk membuat komentar pada Python, dapat menggunakan tanda # (pawn/sign) sebagai penanda komentar dibuat

```
#This is Comment
print("Hello World!")
```
