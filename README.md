# Ringkas Form

Plugin formulir WordPress yang ringkas: buat formulir tanpa kode, semua kiriman tersimpan
lengkap dengan statusnya, email lewat SMTP (Gmail/Google Workspace, MXroute, hosting, dll.),
dan pengunjung bisa langsung diarahkan ke WhatsApp. Cocok untuk tema Themify (ada modul
Themify Builder), dan tetap jalan di tema lain lewat shortcode.

Tidak perlu akun GitHub untuk mengunduh atau memakainya.

## Unduh

**[⬇ Unduh Ringkas Form versi terbaru (zip)](https://github.com/msusanto1981/ringkas-form-releases/releases/latest/download/ringkas-form.zip)**

Daftar semua versi beserta perubahannya ada di halaman
[Releases](https://github.com/msusanto1981/ringkas-form-releases/releases).
File "Source code (zip)" yang otomatis muncul di sana **bukan** plugin. Pakai `ringkas-form.zip`.

## Syarat

- WordPress 6.4 atau lebih baru
- PHP 8.1 atau lebih baru (cek di Alat → Kesehatan Situs → Info → Server)

## Cara pasang

1. Unduh zip di atas. Jangan diekstrak.
2. Di WordPress: **Plugin → Tambah Plugin Baru → Unggah Plugin**, pilih zip-nya, klik **Pasang Sekarang**,
   lalu **Aktifkan**.
3. Buka **Ringkas Form → Pengaturan** dan isi pengaturan email (SMTP). Pilih penyedia email
   Anda dari daftar, lalu klik tes koneksi.
4. Buat formulir di **Ringkas Form → Tambah formulir**. Bisa mulai dari template.
5. Pasang formulir di halaman: modul **Ringkas Form** di Themify Builder, atau shortcode
   `[ringkas_form id="…"]` yang tertera di daftar formulir.
6. Kirim satu formulir uji, lalu cek apakah emailnya masuk.

Pindah dari Contact Form 7? Di halaman **Formulir** ada tautan **Impor**. Formulir CF7 beserta
entri CFDB7 bisa dipindahkan dari sana.

## Pembaruan

Versi baru muncul sendiri di menu **Plugin** WordPress ("Pembaruan tersedia"), sama seperti
plugin lain. Agar terpasang otomatis, klik **Aktifkan pembaruan otomatis** pada baris Ringkas Form.

## Bantuan

Ada masalah atau saran? Hubungi orang yang membagikan plugin ini kepada Anda. Sertakan
versi WordPress, versi PHP, dan tangkapan layar pesan error-nya.

Lisensi: GPL-2.0-or-later.
