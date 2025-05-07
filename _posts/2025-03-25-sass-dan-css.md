---
layout: post
title:   SASS dan CSS
date: 2025-04-21
---

Penjelasan sass dan css

 Apa Itu CSS?

CSS (*Cascading Style Sheets*) adalah bahasa yang digunakan untuk mengatur tampilan dan format 
elemen dalam dokumen HTML Dengan CSS, pengembang web dapat menentukan warna, ukuran, posisi, tata letak, dan berbagai gaya visual lainnya untuk halaman web.
CSS berfungsi memisahkan konten (HTML) dari presentasi (tampilan), sehingga kode menjadi lebih bersih, terstruktur, dan mudah dikelola. CSS merupakan standar yang digunakan oleh semua browser modern.

Kelebihan CSS:

- Mudah digunakan dan dipelajari.
- Didukung secara luas oleh semua browser.
- Memisahkan desain dari struktur HTML.
- Dapat digunakan untuk styling responsif.

### Keterbatasan CSS:
- Tidak memiliki fitur pemrograman seperti variabel, perulangan, atau fungsi.
- Penulisan bisa menjadi repetitif pada proyek besar.
- Sulit untuk menjaga konsistensi dalam proyek skala besar tanpa bantuan eksternal.


## Apa Itu SASS?
SASS (Syntactically Awesome Stylesheets) adalah ekstensi dari CSS yang menambahkan fitur-fitur canggih seperti variabel, nested rules (aturan bertingkat), mixins, dan fungsi—yang tidak tersedia dalam CSS standar. Tujuannya adalah untuk memudahkan dan mempercepat penulisan CSS, terutama dalam proyek web yang besar dan kompleks.



SASS tidak menggantikan CSS, tetapi menambahkan lapisan tambahan untuk memudahkan penulisan dan pengelolaan file CSS, terutama dalam proyek berskala besar.

### Fitur Unggulan SASS:
- **Variabel:** Untuk menyimpan nilai yang digunakan berulang (seperti warna, ukuran, font).
- **Nesting:** Untuk menulis selector secara bertingkat mengikuti struktur HTML.
- **Partials & Import:** Untuk memecah file CSS menjadi modul kecil yang mudah dikelola.
- **Mixin:** Untuk membuat template kode yang bisa digunakan kembali.
- **Fungsi:** Untuk memproses dan menghasilkan nilai dinamis.
- **Perulangan & Logika:** Untuk membuat banyak aturan gaya secara efisien.
- **List & Map:** Untuk menyimpan dan mengelola data dalam struktur kompleks.


## Kapan Menggunakan CSS?

Gunakan **CSS biasa** jika:
- Anda membuat halaman statis yang sederhana.
- Proyek kecil dan tidak memerlukan pengelolaan style yang kompleks.
- Anda ingin menghindari proses kompilasi atau setup build tool.

## Kapan Menggunakan SASS?

Gunakan **SASS** jika:
- Anda mengelola proyek berskala besar dengan banyak halaman atau komponen.
- Anda ingin menggunakan fitur pemrograman untuk mempermudah pengelolaan style.
- Anda memerlukan struktur kode yang modular dan dapat digunakan kembali.



## Kesimpulan

CSS adalah dasar dari pengaturan tampilan web dan tetap penting untuk dipahami oleh semua pengembang web. Namun, untuk proyek yang lebih kompleks dan dinamis, SASS hadir sebagai alat bantu yang sangat kuat. 
Dengan fitur-fitur tambahan seperti variabel, nesting, dan mixin, SASS membuat penulisan CSS lebih terorganisir, hemat waktu, dan mudah dipelihara.

SASS bukan pengganti CSS, melainkan *alat bantu* yang meningkatkan cara kita menulis CSS. File SASS akan tetap dikompilasi menjadi CSS sebelum digunakan di browser. Karena itu, meng
<img src="/assets/images/-css-scss.jpg.webp" alt="html link dan lists" style="width: 300px;">