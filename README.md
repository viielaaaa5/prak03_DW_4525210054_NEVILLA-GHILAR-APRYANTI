# Tugas Praktikum Pertemuan 3 - Desain Web

**Nama:** Nevilla Ghilar
**NPM:** [isi NPM kamu]
**Kelas:** [isi kelas kamu]

## Isi Tugas

Individu

1. Memodifikasi profil dengan menggunakan 10 property CSS inline dan 4 format warna yang berbeda.
2. Membuat Mini Style Guide yang berisi 2 opsi font, warna utama, warna aksen, ukuran heading, dan line height.

README berisi source code, hasil screenshot desktop, dan ringkasan kesimpulan 150–200 kata.

---

## File

| File             | Keterangan                               |
| ---------------- | ---------------------------------------- |
| `index.html`     | Halaman Curriculum Vitae                 |
| `style.css`      | File CSS untuk mengatur tampilan halaman |
| `ss-desktop.png` | Screenshot hasil tampilan pada desktop   |
| `README.md`      | Dokumentasi tugas                        |

---

## Source Code

### HTML

File `index.html` digunakan untuk membuat struktur halaman Curriculum Vitae, seperti profil, data diri, pendidikan, keahlian, minat, dan kontak.

```html
<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum Vitae</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header style="background: linear-gradient(to right, #89CFF0, #F1C6D7); padding: 30px; text-align: center;">

        <img
            src="LINK-FOTO"
            alt="Foto Profil"
            class="foto-profil"
            style="width: 130px; height: 130px; border: 4px solid rgb(255,255,255);">

        <h1 style="color: #37474F; font-size: 35px;">
            NEVILLA GHILAR
        </h1>

        <p style="color: rgba(55,71,79,0.9); font-size: 18px;">
            MAHASISWA TEKNIK INFORMATIKA
        </p>

    </header>

    <main>

        <section>
            <h2 style="color: #546E7A; border-bottom: 2px solid #90A4AE;">
                PROFIL
            </h2>

            <p style="font-size: 17px; line-height: 1.7;">
                Saya adalah mahasiswa Teknik Informatika yang memiliki
                ketertarikan pada bidang desain dan pengembangan website.
                Saya sedang mempelajari HTML, CSS, dan berbagai teknologi
                dalam bidang informatika.
            </p>
        </section>

        <section>
            <h2>DATA DIRI</h2>

            <p>Nama : Nevilla Ghilar</p>
            <p>Program Studi : Teknik Informatika</p>
            <p>Status : Mahasiswa</p>
            <p>Tahun Masuk : 2024</p>
        </section>

        <section>
            <h2>PENDIDIKAN</h2>

            <ul>
                <li>
                    <strong>2024 - Sekarang</strong><br>
                    S1 Teknik Informatika
                </li>

                <li>
                    <strong>2021 - 2024</strong><br>
                    SMA Negeri 1 Wanayasa
                </li>
            </ul>
        </section>

        <section>
            <h2>KEAHLIAN</h2>

            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>Desain Web</li>
                <li>Microsoft Office</li>
            </ul>
        </section>

        <section>
            <h2>MINAT</h2>

            <ul>
                <li>Desain Website</li>
                <li>Web Development</li>
                <li>Teknologi Informasi</li>
            </ul>
        </section>

        <section>
            <h2>KONTAK</h2>

            <p>
                Email :
                <a href="mailto:nevillaghilar@gmail.com">
                    nevillaghilar@gmail.com
                </a>
            </p>

            <p>
                Lokasi : Indonesia
            </p>
        </section>

    </main>

    <footer>
        <p>&copy; 2026 Nevilla Ghilar</p>
    </footer>

</body>
</html>
```

### CSS

File `style.css` digunakan untuk mengatur warna, ukuran tulisan, jarak, background, dan tampilan halaman.

```css
body {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16px;
    line-height: 1.6;
    background-color: #ECEFF1;
    color: #333333;
    margin: 0;
}

header {
    color: white;
}

header h1 {
    margin-bottom: 5px;
}

.foto-profil {
    border-radius: 50%;
    object-fit: cover;
}

main {
    width: 80%;
    margin: 25px auto;
    background-color: white;
    padding: 25px;
}

section {
    margin-bottom: 25px;
}

h2 {
    color: #546E7A;
    font-size: 22px;
    border-bottom: 2px solid #90A4AE;
    padding-bottom: 5px;
}

p {
    color: #37474F;
}

ul {
    line-height: 1.8;
}

a {
    color: #607D8B;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

footer {
    background: linear-gradient(to right, #546E7A, #78909C);
    color: white;
    text-align: center;
    padding: 10px;
}

footer p {
    color: white;
    font-size: 14px;
}
```

---

## 10 Property CSS Inline

| No | Property        | Contoh                 |
| -- | --------------- | ---------------------- |
| 1  | `background`    | `linear-gradient(...)` |
| 2  | `padding`       | `30px`                 |
| 3  | `text-align`    | `center`               |
| 4  | `width`         | `130px`                |
| 5  | `height`        | `130px`                |
| 6  | `border`        | `4px solid rgb(...)`   |
| 7  | `color`         | `#37474F`              |
| 8  | `font-size`     | `35px`                 |
| 9  | `border-bottom` | `2px solid #90A4AE`    |
| 10 | `line-height`   | `1.7`                  |

---

## 4 Format Warna yang Digunakan

| Format | Contoh               | Penggunaan         |
| ------ | -------------------- | ------------------ |
| HEX    | `#546E7A`            | Warna heading      |
| RGB    | `rgb(255,255,255)`   | Border foto        |
| RGBA   | `rgba(55,71,79,0.9)` | Warna teks profesi |
| HSL    | `hsl(0,0%,100%)`     | Warna putih        |

---

## Mini Style Guide

### Font

**Opsi 1:** Arial, Helvetica, sans-serif
Digunakan untuk isi halaman karena sederhana dan mudah dibaca.

**Opsi 2:** Georgia, Times New Roman, serif
Dapat digunakan untuk heading agar terlihat lebih formal.

### Warna Utama

`#546E7A` — digunakan untuk heading dan elemen utama.

### Warna Aksen

`#90A4AE` — digunakan untuk garis bawah heading dan elemen pendukung.

### Ukuran Heading

* H1: `35px`
* H2: `22px`

### Line Height

* Body: `1.6`
* Paragraf: `1.7`
* List: `1.8`

---

## Screenshot

### Hasil Tampilan Desktop

![Hasil Tampilan Desktop](ss-desktop.png)

---

## Ringkasan dan Kesimpulan

Pada tugas ini saya membuat dan memodifikasi halaman Curriculum Vitae menggunakan HTML dan CSS. HTML digunakan untuk membuat struktur halaman yang berisi profil, data diri, pendidikan, keahlian, minat, dan kontak. CSS digunakan untuk mengatur tampilan halaman seperti warna, ukuran teks, jarak, background, dan posisi elemen. Saya juga menerapkan CSS inline pada beberapa bagian HTML dengan menggunakan lebih dari sepuluh property CSS. Selain itu, terdapat empat format warna yang digunakan, yaitu HEX, RGB, RGBA, dan HSL. Penggunaan beberapa format warna tersebut membantu memahami bahwa CSS memiliki berbagai cara untuk menentukan warna. Pada bagian header saya menggunakan background gradient agar tampilan profil tidak terlalu polos. Saya juga membuat mini style guide yang berisi dua pilihan font, warna utama, warna aksen, ukuran heading, dan line height. Dari tugas ini saya menjadi lebih memahami hubungan antara HTML dan CSS dalam membuat sebuah halaman web. HTML digunakan sebagai struktur dasar, sedangkan CSS digunakan untuk memperindah dan mengatur tampilan halaman agar lebih nyaman dilihat.
