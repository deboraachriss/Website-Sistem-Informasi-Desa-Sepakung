# Website Pemerintah Desa Sepakung

Website informasi Pemerintah Desa Sepakung yang memuat informasi desa, publikasi, potensi wilayah, dan kanal komunikasi masyarakat. Proyek ini menggunakan PHP untuk halaman dan pemrosesan sisi server, serta aset gambar untuk mendukung penyajian informasi.

## Fitur yang terlihat pada source code

- Halaman informasi/beranda desa.
- Halaman informasi wisata dan potensi desa.
- Halaman aplikasi/informasi desa.
- Halaman kontak dan penyampaian kritik atau saran.
- Area administrator untuk pengelolaan konten dan administrasi.
- Penggunaan aset foto dan ilustrasi terkait desa.

> Catatan: daftar fitur di atas dirangkum dari file yang tersedia dalam repository. Fungsi yang membutuhkan database atau layanan eksternal perlu dikonfigurasi dan diuji kembali sebelum digunakan.

## Teknologi

- PHP
- HTML
- CSS
- JavaScript
- MySQLi (koneksi database pada beberapa file PHP)

## Struktur direktori

```text
Website-Desa-Sepakung/
├── FOTO/          # Aset foto dan gambar
├── PENGUNJUNG/    # Halaman untuk pengunjung
└── SEPAKUNG/      # Halaman dan fitur administrasi
```

## Menjalankan secara lokal

1. Pasang XAMPP atau lingkungan server lokal yang mendukung PHP dan MySQL.
2. Salin folder proyek ke direktori `htdocs`.
3. Siapkan database MySQL sesuai tabel yang dirujuk oleh file PHP.
4. Sesuaikan konfigurasi koneksi database pada file PHP dengan lingkungan lokal.
5. Jalankan Apache dan MySQL, kemudian buka halaman proyek melalui `http://localhost/Website-Desa-Sepakung/`.

## Catatan konfigurasi dan keamanan

- Arsip sumber yang diterima belum menyertakan file ekspor database `.sql`. Database dan struktur tabel perlu diekspor/dilengkapi sebelum instalasi dapat direproduksi secara utuh.
- Periksa dan sesuaikan kredensial database sebelum dipublikasikan. Jangan unggah password, token, atau data pribadi.
- Beberapa halaman PHP membutuhkan server PHP dan database; GitHub Pages tidak dapat menjalankan PHP. Repository ini berfungsi sebagai dokumentasi kode sumber, bukan hosting langsung aplikasi PHP.

## Pengembang

Proyek pengembangan website informasi desa.
