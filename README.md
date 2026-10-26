# Portofolio Chahyo Kumolo Nugroho

Situs statis (HTML + gambar), tanpa build.

Deploy gratis ke GitHub Pages:

- Workflow GitHub Actions di `.github/workflows/pages.yml` menerbitkan situs otomatis setiap ada push ke branch `main`.
- Setelah workflow pertama selesai, situs tersedia di https://cahyokml.github.io/Portofolio-ChahyoKumoloNugroho/
- Jika deploy pertama belum berjalan otomatis, buka tab Actions di GitHub dan jalankan workflow "Deploy portfolio to GitHub Pages".
- Netlify Drop juga tersedia di https://app.netlify.com/drop untuk deploy manual.

Preview lokal: `npx serve .` lalu buka http://localhost:3000

Ganti teks atau gambar: edit index.html dan file di assets/images/.

Navigasi portfolio:

- Bagian Project memakai panel sticky bertumpuk dengan jarak yang cukup agar setiap project dapat dilihat sebelum panel berikutnya menutupinya. Gulir untuk beralih dari satu project ke project berikutnya; tombol "VIEW PROJECT" membuka detail proyek di tab baru.
- Detail proyek memuat deskripsi yang ringkas, kontribusi/temuan, teknologi, tiga gambar galeri, dan tautan yang tersedia. Daftar "Project Lainnya" berada di bawah galeri pada halaman detail. Gambar kedua dan ketiga adalah placeholder yang dapat diganti melalui daftar `images` di `index.html`.
- Tautan "Tentang" di navigasi membuka halaman baru dengan foto, profil, pendidikan, pengalaman, dan sertifikat.
- Halaman Tentang dan detail proyek menyediakan tautan kembali, tombol navigasi halaman, dan navigasi gestur/keyboard: geser atau tekan panah kiri untuk kembali ke beranda, dan geser atau tekan panah kanan untuk membuka project berikutnya.
- Bagian tools dan teknologi tampil di halaman utama setelah seluruh proyek; sertifikat tersedia di halaman Tentang.
