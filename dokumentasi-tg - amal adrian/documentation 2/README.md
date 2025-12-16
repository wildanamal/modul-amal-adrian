# 📘 **Apa Itu CSS??**
> **CSS (Cascading Style Sheets)**  adalah bahasa yang digunakan untuk mengatur tampilan visual sebuah website. Jika HTML diibaratkan sebagai kerangka atau struktur bangunan, maka CSS adalah bagian yang menentukan warna cat, ukuran ruangan, tata letak, dan dekorasi agar bangunan terlihat menarik dan nyaman dilihat.

# **Fungsi CSS**
> CSS memiliki peran yang cukup penting pada desain sebuah website karena berfungsi sebagai pengatur tampilan visual yang menentukan bagaimana sebuah halaman web dilihat dan dirasakan oleh pengguna. Dengan CSS, pengembang dapat mengubah halaman web yang awalnya sederhana menjadi lebih menarik, rapi, dan mudah digunakan. kalau misal gaada CSS nya sebuah webiste hanya akan terlihat teks dan elemen-elemen dasar.

**Fungsi-fungsi CSS diantaranya**
- Mengatur Warna dan Latar Belakang
  ```HTML 
  <style>
    body {
  background-color: lightblue;
    }
</style>

- Mengatur Teks dan Font
```HTML
<style>
    p {
      font-family: Arial;
      font-size: 16px;
      color: Black;
    }
</style>
```
- Mengatur jarak dan ukuran elemen
```HTML
<style>
  div {
  margin: 20px;
  padding: 10px;
}
</style>
```

- Mengatur Tata Letak (Layout)
```HTML
<style>
  .container {
  display: flex;
  justify-content: center;
}
</style>
```

- Membuat Tampilan Responsif
```HTML
<style> 
@media (max-width: 600px) {
  body {
    background-color: white;
  }
}
</style>
```
 
# **Contoh Penggunaan**
```HTML
<style>
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
</style>
```
<div class="contoh-container">
    <h1>My First CSS Example</h1>
    <p>This is a paragraph.</p>
</div>

<div class="tab-pane" data-tab="image">

  ![Description of paus image](images/css_gambar.jpg)
</div>


