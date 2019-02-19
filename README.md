# labpy03

## APA ITU BAHASA PEMROGRAMAN PYTHON?

Bahasa pemrograman python adalah bahasa pemrograman tinggi yang dapat melakukan eksekusi sejumlah intruksi multiguna secara langsung (interpretatif) 
dengan metode orientasi objek (Object Oriented Programming) serta menggunakan sinematik dinamis untuk memberikan tingkat keterbacaan syntax. Sebagai b
ahasa pemrograman tinggi, python dapat dipelajari dengan mudah karena sudah dilengkapi dengan manajemen memori otomatis (pointer). Berikut saya akan 
menjelaskan mengenai langkah-langkah dan penjelasan programnya.

## ALUR ALGORITMA

Alur berpikir program, algoritma, dan tahapan pembuatan algoritma pemrograman terstruktur merupakan konsep dasar yang harus dipahami sebelum melakukan 
implementasi pada pembuatan program. Pada mulanya komputer adalah merupakan mesin penghitung (COMPUTER = To + COMPUTE + ER) yang digunakan
 untuk membantu dalam proses perhitungan. Secara umum proses yang dilakukan pada sebuah komputer adalah menerima data (masukan/input) kemudian nilai data 
diproses dalam pusat pengolahan data (aritmatika dan logika) kemudian hasil pengolahan tersebut dikeluarkan berupa data hasil pengolahan (keluaran/output). 
Komputer juga membutuhkan media penyimpanan data untuk melakukan proses sederhana tersebut. Algoritma adalah sekumpulan langkah-langkah terbatas untuk
 mencari solusi suatu masalah. Kata ini berasal dari kata algoris dan ritmis yang pada awalnya diungkapkan oleh Al Khowarizmi. Dalam pemrograman, algoritma didefinisikan
 sebagai metode yang terdiri dari langkah-langkah terstruktur untuk mencari solusi suatu masalah dengan bantuan komputer. Tahapan dalam menyelesaikan permasalahan menggunakan 
algoritma adalah terdiri dari tiga bagian yaitu menentukan permasalahan (idea), pemecahan masalah, solusi (hasil). Pada bagian pemecahan masalah terbagi menjadi tiga
 bagian lagi yaitu penyusunan algoritma, penulisan kode program (source code), dan terakhir mengeksekusi kode program untuk mengetahui hasil dari proses.

**Aplikasi PyChram**

Buka PyChram  terlebih dahulu, untuk mengetik program dan buat project baru. 

![1](https://raw.githubusercontent.com/Hadip31/labpy03/master/1.PNG)

## Latihan1

**Script Latihan1**

	import random
	jumlah=int(input("masukkan jumlah N : "))
	
	for i in range (jumlah):
		i=random.uniform(0.0,0.5)
		print("Data ke: =>",i)

	print("Selesai")

## Penjelasan program di atas seperti ini :
**Import Random** 

berfungsi untuk menentukan suatu pilihan juga mengembalikan bilangan float random x, dimana 0<x<1. Fungsi random() tidak memiliki parameter masukan.

![2](https://raw.githubusercontent.com/Hadip31/labpy03/master/2.PNG)

**Int** 

digunakan untuk mengambil data angka, juga bisa untuk menampilkan bilangan float random dengan batas awal bilangan x dan akhir bilangan y.

**For Loop** 

adalah perulangan for yang disebut counted loop (perulangan yang terhitung). Biasanya digunakan untuk mengulangi kode yang sudah diketahui banyak perulangannya. 
range() digunakan untuk membuat list dengan range yang kita tentukan dengan rentang nilai tertentu.

![3](https://raw.githubusercontent.com/Hadip31/labpy03/master/3.PNG)

**Print**

Fungsi Print adalah untuk mencetak atau menampilkan suatu objek ke perangkat keluaran (layar) atau ke file teks. 

![4](https://raw.githubusercontent.com/Hadip31/labpy03/master/4.PNG)

**Runn**

Kemudian kita Runn untuk meliat hasil project tersebut

![5](https://raw.githubusercontent.com/Hadip31/labpy03/master/5.png)

**Output**

Berikut hasil screenshot program Latihan1

![latihan1](https://raw.githubusercontent.com/Hadip31/labpy03/master/latihan1.PNG)

## Latihan2

**Script Latihan2**

	max = 0
	while True:
		a= int(input("masukkan Bilangan: "))
		if max < a:
			max = a
		if a==0:
			break
	print("Bilangan Terbesar : ",max)

## Penjelasan program di atas seperti ini :

**Max** 

digunakan untuk mencari nilai terbesar dari data yang telah di inputkan.

![6](https://raw.githubusercontent.com/Hadip31/labpy03/master/6.PNG)

**While Loop** 

adalah perulangan while yang disebut uncounted loop (perulangan yang tidak terhitung). Perulangan ini digunakan untuk perulangan yang memiliki syarat dan tidak tentu berapa banyak perulangannya.

**If** 

Statement digunakan untuk menjalankan suatu perintah dalam kondisi tertentu.

![7](https://raw.githubusercontent.com/Hadip31/labpy03/master/7.PNG)

**Break** 

digunakan untuk menghentikan proses perulangan jika kondisi yang kita inginkan telah tercapai.

![8](https://raw.githubusercontent.com/Hadip31/labpy03/master/8.PNG)

**Output**

Berikut hasil screenshot program Latihan2

![latihan2](https://raw.githubusercontent.com/Hadip31/labpy03/master/latihan2.PNG)

## Program1

**Script Program1**

	a=100000000
	for x in range(1,9):
		if(x>=1 and x<=2):
			b=a*0
			print("Laba bulan ke-",x," :",b)
		if(x>=3 and x<=4):
			c=a*0.1
			print("Laba bulan ke-",x," :",c)
		if(x>=5 and x<=7):
			d=a*0.5
			print("Laba bulan ke-",x," :",d)
		if(x==8):
			e=a*0.2
			print("Laba bulan ke-",x," :",e)
	total = b+b+c+c+d+d+d+e
	print("\nTotal : ",total)

## Penjelasan program di atas seperti ini :

**Variabel**

 x digunakan untuk menampung indeks. range(1,9) berfungsi untuk membuat list dengan range 1-10.

![9](https://raw.githubusercontent.com/Hadip31/labpy03/master/9.PNG)

**If** 

Statement digunakan untuk membuat perbandingan logis antara nilai dan apa yang di harapkan dengan menguji kondisi dan mengembalikan hasil jika True atau False.

![10](https://raw.githubusercontent.com/Hadip31/labpy03/master/10.PNG)

**Total** 

digunakan untuk membuat baris baru lalu mengakumulasikan hasil dari statement if yang telah berhasil di inputkan.

![11](https://raw.githubusercontent.com/Hadip31/labpy03/master/11.PNG)

**Output**

Berikut hasil screenshot program1

![program1](https://raw.githubusercontent.com/Hadip31/labpy03/master/program1.PNG)

# SELESAI