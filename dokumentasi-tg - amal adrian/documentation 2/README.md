# 📘 **gelo gua ganteng banget cuk**
# **Level 0 : Pengenalan**
## 👉🏻 **Definisi** 
> **CSS (Cascading Style Sheets)**  adalah bahasa yang digunakan untuk mengatur tampilan visual sebuah website. Jika HTML diibaratkan sebagai kerangka atau struktur bangunan, maka CSS adalah bagian yang menentukan warna cat, ukuran ruangan, tata letak, dan dekorasi agar bangunan terlihat menarik dan nyaman dilihat. 

## 🛠 **Fungsi CSS**
> CSS memiliki peran yang cukup penting pada desain sebuah website karena berfungsi sebagai pengatur tampilan visual yang menentukan bagaimana sebuah halaman web dilihat dan dirasakan oleh pengguna. Dengan CSS, pengembang dapat mengubah halaman web yang awalnya sederhana menjadi lebih menarik, rapi, dan mudah digunakan. kalau misal gaada CSS nya sebuah webiste hanya akan terlihat teks dan elemen-elemen dasar.

**Fungsi-fungsi CSS diantaranya**
- Mengatur Warna dan Latar Belakang
  ```css 
    body {
  background-color: lightblue;
    }
  ```

- Mengatur Teks dan Font
```css
    p {
      font-family: Arial;
      font-size: 16px;
      color: Black;
    }
```
- Mengatur jarak dan ukuran elemen
```css
  div {
  margin: 20px;
  padding: 10px;
}
```

- Mengatur Tata Letak (Layout)
```css
  .container {
  display: flex;
  justify-content: center;
}
```

- Membuat Tampilan Responsif
```css
@media (max-width: 600px) {
  body {
    background-color: white;
     }
}
```
 
<h3> Contoh Penggunaan </h3>

```css
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
```

<h3> Output </h3>

<div class="tab-pane" data-tab="image">

  ![Description of paus image](images/css_gambar.jpg)
</div>


## 📂 **Perbedaan HTML dan CSS**

> HTML dan CSS memiliki fungsi yang berbeda namun saling melengkapi. HTML bertugas menyusun struktur konten, sedangkan CSS bertugas mengatur tampilannya.
>
>Secara sederhana, perbedaan HTML dan CSS dapat dijelaskan sebagai berikut:
>- HTML digunakan untuk membuat elemen seperti judul, paragraf, gambar, dan tautan
>- CSS digunakan untuk mengatur warna, ukuran teks, jarak, dan tata letak elemen tersebut
>
>Dengan kata lain, HTML adalah kerangka website, sedangkan CSS adalah desain dan dekorasinya.


## 🔧 **Cara Kerja CSS**
>CSS bekerja dengan cara memberikan aturan tampilan pada elemen-elemen HTML. Saat sebuah halaman web dibuka, browser akan memproses HTML dan CSS secara bersamaan untuk menentukan bagaimana setiap elemen ditampilkan di layar. Proses ini tidak terjadi secara acak, tetapi melalui tahapan yang terstruktur.
>
>1. **Browser Membaca File HTML**, 
Browser terlebih dahulu membaca HTML untuk mengetahui struktur halaman, seperti judul, paragraf, dan gambar. Pada tahap ini, halaman masih belum memiliki tampilan khusus.
2. **Browser Mencari dan Membaca CSS**, 
Setelah itu, browser mencari CSS yang terhubung dengan HTML, baik dari inline, internal, maupun external CSS. Semua aturan CSS dikumpulkan sebelum diterapkan.
3. **CSS Memilih Elemen HTML (Selector)**, 
CSS menggunakan selector untuk menentukan elemen HTML mana yang akan diberi gaya, misalnya paragraf, class, atau id tertentu.
4. **CSS Menerapkan Aturan Tampilan**,
Browser menerapkan property dan value CSS pada elemen yang sudah dipilih, seperti mengatur warna, ukuran teks, atau jarak elemen.
5. **Prinsip Cascading pada CSS**, 
Jika ada beberapa aturan CSS untuk elemen yang sama, browser akan memilih aturan yang paling tepat berdasarkan prioritas dan urutan penulisan.
6. **Browser Menggabungkan HTML dan CSS**, 
Struktur HTML dan aturan CSS digabungkan sehingga tampilan visual halaman mulai terbentuk sesuai desain.
7. **Website Ditampilkan ke Pengguna**, 
Hasil akhir halaman web ditampilkan ke layar. Jika CSS diubah, browser akan memperbarui tampilan tanpa mengubah HTML.


# **Level 1 : Dasar CSS**
## 📖 **Struktur Dasar CSS**
