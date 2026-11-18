# Cricket Jakarta — Athlete Hub

Aplikasi online: https://tukangolahraga.github.io/ArsipCricketJakarta/

Portal Pelatih untuk satu klub dan Portal Litbang untuk database seluruh klub. Versi ini mencakup foto atlet, riwayat tes dan radar per sesi, statistik pertandingan, kehadiran, sasaran/tindak lanjut, saran latihan berbasis aturan tes, serta konfirmasi simpan dan tarik data.

## Penggunaan

Masuk menggunakan username dan kata sandi akun portal. Alamat backend Google sudah dikonfigurasi. Pengiriman dianggap berhasil setelah DATA TERKONFIRMASI; Litbang menekan Tarik data terbaru untuk memperbarui tampilannya. Demo hanya memuat data sintetis dalam memori sesi dan tidak menulis ke database nyata.

Saran latihan merupakan draf untuk ditinjau pelatih, belum norma bakat atau program otomatis.

## Penyimpanan dan akses

GitHub Pages menyajikan antarmuka statis. Data nyata tetap berada pada backend Google yang mengautentikasi akun dan membatasi klub. Repository ini tidak memuat kata sandi akun, isi spreadsheet, backup atlet atau alat pemulihan administrator. URL backend dalam HTML merupakan alamat layanan, bukan kredensial akses. Jangan menyimpan rahasia atau data atlet dalam repository ini.

Jika jaringan gagal, jangan menutup halaman sebelum retry atau ekspor backup. Sesi pending belum merupakan antrean offline permanen. Data aplikasi riwayat lama tidak dimigrasikan otomatis; gunakan backup dan impor yang disetujui Litbang.

## Publikasi

index.html adalah build mandiri dengan CSS, JavaScript, ilustrasi dan ikon tertanam. Tidak memerlukan instalasi paket atau CDN. Publikasi memakai konfigurasi GitHub Pages repository yang sudah ada. Berkas PCI.jpeg lama dipertahankan.

## Aset

Logo PCI DKI Jakarta disediakan pengelola. Foto ilustrasi: Andrew Yu / Unsplash, https://unsplash.com/photos/2TvMbrXKalQ, https://unsplash.com/license. Ikon Lucide/Feather menggunakan lisensi ISC/MIT yang disertakan dalam komentar HTML.
