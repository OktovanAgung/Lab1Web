# Nama        : Oktovan Agung Shailendra
# NIM         : 312010131
# Kelas       : TI.20.A1
# Mata Kuliah : Pemrograman Web

## **Langkah- Langkah Praktikum**
persiapan membuka VSCode dan Browser.
![img](Img/IMG%20(1).png)

Kemudian buat file baru dengan nama **Lab1_tag-dasar.html** dan tambahkan tag dasar dokumen HTML.
![img](Img/IMG%20(2).png)

Selanjutnya buka file tersebut pada web browser, disini saya menggunakan **Opera.**
![img](Img/IMG%20(3).png)

## **1. Membuat Paragraf**
Buatlah paragraf sederhana seperti berikut, dan kemudian lihat hasilnya dengan merefresh pada web broser sebelumnya.
![img](Img/IMG%20(4).png)

Kemudain atur atribut paragraf seperti berikut dan lihat perubahannya
![img](Img/IMG%20(5).png)
Simpan dan refresh web browser untuk melihat perubahannya. selanjutnya ubah - ubah nilai atributnya (*align = justify, leftl right dan center*) untuk melihat perbedaannya.

## **2. Menambahkan Judul**
Judul memiliki 6 level yang berbeda mulai dari h1 sampai h6. Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub-judul h2 sebelum paragraf ke 2.
![img](Img/IMG%20(6).png)
Simpan dan lihat perubahannya.

## **3. Memformat Teks**
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teksm sehingga tampilannya seperti berikut
![img](Img/IMG%20(7).png)
Lakukan eksperimen lainnya dengan tag - tag pemformatan teks yang ada.

## **4. Menyisipkan Gambar**
Untuk menyisipkan gambar, siapkan gambar yang akan disisipkan dan taruh pada satu folder dengan file HTML., atau bisa juga menyisipkan gambar dari website eksternal.
![img](Img/IMG%20(8).png)
Kemudian tambahkan tag img setelah paragraf kedua, dengan menambahkan heading 3 sebelumnya.
![img](Img/IMG%20(9).png)
Gambar akan ditampilkan apa adanya sesuai ukuran aslinya. Untuk mengatur ukuran gambar, dapat digunakan atribit witdh dan height dengan nilai integer yang disesuaikan
![img](Img/IMG%20(10).png)

## **5. Menambahkan Hyper Link**
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut. Dan lihat hasilnya hasilnya.
![img](Img/IMG%20(11).png)

## **Jawab Pertanyaan Berikut**
1. Lakukan perubahan pada kode sesuai keinginan anda, amati perubahannya adakah *error* ketika terjadi kesalahan penulisan tag ?
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya !
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya !
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak ? Berikan penjelasanya !
5. pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing - masing nilai atribut tersebut ?

## **JAWABAN**
1. Saya akan melakukan perubahan pada tag HTML
sebelum perubahan
![img](Img/IMG%20(12).png)
Setelah perubahan
![img](Img/IMG%20(13).png)
Disini saya melakukan perubahan dengan menghilangkan akhiran pada Tag `</h1>` menjadi `<h1>`, maka yang akan terjadi seluruh elemen dibawah tag tersebut akan berubah mengikuti Tag `<h1>` dikarenakan tidak ada akhiran/penutup Tag tersebut.

2. Tag `<p>` berfungsi untuk memberi perintah paragraf pada halaman html
Tag `<br>` berfungsi untuk memberikan perintah breakline atau baris baru.
![img](Img/IMG%20(14).png)

3. `title` berfungsi untuk memberikan judul pada gambar, Sedangkan
`alt` berfungsi untuk menunjukkan sebuah alternate text (teks pengganti) yang akan muncul apabila gambar tidak dapat ditampilkan.
gambar dibawah ini menunjukan perbedaan title dan alt.
![img](Img/IMG%20(15).png)

4. Menurut saya tidak harus menggunakan keduanya karena jika menggunakan keduanya dengan ukuran angka yang sama ukuran gambar pada web tidak simetris, sedangkan jika hanya menggunakan salah satu ukutannya akan bertambah besar secara simetris. Comtoh seperti gambar dibawah :
![img](Img/IMG%20(16).png)

5.  `_blank` untuk membuka link di tab baru

    `_self` untuk membuka link di frame link itu berada

    `_top` untuk membuka link di frame paling atas (paling luar).  contohnya jika di website(1) di dalamnya ada website(2) lalu di website(2) di dalamnya ada website (3) lalu di website (3) ini ada link dan kita klik, maka link akan terbuka di website(1)

    `_parent` untuk membuka link di frame yang satu tingkat di atas frame link tersebut berada. contohnya jika di website(1) di dalamnya ada website(2) lalu di website(2) ini ada link dan kita klik, maka link akan terbuka di website(1)