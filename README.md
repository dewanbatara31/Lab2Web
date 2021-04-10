# Lab2Web

1.	Membuat dokumen HTML

![image](https://user-images.githubusercontent.com/56387936/114257177-41c7af00-99e8-11eb-8335-a665423ec47f.png)

Selanjutnya buka pada brwoser untuk melihat hasilnya.
![image](https://user-images.githubusercontent.com/56387936/114257222-7fc4d300-99e8-11eb-8e91-0e0cc22f86c9.png)

2.	Mendeklarasikan CSS Internal 
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen
![image](https://user-images.githubusercontent.com/56387936/114257252-c4506e80-99e8-11eb-9675-47aa3610b972.png)

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.
![image](https://user-images.githubusercontent.com/56387936/114257276-04175600-99e9-11eb-9757-54369118434c.png)

3.	Menambahkan Inline CSS 
Kemudian tambahkan deklarasi inline CSS pada tag seperti berikut.
![image](https://user-images.githubusercontent.com/56387936/114257330-75570900-99e9-11eb-9948-07044d2c3ed0.png)

Simpan kembali dan refresh kembali browser untuk melihat perubahannya.
![image](https://user-images.githubusercontent.com/56387936/114257370-c7982a00-99e9-11eb-8ef7-a5e936c4caa1.png)

4.	Membuat CSS Eksternal
 Buat file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.
![image](https://user-images.githubusercontent.com/56387936/114257413-18a81e00-99ea-11eb-8dc0-3bc806e53191.png)

Kemudian tambahkan tag untuk merujuk file css yang sudah dibuat pada bagian
![image](https://user-images.githubusercontent.com/56387936/114257453-54db7e80-99ea-11eb-99cc-30f12e3ef519.png)

Selanjutnya refresh kembali browser untuk melihat perubahannya.
![image](https://user-images.githubusercontent.com/56387936/114257483-9704c000-99ea-11eb-972b-5bd52e23f4a7.png)

5.	Menambahkan CSS Selector 

Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kode berikut.

![image](https://user-images.githubusercontent.com/56387936/114257539-cfa49980-99ea-11eb-9520-49e1699e2019.png)

Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.

![image](https://user-images.githubusercontent.com/56387936/114257889-17c4bb80-99ed-11eb-9036-b02f8da47a1a.png)

Pertanyaan dan Tugas

1.	Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini. 
2.	Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya! 
3.	Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! 
4.	Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (  < p id="paragraf-1" class="text-paragraf" > )

Jawab :

1.	Jadi dalam eksperimen saya .. saya menambah <body bgcolor="#ff9966"> ini untuk supaya background dapat berwarna semua hingga memenuhi layar computer dan seperti inilah hasil gambarnya : 

2. Elemen h1 {...} yang dideklarasikan pada CSS mengacu pada style atau gaya teks saja yang ada di halaman awal web (sebagai header) atau memberi style CSS pada elemen HTML yang diingikan. Elemen h1 {...} mengacu pada Internal CSS yaitu menyisipkan CSS pada file HTML. sedangkan lemen #intro h1 {...} memiliki id maka penggunaan pada css dengan pagar (#) dan di dalam file index.html dalam pemanggilannya menggunakan id=" ". Elemen tersebut mengacu pada tampilan selector yang terdiri dari ID dan Class dimana ID selector ditandai dengan tanda pagar (#) di depannya.

3. 	Jadi yang akan muncul di browser itu adalah CSS internal karena Kode CSS internal diletakkan di dalam bagian pada halaman HTML. Class dan ID bisa digunakan untuk merujuk pada kode CSS, namun hanya akan aktif pada halaman tersebut (hanya 1 halaman). CSS internal diletakkan di dalam tag < style></style >.

