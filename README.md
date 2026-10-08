# Arunika Studio

Project Praktikum Desain Web dengan studi kasus pembuatan landing page Arunika Studio.

## Studi Kasus

Arunika Studio membutuhkan sebuah landing page sederhana yang dapat digunakan dengan nyaman pada perangkat desktop maupun mobile. Website ini digunakan untuk memperkenalkan Arunika Studio dan layanan yang ditawarkan.

Landing page terdiri dari beberapa bagian utama, yaitu header, hero section, bagian layanan, dan footer. Pada bagian layanan terdapat tiga layanan yang ditampilkan dalam bentuk card agar informasi lebih mudah dibaca oleh pengguna.

Masalah utama pada studi kasus ini adalah bagaimana membuat tampilan website yang tetap rapi pada ukuran layar yang berbeda. Selain itu, kode CSS perlu dibuat lebih terstruktur agar tidak terlalu banyak style yang ditulis secara berulang.

Untuk menyelesaikan masalah tersebut, website dibuat menggunakan HTML dan CSS yang dipisahkan menjadi dua file. CSS menggunakan beberapa class yang dapat digunakan kembali atau reusable class. Website juga menggunakan box model seperti margin, padding, border, dan border-radius.

Responsive design diterapkan menggunakan media query dengan batas ukuran layar 768px. Pada tampilan desktop, ketiga card layanan ditampilkan secara berjajar. Ketika ukuran layar lebih kecil, card layanan berubah menjadi satu kolom sehingga lebih mudah dibaca pada perangkat mobile.

## Tujuan

Tujuan dari pembuatan website ini adalah:

- Membuat landing page sederhana untuk Arunika Studio.
- Menerapkan struktur HTML yang terorganisir.
- Memisahkan kode HTML dan CSS.
- Menerapkan konsep box model.
- Menggunakan minimal dua class yang dapat digunakan kembali.
- Membuat tampilan website yang responsive.
- Menyesuaikan tampilan card layanan pada perangkat dengan ukuran layar yang lebih kecil.

## Struktur Website

Website Arunika Studio terdiri dari beberapa bagian utama.

### 1. Header

Header merupakan bagian paling atas dari website. Pada bagian ini terdapat nama atau identitas Arunika Studio serta menu navigasi.

Menu navigasi digunakan untuk membantu pengguna berpindah ke bagian tertentu pada halaman, seperti Home, Layanan, dan Kontak.

### 2. Hero Section

Hero section merupakan bagian utama yang pertama kali dilihat oleh pengguna ketika membuka website.

Bagian ini berisi judul utama, deskripsi singkat mengenai Arunika Studio, dan tombol yang mengarahkan pengguna untuk melihat layanan yang tersedia.

### 3. Layanan

Bagian layanan digunakan untuk menampilkan layanan yang ditawarkan oleh Arunika Studio.

Terdapat tiga layanan yang ditampilkan dalam bentuk card:

- Web Design
- UI/UX Design
- Branding

Setiap card memiliki struktur dan tampilan yang sama sehingga dapat menggunakan class CSS yang sama.

### 4. Footer

Footer merupakan bagian paling bawah dari website. Bagian ini digunakan untuk menampilkan informasi tambahan seperti nama Arunika Studio, email, dan copyright.

## Penerapan HTML dan CSS

HTML digunakan untuk membuat struktur halaman website, sedangkan CSS digunakan untuk mengatur tampilan halaman.

File yang digunakan dalam project ini adalah:

- `index.html` untuk struktur dan isi halaman.
- `CSS/style.css` untuk mengatur tampilan website.
- `README.md` untuk menjelaskan project.
- `output.jpeg` sebagai screenshot hasil tampilan website.

## Penerapan Box Model

Box model diterapkan pada beberapa elemen website. Properti yang digunakan antara lain:

- `margin` untuk memberikan jarak antar elemen.
- `padding` untuk memberikan ruang di dalam elemen.
- `border` untuk memberikan garis pada elemen.
- `border-radius` untuk membuat sudut elemen menjadi lebih halus.

Contoh penerapan box model digunakan pada card layanan sehingga setiap card memiliki jarak, ruang di dalam elemen, serta bentuk yang lebih rapi.

## Class Reusable

Pada project ini digunakan beberapa class reusable agar kode CSS lebih sederhana dan tidak ditulis berulang kali.

Contohnya adalah:

### `container`

Class `container` digunakan pada beberapa bagian website untuk mengatur lebar konten dan membuat posisi konten lebih rapi.

### `card`

Class `card` digunakan pada tiga layanan. Karena ketiga layanan memiliki bentuk dan tampilan yang hampir sama, satu class dapat digunakan untuk semuanya.

### `button`

Class `button` digunakan untuk mengatur tampilan tombol pada bagian hero.

Penggunaan class reusable membuat kode lebih mudah dibaca dan lebih mudah diperbaiki jika terdapat perubahan pada desain.

## Responsive Design

Website dibuat agar dapat menyesuaikan tampilan dengan ukuran layar pengguna.

Responsive design diterapkan menggunakan media query:

```css
@media (max-width: 768px)
