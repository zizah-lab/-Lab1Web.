# Praktikum 1 Web 

**Nama:** Azizah Rachmatania<br>
**Kelas:** I251B<br>
**NIM:** 312510159<br>

Dokumentasi proses pengerjaan Praktikum 1 mata kuliah Pemrograman Web<br>
Repository ini berisi latihan penggunaan tag-tag dasar HTML seperti:

-struktur dokumen,

-heading,

-paragraf,

-format teks,

-gambar,

-hyperlink,

-list, dan

-komentar.

## 1. Membuat Paragraf
Menambahkan dua paragraf menggunakan tag `<p>` ke dalam `index.html`. Setiap paragraf diberi komentar HTML (`<!-- ... -->`) sebagai penanda, sesuai instruksi praktikum. 

Paragraf pertama menjelaskan tentang mata kuliah Pemrograman Web, sedangkan paragraf kedua menjelaskan fungsi HTML dalam menyusun struktur dan konten halaman web.

![Kode Membuat Paragraf](Dokumentasi/1.%20Membuat%20Paragraf.png)
![Hasil Membuat Paragraf](Dokumentasi/1.%20Membuat%20Paragraf%20(hasil).png)

## 2. Menambahkan Judul, Memformat Teks, dan Menyisipkan Gambar
Tiga langkah digabung dalam satu tahap pengerjaan:
- **Heading**: menambahkan `<h1>Belajar Dasar HTML</h1>` sebagai judul utama sebelum paragraf pertama, dan `<h2>Paragraf pada HTML</h2>` sebagai subjudul sebelum paragraf kedua.
- **Format teks**: menerapkan tag `<b>` untuk teks tebal, `<i>` untuk miring, `<strong>` untuk teks penting, serta `<sub>` dan `<sup>` untuk menulis notasi seperti H₂O dan x².
- **Gambar**: menyisipkan logo menggunakan tag `<img>` dengan atribut `src`, `width`, dan `alt`, lalu mencoba mengubah nilai `width` untuk melihat perubahan ukuran tampilan gambar.

![Kode Judul dan Teks](Dokumentasi/2.%20Judul%20dan%20teks%20(hasil).png)
![Kode Judul, Teks, dan Gambar](Dokumentasi/2.%20Judul%20teks%20dan%20gambar%20.png)
![Hasil Gambar](Dokumentasi/3.%20gambar%20(hasil).png)

## 3. Menambahkan Hyperlink
Membuat file baru `halaman2.html` sebagai halaman kedua. Pada kedua file (`index.html` dan `halaman2.html`) ditambahkan elemen `<nav>` berisi tiga hyperlink:
- Link internal ke `index.html`
- Link internal ke `halaman2.html`
- Link eksternal ke `https://www.google.com`

Navigasi diuji langsung di browser dengan mengklik tiap link secara bergantian untuk memastikan perpindahan halaman berjalan dengan benar.

![Kode Hyperlink](Dokumentasi/6.%20Menambahkan%20Hyperlink.png)
![Hasil Hyperlink](Dokumentasi/6.%20Menambahkan%20Hyperlink%20(hasil).png)

## 4. Menambahkan Komentar
Menambahkan komentar HTML pada beberapa bagian kode sebagai penanda, misalnya sebelum bagian "Profil Mahasiswa" dan bagian "Keahlian". Komentar berguna untuk dokumentasi kode dan tidak akan ditampilkan di browser — hanya terlihat pada source code.

![Kode Komentar](Dokumentasi/7.%20Menambahkan%20Komentar.png)
![Hasil Komentar](Dokumentasi/7.%20Menambahkan%20komentar%20(hasil).png)

## 5. Menambahkan List
Membuat daftar keahlian menggunakan `<ul>` (unordered list) berisi HTML, CSS, dan JavaScript, serta daftar urutan belajar menggunakan `<ol>` (ordered list) yang berisi tahapan mempelajari struktur HTML hingga menguji halaman di browser.

![Kode List](Dokumentasi/8.%20Menambahkan%20List.png)
![Hasil List](Dokumentasi/8.%20Menambahkan%20List%20(hasil).png)

## 6. Menggabungkan Semua Elemen
Menyusun ulang `index.html` menjadi satu halaman utuh berjudul **Profil Mahasiswa**, menggabungkan seluruh elemen yang telah dipelajari: navigasi (`<nav>`), heading, gambar profil, paragraf data diri, unordered list untuk keahlian, dan ordered list untuk target belajar — disusun dalam struktur HTML yang lengkap dan rapi.

![Kode Bagian 1](Dokumentasi/9.%20Menggabungkan%20Semua%20Elemen%201.png)
![Kode Bagian 2](Dokumentasi/9.%20Menggabungkan%20Semua%20Elemen%202.png)
![Hasil Akhir](Dokumentasi/9.%20Menggabungkan%20Semua%20Elemen%20(hasil).png)

## Validasi HTML
Kedua file (`index.html` dan `halaman2.html`) divalidasi menggunakan [W3C Markup Validation Service](https://validator.w3.org). Hasil validasi menunjukkan kedua file **valid, tanpa error maupun warning**.

![Hasil Validasi](Dokumentasi/Hasil%20Setiap%20Validasi.png)
