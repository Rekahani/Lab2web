*Langkah-langkah HTML dan CSS Praktikum Web*

1. Buka text editor, VS Code sebagai editor. Kemudian klik **file** pilih **open folder**, buka folder yang tadi di clone (**Lab2Web**) buat file baru dengan nama `lab2_css_dasar.html` seperti berikut

![1.png](img/1.png)

2. Membuat dokumen HTML, seperti berikut

![102.png](img/102.png)

Selanjutnya buka pada browser untuk melihat hasilnya

![2.png](img/2.png)

3. Mendeklarasikan CSS Internal

Kemudian tambahkan deklarasi tag CSS Internal seperti contoh berikut masukkan tag CSS di dalam < head >

![103.png](img/103.png)

Selanjutnya buka kembali Browser untuk melihat Hasilnya

![3.png](img/3.png)

4. Menambahkan Inline CSS

Kemudian tambahkan deklarasi inline CSS di dalam Tag < p > seperti berikut.

![104.png](img/104.png)

Simpan kembali dan refresh kembali browser untuk melihat perubahannya

![4.png](img/4.png)

5. Membuat CSS Eksternal

Membuat file baru dengan nama style_eksternal.css 
Kemudian buatlah deklarasi CSS seperti berikut

![105.png](img/105.png)

Kemudian tambahkan < link > untuk merujuk file css yang sudah dibuat pada bagian < head >

![106.png](img/106.png)

Dan hasilnya refresh Browser kembali maka tag css yang dibuat tadi berfungsi untuk mengubah tampilan warna background dan ukuran padding.

![5.png](img/5.png)

6. Menambahkan CSS Selector

Untuk menggunakan selector ID dan Class. pada file CSS, dengan menggunakan kode tag sebagai berikut.

![107.png](img/107.png)

Kemudian hasilnya refresh kembali Browser maka tampilan bentuk web akan berubah seperti ini, dikarenakan kode tag tersebut mengubah bentuk tampilan warna background dengan padding kembali terhadap pada bagian yang telah diberi selector tersebut.

![6.png](img/6.png)

*Pertanyaan dan tugas*

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

```
Perbedaan jika dengan tag elemen h1 maka tag yang ber elemen h1 akan ikut berubah semua. namun jika menggunkan selector maka yang akan berubah hanya elemen yang di beri selector saja yang akan berubah.
```

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

```
Maka yang akan di tampilkan di browser yaitu yang secara internal karena masih pada elemen yang sama contoh nya kita membuat inline pada sebuah huruf.
```

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya!  ( < p id="paragraf-1" class="text-paragraf" > )

```
Maka yang akan di tampilkan di browser ialah dengan selector ID karena sudah ada selector id maka class tidak akan di tampilkan di browser contohnya kita membuat 2 selector maka di saat deklarasi CSS nya kita gunakan deklarasi background color maka yang tampil warna di browser adalah selector ID.
```
