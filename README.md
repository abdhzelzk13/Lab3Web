# Lab3Web

**Nama:** Abid Hazel Zaki  
**Kelas:** I.25.3A  
**Prodi:** Teknik Informatika

## Membuat Dokumen HTML

![Gambar 1](Screenshot/Membuat%20Dokumen%20HTML.png)

## Mendeklarasikan CSS Internal

![Gambar 2](Screenshot/Mendeklarasikan%20CSS%20Internal.png)

## Menambahkan Inline CSS

![Gambar 3](Screenshot/Menambahkan%20Inline%20CSS.png)

## Membuat CSS Eksternal

![Gambar 4](Screenshot/Menambahkan%20CSS%20Eksternal.png)

## Menambahkan CSS Sseelector

![Gambar 5](Screenshot/Menambahkan%20CSS%20Selector.png)

# Pertanyaan dan Tugas Praktikum CSS

## 1. Eksperimen Mengubah dan Menambah Properti CSS

Eksperimen dilakukan dengan mengubah properti CSS seperti `color`, `background-color`, `font-size`, `padding`, `margin`, dan `border` untuk melihat perubahan tampilan halaman web.

Contoh kode CSS:

```css
body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
}

h1 {
    color: blue;
    text-align: center;
}
```

## 2. Perbedaan Selector `h1` dan `#intro h1`

Selector `h1` digunakan untuk mengatur semua elemen heading tingkat satu. Sementara itu, selector `#intro h1` hanya mengatur elemen `h1` yang berada di dalam elemen dengan ID `intro`.

## 3. Prioritas CSS Internal, Eksternal, dan Inline

CSS inline umumnya memiliki prioritas lebih tinggi daripada CSS internal dan eksternal jika ketiganya mengatur properti yang sama dalam kondisi normal.

Contoh:

```html
<p style="color: red;">Belajar CSS</p>
```

Teks akan berwarna merah karena menggunakan CSS inline.

## 4. Prioritas ID Selector dan Class Selector

ID selector memiliki spesifisitas lebih tinggi daripada class selector apabila keduanya mengatur properti yang sama dan tidak ada aturan lain yang mengubah hasil cascade.

Contoh:

```html
<p id="paragraf-1" class="text-paragraf">
    Contoh paragraf CSS
</p>
```

```css
#paragraf-1 {
    color: red;
}

.text-paragraf {
    color: blue;
}
```

Teks akan berwarna merah karena ID selector memiliki spesifisitas lebih tinggi daripada class selector.

# Kesimpulan

Praktikum ini mempelajari penggunaan CSS internal, inline, dan eksternal serta penggunaan selector elemen, ID, dan class untuk mengatur tampilan halaman HTML.

