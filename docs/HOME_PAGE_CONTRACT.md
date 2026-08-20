# Home Page Contract — Ngepas Builder Library

## Tujuan layar
Dalam 15 detik, pengunjung paham bahwa ini tempat belajar programming lewat analogi sederhana dan tahu harus mulai dari mana.

## Route
`/`

## Pengguna utama
Pemula yang sedang bingung dengan konsep programming, tetapi ingin belajar sambil membangun sesuatu.

## Susunan halaman
1. Navigasi publik: logo, Learn, Paths, Projects, My Learning, dan pencarian.
2. Hero: pesan “Mulai dari yang bikin lu bingung.”
3. Pencarian lesson: mengarah ke `/learn?q=kata-kunci`.
4. Tombol utama: “Mulai jalur pertama” menuju `/learn`.
5. Tombol kedua: “Lihat peta belajar” menuju `/paths`.
6. Kartu tiga level: Fundamental, Intermediate, dan Expert.
7. Kartu “Lanjutkan belajar” yang membaca progress lokal pengguna.

## Data yang dibutuhkan
- Daftar lesson published.
- Progress lesson dari penyimpanan lokal perangkat.
- Lesson terakhir yang dibuka.

## State penting
- Loading: tampilkan indikator saat daftar lesson belum siap.
- Empty: jelaskan jika belum ada lesson tersedia.
- Error: beri pesan refresh jika lesson gagal dimuat.

## Kriteria selesai
- Halaman nyaman dibaca di layar HP.
- Pencarian menghasilkan halaman Learn Hub yang terfilter.
- Tombol utama dan kedua punya tujuan jelas.
- Progress lokal tampil tanpa login learner.

## Di luar scope V0
- Login learner.
- Pembayaran.
- Editor kode interaktif.
- Rekomendasi materi dengan AI.
