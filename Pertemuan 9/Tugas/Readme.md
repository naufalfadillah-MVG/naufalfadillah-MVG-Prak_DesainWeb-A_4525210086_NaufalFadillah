# Laporan Praktikum Pertemuan 9 Membuat Dashboard Akademik dengan Bootstrap 5

## Deskripsi Tugas

Tugas praktikum ini bertujuan untuk membuat halaman Dashboard Akademik menggunakan HTML, CSS, dan Bootstrap 5 melalui CDN. Dashboard ini menampilkan informasi data mahasiswa, statistik jumlah mahasiswa, status mahasiswa, dan rata-rata IPK.

---

## Komponen dan Class Bootstrap yang Digunakan

1. **Bootstrap 5.3.8 via CDN**  
   Digunakan untuk membantu mengatur tampilan halaman menggunakan Bootstrap.

2. **Sistem Grid**  
   Menggunakan `container`, `row`, `col-md-8`, `col-md-4`, `col-12`, `col-md-6`, dan `col-lg-3` untuk mengatur posisi elemen agar responsif.

3. **Kartu Statistik**  
   Menggunakan class `card`, `card-body`, dan `h-100` untuk menampilkan informasi jumlah mahasiswa, mahasiswa aktif, mahasiswa cuti, dan rata-rata IPK.

4. **Tabel**  
   Menggunakan `table`, `table-hover`, `align-middle`, dan `table-responsive` untuk menampilkan data mahasiswa.

5. **Class Utilitas Bootstrap**  
   Menggunakan beberapa class seperti `text-white`, `text-secondary`, `text-success`, `text-warning`, `text-primary`, `fw-bold`, `py-4`, `my-5`, dan `mb-4`.

6. **Badge**  
   Menggunakan `badge`, `text-bg-success`, `text-bg-warning`, dan `text-bg-danger` untuk membedakan status mahasiswa.

7. **Tombol**  
   Menggunakan class `btn` untuk tombol Mahasiswa Baru dan tombol Lihat pada tabel.

8. **CSS Custom**  
   Menggunakan file `css/style.css` untuk mengatur warna background, header, footer, kartu statistik, dan tabel.

---

## Hasil Tampilan (Screenshot)

Berikut merupakan hasil tampilan Dashboard Akademik pada beberapa ukuran layar.

### 1. HP (375px) – Tampilan Mobile

![Tampilan HP 1](images/hasil%20hp1.png)

![Tampilan HP 2](images/hasil%20hp2.png)

### 2. Laptop – Tampilan Desktop

![Tampilan Laptop](images/hasil%20laptop.png)

---

## Penjelasan Perubahan, Masalah, dan Solusi

- **Masalah:** Tampilan dashboard pada layar HP memiliki ukuran yang lebih kecil dibandingkan laptop.

  **Solusi:** Menggunakan Bootstrap Grid dengan class `col-12`, `col-md-6`, dan `col-lg-3` agar kartu statistik menyesuaikan ukuran layar.

- **Masalah:** Kartu statistik perlu disusun agar terlihat rapi pada berbagai ukuran layar.

  **Solusi:** Menggunakan kombinasi class Bootstrap seperti `row` dan `g-4` untuk mengatur posisi serta jarak antar kartu.

- **Masalah:** Tabel memiliki banyak kolom sehingga berpotensi melebar pada layar HP.

  **Solusi:** Menggunakan `table-responsive` agar tabel dapat digeser secara horizontal ketika ukuran layar tidak mencukupi.

- **Masalah:** Tampilan status mahasiswa perlu dibedakan agar mudah diketahui.

  **Solusi:** Menggunakan badge dengan warna berbeda, yaitu hijau untuk Aktif, kuning untuk Cuti, dan merah untuk Nonaktif.

- **Masalah:** Tampilan halaman membutuhkan pembeda antara bagian atas, isi, dan bagian bawah.

  **Solusi:** Mengatur warna header menggunakan hijau, background halaman menggunakan abu-abu muda, dan footer menggunakan warna abu-abu gelap melalui CSS.

---

## Kesimpulan

Dari praktikum ini, saya dapat memahami penggunaan Bootstrap 5 untuk membuat Dashboard Akademik yang responsif. Dengan menggunakan sistem grid, card, tabel, badge, dan CSS tambahan, halaman dapat menyesuaikan tampilan pada perangkat HP maupun laptop.