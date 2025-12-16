# 📘 **Penggambaran HTML**
> **HTML (HyperText Markup Language)** adalah bahasa dasar untuk membuat struktur halaman web. HTML menggunakan tag untuk menandai bagian-bagian tertentu pada sebuah halaman.

---
# 🧩 **Struktur Dasar HTML**

```HTML
<!DOCTYPE html>
<html>
<head>
    <title>Judul Halaman</title>
</head>
<body>
    <h1>Halo Dunia!</h1>
    <p>Ini adalah paragraf pertama saya.</p>
</body>
</html>
```
**Penjelasan Struktur di Atas:**

- `<!DOCTYPE html>`: Mendeklarasikan tipe dokumen HTML5

- `<html>`: Elemen root dari halaman

- `<head>`: Berisi informasi halaman (tidak ditampilkan di browser)

- `<title>`: Judul halaman (muncul di tab browser)

- `<body>`: Isi utama halaman (yang terlihat oleh user)

# 🏷️ **Elemen & Properti HTML Penting**
## 1. Heading (`<h1> sampai <h6>`)

```HTML
<h1>Judul Besar</h1>
<h2>Judul Sub</h2>
<h3>Judul Kecil</h3>
```
*📌 Heading digunakan untuk struktur konten. Gunakan `<h1>` untuk judul utama dan turunannya sesuai urutan penting.*

## 2. Paragraf (`<p>`)

```HTML
<p>Ini adalah teks paragraf.</p>
```
*📌 Gunakan paragraf untuk menulis teks biasa.*

## 3. Link (`<a>`)
```HTML
<a href="https://www.google.com">Kunjungi Google</a>
```
*📌 Properti `href` menentukan tujuan tautan.*

## 4. Gambar (`<img>`)
```HTML
<img src="gambar.jpg" alt="Deskripsi Gambar" width="300">
```
*📌 Gunakan `src` untuk lokasi gambar dan `alt` sebagai deskripsi.*

## 5. List (Daftar)
**Unordered List (bullet):**
```HTML
<ul>
  <li>Kopi</li>
  <li>Teh</li>
</ul>
```
**Ordered List (bernomor):**
```HTML
<ol>
  <li>Pertama</li>
  <li>Kedua</li>
</ol>
```
*📌 Gunakan `ul` untuk daftar biasa, `ol` untuk yang bernomor.*

## 6. Tabel (`<table>`)
```HTML
<table border="1">
  <tr>
    <th>Nama</th>
    <th>Usia</th>
  </tr>
  <tr>
    <td>Bayu</td>
    <td>22</td>
  </tr>
</table>
```
*📌 Gunakan tabel untuk menampilkan data tabular.*

## 7. Formulir (Form)
```HTML
<form action="/submit" method="post">
  <label for="nama">Nama:</label>
  <input type="text" id="nama" name="nama">
  <input type="submit" value="Kirim">
</form>
```
*📌 Digunakan untuk mengambil input dari user.*

## 8. Button
```HTML
<button>Click Saya!</button>
```
*📌 Digunakan untuk interaksi seperti submit, aksi JavaScript, dsb.*

## 9. Penggunaan `<div>`
**Contoh Penggunaan `<div`> (Blok Besar)**
```HTML
<div style="background-color:lightblue; padding:10px;">
  <h3>Judul Artikel</h3>
  <p>Ini isi artikel di dalam sebuah div.</p>
</div>
```
*📌 Penjelasan: `div` ini membungkus judul dan paragraf jadi satu bagian, dan diberi warna latar.*

## 10. Penggunaan `<span>`
**Contoh Penggunaan `<span>`**
```HTML
<p>Saya suka <span style="color:red;">HTML</span> karena mudah dipelajari.</p>
```
*📌 Penjelasan: `span` hanya memberi warna pada teks HTML, tanpa memengaruhi struktur paragraf.

## 📚 Properti Global HTML (umum di semua elemen)

| Properti | Kegunaan |
|----------|----------|
|`id`|	Identfikasi unik|
|`class`|	Kelompokkan elemen (CSS/JS)|
|`style`|	Tambahkan CSS langsung |
|`title`|	Tooltip saat hover|
|`hidden`|	Sembunyikan elemen|

# 👨‍💻 **Contoh Singkat Struktur Website**

<div class="tab-container">
  <div class="tab-buttons">
    <button class="tab-button active" data-tab="code">Code View</button>
    <button class="tab-button" data-tab="image">Image View</button>
  </div>
   <div class="tab-content">
    <div class="tab-pane active" data-tab="code">

```HTML
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Contoh Web</title>
</head>
<body>

  <header>
    <h1>BelajarHTML.com</h1>
  </header>

  <nav>
    <a href="#beranda">Beranda</a>
    <a href="#tentang">Tentang</a>
    <a href="#kontak">Kontak</a>
  </nav>

  <main>
    <section id="beranda">
      <h2>Selamat Datang!</h2>
      <p>Ini adalah halaman beranda.</p>
    </section>

    <section id="tentang">
      <h2>Tentang Kami</h2>
      <p>Kami adalah tim pengajar HTML.</p>
    </section>

    <article>
      <h2>Artikel Terbaru</h2>
      <p>Belajar HTML itu mudah dan menyenangkan.</p>
    </article>

    <aside>
      <h3>Artikel Populer</h3>
      <ul>
        <li><a href="#">Dasar CSS</a></li>
        <li><a href="#">JavaScript Mudah</a></li>
      </ul>
    </aside>
  </main>

  <footer>
    <p>© 2025 BelajarHTML.com - Semua Hak Dilindungi</p>
  </footer>

</body>
</html>
```
</div>
<div class="tab-pane" data-tab="image">

  ![Description of html image](../images/strukturweb.png)
</div>
</div>

**🎯 Penjelasan Struktur**
- `<header>` = Logo atau judul halaman

- `<nav>` = Menu navigasi

- `<main>` = Area utama konten (wajib satu per halaman)

- `<section>` = Blok khusus, biasanya berdasarkan topik

- `<article>` = Konten mandiri seperti postingan

- `<aside>` = Info tambahan (samping konten)

- `<footer>` = Hak cipta, kontak, atau link tambahan