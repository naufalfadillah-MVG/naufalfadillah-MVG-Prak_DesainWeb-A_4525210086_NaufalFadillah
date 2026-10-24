# Mini Portofolio dan Website Arunika Studio

## Deskripsi

Folder ini berisi dua bagian, yaitu **contoh** dan **tugas**. Folder `contoh` berisi halaman mini portofolio pribadi menggunakan HTML dan CSS eksternal. Folder `Tugas` berisi website Arunika Studio yang dikembangkan dengan HTML dan CSS eksternal, termasuk penyesuaian tampilan untuk perangkat mobile.

## Struktur file

### 1. Contoh

- [`contoh/index.html`](./contoh/index.html) — struktur halaman mini portofolio pribadi.
- [`contoh/css/style.css`](./contoh/css/style.css) — pengaturan tampilan menggunakan CSS eksternal.
- [`contoh/css/images/fotosaya.jpeg`](./contoh/css/images/fotosaya.jpeg) — foto profil.
- [`contoh/dokumentasi/hasil.png`](./contoh/dokumentasi/hasil.png) — bukti tampilan halaman.
- [`contoh/dokumentasi/code1.png`](./contoh/dokumentasi/code1.png) dan [`contoh/dokumentasi/code2.png`](./contoh/dokumentasi/code2.png) — dokumentasi kode.
- [`contoh/dokumentasi/Readme.md`](./contoh/dokumentasi/Readme.md) — README yang tersedia di folder dokumentasi contoh.

### 2. Tugas

- [`Tugas/index.html`](./Tugas/index.html) — struktur halaman website Arunika Studio.
- [`Tugas/css/style.css`](./Tugas/css/style.css) — pengaturan tampilan, kartu layanan, tombol, navigasi, dan media query.
- [`Tugas/images/hasil website.png`](./Tugas/images/hasil%20website.png) — bukti tampilan website.
- [`Tugas/images/hasil1 mobile.png`](./Tugas/images/hasil1%20mobile.png) dan [`Tugas/images/hasil2 mobile.png`](./Tugas/images/hasil2%20mobile.png) — bukti tampilan pada perangkat mobile.
- `README.md` — dokumentasi untuk folder contoh dan tugas.

## Pemeriksaan kebutuhan

Kedua halaman menghubungkan CSS eksternal melalui elemen `<link rel="stylesheet">`. Pada folder `contoh`, halaman mini portofolio memuat bagian pengenalan, tentang saya, daftar proyek, kontak, navigasi, dan footer. CSS mengatur warna, jarak, foto profil, kartu proyek, serta efek hover.

Pada folder `Tugas`, website Arunika Studio memuat bagian Tentang Kami, Layanan Kami, Kontak, dan footer. CSS mengatur tata letak, navigasi, kartu layanan, tombol, warna, serta efek hover. Media query pada lebar layar maksimal 768 piksel digunakan untuk menyesuaikan tata letak agar lebih nyaman dilihat pada perangkat mobile.

## Ringkasan perubahan, masalah, dan solusi

Contoh mini portofolio menggunakan header dan navigasi, bagian pengenalan dengan foto profil, kartu proyek, informasi kontak, serta footer. CSS eksternal digunakan agar aturan tampilan terpisah dari struktur HTML dan lebih mudah dikelola.

Tugas Arunika Studio menerapkan konsep serupa untuk website studio kreatif. Halaman menampilkan informasi studio, tiga kartu layanan, kontak, dan tombol navigasi. Media query digunakan untuk mengubah susunan header dan kartu layanan pada layar kecil. File CSS harus tetap berada di lokasi `css/style.css` sesuai dengan alamat yang ditulis pada HTML. Jika file CSS atau gambar dipindahkan, jalur file pada HTML dan README perlu disesuaikan.

## Bukti tampilan

### Contoh mini portofolio

![Hasil tampilan mini portofolio](./contoh/dokumentasi/hasil.png)

### Tugas Arunika Studio

![Hasil tampilan website Arunika Studio](./Tugas/images/hasil%20website.png)

### Tampilan mobile

![Tampilan mobile pertama](./Tugas/images/hasil1%20mobile.png)

![Tampilan mobile kedua](./Tugas/images/hasil2%20mobile.png)

## Pengerjaan Tugas

Pengerjaan dilakukan dengan mempelajari contoh mini portofolio, memahami hubungan HTML dan CSS eksternal, kemudian menerapkan konsep tersebut pada website Arunika Studio. Setelah itu, tampilan diperiksa melalui hasil screenshot desktop dan mobile yang tersedia.