# Faris Priadi — Landing Page Simple Professional Blue

Website statis 1 file (`index.html`) yang siap dipasang di GitHub Pages.

## Tema desain

- Latar utama: putih (`#FFFFFF`)
- Teks utama: navy gelap (`#1B2B42`)
- Teks pendukung: abu-abu kebiruan (`#52647A`)
- Biru aksen dan tombol: `#1B5CA8`
- Bagian alternatif: putih keabu-abuan (`#F8FAFC`)
- Kartu layanan: putih dengan border lembut, tanpa gradasi mencolok

## Preview

Buka `index.html` memakai Chrome, Edge, atau Firefox. Tersedia contoh gambar `desktop-preview-simple-blue.png` dan `mobile-preview-simple-blue.png`.

Website sudah diuji pada ukuran desktop (1440 px) dan mobile (390 px): tidak ada overflow horizontal, dan navigasi serta tombol contoh kode berfungsi.

## Kontak hanya melalui WhatsApp

Tidak ada formulir kontak atau database. Semua tombol konsultasi diarahkan ke WhatsApp, dengan pesan pembuka yang berbeda untuk jalur Belajar Coding, Bedah Kode, dan konsultasi umum.

**Sebelum publikasi:**

1. Buka `index.html` di editor teks.
2. Cari: `const WHATSAPP_NUMBER = "";`
3. Isi nomor WhatsApp Anda memakai kode negara, tanpa tanda `+` dan tanpa nol depan, misalnya `const WHATSAPP_NUMBER = "628xxxxxxxxxx";` dengan `x` diganti digit nomor Anda.
4. Simpan dan uji semua tombol kontak.

Sebelum nomor diisi, tombol akan menampilkan pemberitahuan mode preview dan **tidak** mengarahkan pengunjung ke nomor lain.

Ubah teks pesan pembuka di variabel `whatsappMessages` apabila diperlukan.

## Publikasi GitHub Pages

1. Buat atau buka repository `farispriadi.github.io` pada akun GitHub yang sesuai.
2. Unggah `index.html` ke direktori root repository.
3. Buka **Settings → Pages → Build and deployment**.
4. Pilih **Deploy from a branch**, branch **main**, folder **/(root)**, lalu **Save**.
5. Akses alamat GitHub Pages setelah terbit.

## Catatan

- Tanpa framework, build tools, CDN, server, tracking, atau database.
- Bagian contoh proyek masih berupa ilustrasi materi, bukan karya siswa tertentu.
- `index.html` adalah file yang digunakan untuk publikasi.
