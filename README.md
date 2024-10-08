 Nama                    | NIM        | Kelas   | Matkul            |
|-------------------------|------------|---------|-------------------|
| Luthfi Nur Alfian | 312310420 | TI.23.A4| Pemrograman Web 1 |

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

![alt text](https://github.com/Reval2703/Lab2Web/blob/main/Screenshot%202024-10-07%20115131.png)

Disisni saya mengubah warna dan hover dibagian nav nya menjadi hitam dan hovernya menjadi warna orange lalu mengubah link selengkapnya menjadi tombol yang mempunyai hover.

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!


Perbedaannya adalah jika hanya menuliskan h1 saja tanpa adanya # itu tandanya elemen h1 tersebut tidak diberikan id, jika #intro h1 itu tadanya elemen tersebut mempunyai sebuah id
CONTOHNYA :

![alt text](https://github.com/Reval2703/Lab2Web/blob/main/Screenshot%202024-10-07%20115451.png)

Semua tulisan h1 akan berwarna blueviolet, tetapi jika tulisan #intro yang akan brown karena gaya yang lebih spesifik dari #intro h1

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

Yang akan muncul hasilnya adalah inline css karena mempunyai prioritas tertinggi antara external atau internal
CONTOH: 

![alt text](https://github.com/Reval2703/Lab2Web/blob/main/Screenshot%202024-10-07%20120016.png)

contoh css:

![alt text](https://github.com/Reval2703/Lab2Web/blob/main/Screenshot%202024-10-07%20120437.png)

Maka hasilnya yang keluar adalah:

![alt text](https://github.com/Reval2703/Lab2Web/blob/main/Screenshot%202024-10-07%20120525.png)

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

Ketika html mempunyai deklarasi seperti id dan class maka akan muncul pada hasilnya adalah id karena spesifisitas id lebih tinggi 
CONTOH: 

![alt text](https://github.com/Reval2703/Lab2Web/blob/main/Screenshot%202024-10-07%20120639.png)

CONTOH CSS NYA:

![alt text](https://github.com/Reval2703/Lab2Web/blob/main/Screenshot%202024-10-07%20120810.png)

Hasil akhirnya: 

![alt text](https://github.com/Reval2703/Lab2Web/blob/main/Screenshot%202024-10-07%20120843.png)
