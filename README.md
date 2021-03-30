# Praktikum 1 - Pemrograman WEB
<P> <B> Mochamad Amri Adrian Wiratama </B> </P> 
<P> <B> 311910226 </B> </P>
<P> <B> TI.19.A2 </B> </P>
<P> <B> Universitas Pelita Bangsa </B> </P>

# Langkah 1 

## Buka VS Code dan buat file HTML baru, setelah itu buat struktur HTML baru 
```
<!DOCTYPE html>
<html>
<head>
    <title></title>
</head>
<body>

</body>
</html>
```
![Langkah 1](https://user-images.githubusercontent.com/56380838/112936937-edebd900-9150-11eb-8d4e-e118f7614ca3.png)

# Langkah 2
## Membuat 2 paragraf dan atur paragraf dengan atribut ( Rata Kanan/ Rata Kiri/ Rata Tengah/ Rata Kanan & Kiri )
```
<!-- Ini adalah paragraf pertama -->
<p align="left">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="justify">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
 ```
 ![Langkah 2](https://user-images.githubusercontent.com/56380838/112937164-62267c80-9151-11eb-9174-f6772f1f37f1.png)
 # Langkah 3
 ## Menambahkan judul paragraf dengan menggunakan Tag Heading (H1, H2, H3, H4, H5, H6), Semakin besar angka Tag Heading semakin kecil ukuran huruf nya
 ```
 <!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
![Langkah 3](https://user-images.githubusercontent.com/56380838/112937451-dc570100-9151-11eb-868c-6a52b876844d.png)

<p> <b> Dan untuk yang di browser nya akan seperti ini </b> </p>

![Langkah 3 1](https://user-images.githubusercontent.com/56380838/112937463-df51f180-9151-11eb-96fd-eaf43aba2c8f.png)
# Langkah 4
## Memformat teks dengan menggunakan format teks yang ada
```
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```
![Langkah 4](https://user-images.githubusercontent.com/56380838/112939131-22619400-9155-11eb-99d4-ec05d6b50e9a.png)
![Langkah 4 1](https://user-images.githubusercontent.com/56380838/112939137-255c8480-9155-11eb-9597-594e2350517f.png)
# Langkah 5
## Menyisipkan Gambar dan mengatur ukuran gambar. Sebelum menyisipkan gambar, file HTML yg sudah dibuat dijadikan satu bersama dengan gambar yg akan disisipkan.
![Langkah 5](https://user-images.githubusercontent.com/56380838/112939407-9e5bdc00-9155-11eb-94ef-3df07698a2e1.png)
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="UPB1.png" width="200" title="Logo Univeritas Pelita Bangsa">
```
![Langkah 5 1](https://user-images.githubusercontent.com/56380838/112939840-5f7a5600-9156-11eb-9a0f-cf7480ee1301.png)
![Langkah 5 2](https://user-images.githubusercontent.com/56380838/112939846-62754680-9156-11eb-9967-222c7206d88c.png)
# Langkah 6
## Menambahkan Hyperlink
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```
![Langkah 6](https://user-images.githubusercontent.com/56380838/112940334-34dccd00-9157-11eb-9099-76b9e4ff9767.png)
![Langkah 6 1](https://user-images.githubusercontent.com/56380838/112940344-373f2700-9157-11eb-919b-c920afefa067.png)
# Langkah 7
## Cara menggabungkan halaman kedua dengan halaman pertama menggunkan Hyperlink
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag Halaman Dasar 2</title>
</head>
<body>
    <!-- Judul Paragraf pertama -->
    <h1> Belajar Tag Dasar </h1>
<p> <b>Ini adalah halaman kedua saya</b></p>
</body>
</html>
```
![Langkah 7](https://user-images.githubusercontent.com/56380838/112941549-f811d580-9158-11eb-851f-2cee6c25909f.png)
![Langkah 7 1](https://user-images.githubusercontent.com/56380838/112941558-fb0cc600-9158-11eb-9d93-0cefb5b91147.png)

# Pertanyaan :
1. Lakukan perubahan pada code sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag `<p>` dengan tag `<br>` berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai antribut tersebut?
# Jawab :
1. Ada eror ketika saya melakukan penulisan tag `<b>` tidak ditutup dnegan `</b>` maka tidak tulisan nya tidak tebal dan jadi seperti tulisan seperti biasa
2. Berbeda, kalau tag `<P>` jarak pragraf nya tidak terlalu jauh, sedangkan tag `<br>` dia paragraf nya longkap 1 line / baris
3. Kalau atribut `title` pada tag <img> fungsi nya untuk memberi judul pada gambar, sedangkan atribut `alt` pada tag <img> digunakan untuk memberi deskripsi pada gambar yg disisipkan
4. Kalau menurut saya, agar gambar tersebut tetap proporsional, cantumkan hanya salah satu atribut saja (width saja atau height saja, namun tidak keduanya). Misal kita ingin menampilkan gambar dengan menetatpkan widht 500px, maka web browser akan menampilkan gambar dengan lebar 500px dan menghitung otomatis tinggi gambar tersebut agar gambar tetap proporsional
5.
```
Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
```
