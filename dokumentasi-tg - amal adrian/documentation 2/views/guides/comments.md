# **Penggambaran CSS**

> **CSS (Cascading Style Sheets)** adalah bahasa yang digunakan untuk menentukan tampilan dan format halaman web. CSS memungkinkan pemisahan konten (yang biasanya dibuat dengan HTML) dari presentasi visual, seperti warna, font, tata letak, dan lainnya. 

---

# **Dasar CSS**
**🔹 Sintaks Umum**
```CSS
selector {
  property: value;
}
```

## 📄 1. Selektor CSS
| Selektor | Fungsi | Contoh|
|----------|--------|-------|
| `*` |	Semua elemen|	`* {}`|
|`tag`|	Elemen HTML tertentu|	`p {}`|
|`.class`|	Berdasarkan class|	`.menu {}`|
|`#id`|	Berdasarkan id|	`#judul {}`|
|`tag1, tag2`|	Gabungan selektor|	`h1, h2 {}`|
|`tag.class`|	Tag dengan class tertentu|	`p.tebal {}`|
|`tag tag`|	Elemen di dalam elemen lain|	`div p {}`|

*📝 Gunakan selektor untuk menargetkan halaman tertentu*

## 🎨 2. Warna
```CSS
color: red;
background-color: #f4f4f4;
opacity: 0.8;
```
*📝 `color` untuk teks, `background-color` untuk latar belakang, `opacity` untuk transparansi.*

## 📐 3. Ukuran dan Spasi
```CSS
width: 300px;
height: 200px;
margin: 10px;
padding: 20px;
```
*📝 `margin` adalah jarak luar elemen, `padding` adalah jarak dalam, `width` adalah lebar, `height` adalah tinggi*

## 🖍️ 4. Teks dan Font
```CSS
font-size: 16px;
font-family: Arial, sans-serif;
font-weight: bold;
text-align: center;
text-decoration: underline;
```
*📝 `font-size` mengatur ukuran font, `font-family` mengatur jenis font, `font-weight` mengatur ketebalan font, `text-align` perataan, dan `text-decoration` mengatur garis teks.*

## 🧱 5. Border (Garis Pinggir)
```CSS
border: 2px solid black;
border-radius: 10px;
```
*📝 `border` mengatur ketebalan, jenis garis, dan warna. `border-radius` untuk sudut melengkung.*

## 📦 6. Display dan Box Model
```CSS
display: block | inline | inline-block | flex | grid;
box-sizing: border-box;
```
*📝 `display` mengatur tipe tampilan. `box-sizing: border-box` membuat padding tidak menambah ukuran elemen.*

## 📌 7. Positioning
```CSS
position: static | relative | absolute | fixed | sticky;
top: 10px;
left: 20px;
z-index: 2;
```
*📝 Mengatur posisi elemen relatif terhadap elemen lain atau layar.*

## 📏 8. Flexbox (Layout Fleksibel)
```CSS
display: flex;
flex-direction: row;
justify-content: space-between;
align-items: center;
gap: 10px;
```
*📝 Digunakan untuk menyusun elemen secara horizontal/vertikal dengan mudah.*

## 🔲 9. Grid (Layout Kotak-Kotak)
```CSS
display: grid;
grid-template-columns: repeat(3, 1fr);
gap: 20px;
```
*📝 Untuk layout kolom dan baris yang kompleks.*

## 🖼️ 10. Gambar
```CSS
width: 100%;
height: auto;
object-fit: cover;
```
*📝 `object-fit` menjaga rasio gambar tetap proporsional.*

## 🖱️ 11. Hover dan Transisi
```CSS
a:hover {
  color: red;
}

button {
  transition: all 0.3s ease;
}
```
*📝 Efek saat user hover elemen dan efek animasi perubahan properti.*

## ✨ 12. Animasi CSS
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.box {
  animation: fadeIn 1s ease-in;
}
*📝 Animasi sederhana tanpa JavaScript.*

## 📱 13. Responsif (Media Query)
@media (max-width: 768px) {
  body {
    font-size: 14px;
  }
}
*📝 Untuk menyesuaikan tampilan di perangkat kecil seperti HP/tablet.*

## 🛠️14. Variabel CSS (Custom Property)

```CSS
:root {
  --warna-primer: #007BFF;
}

h1 {
  color: var(--warna-primer);
}
```
*📝 Gunakan `--warna` untuk membuat warna atau ukuran reusable.*

## 🧽 15. Reset CSS (Untuk Awal Bersih)
```CSS
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```
*📝 Menghilangkan margin/padding default dari browser.*

# 🧪 **Contoh CSS Lengkap**

<div class="tab-container">
  <div class="tab-buttons">
    <button class="tab-button active" data-tab="code">Code View</button>
    <button class="tab-button" data-tab="image">Image View</button>
  </div>
   <div class="tab-content">
    <div class="tab-pane active" data-tab="code">

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <style>
    body {
      font-family: sans-serif;
      background-color: #f4f4f4;
      padding: 20px;
    }
  
    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
  
    .card:hover {
      transform: scale(1.03);
    }
  </style>
  
  <div class="card">
    <h2>Belajar CSS</h2>
    <p>Ini contoh card dengan gaya modern.</p>
  </div>
  
</body>
</html>
```
</div>
<div class="tab-pane" data-tab="image">

  ![Description of css image](../images/css.png)
</div>
</div>

