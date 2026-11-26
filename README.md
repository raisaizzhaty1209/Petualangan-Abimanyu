# Petualangan Pintar — Kelas 1 SD

Website kuis interaktif untuk latihan belajar kelas 1 SD. Dibuat sebagai satu file HTML agar mudah dipublikasikan melalui GitHub Pages.

## Isi
- 6 mata pelajaran: Bahasa Indonesia, Matematika, Bahasa Inggris, IPAS, Pendidikan Pancasila, dan Pendidikan Agama Islam.
- 5 soal latihan per mata pelajaran.
- Umpan balik jawaban, skor, bintang, dan progres tersimpan di browser perangkat menggunakan localStorage.
- Responsif untuk ponsel dan komputer.
- Tidak memerlukan login, server, atau database.

## Menjalankan di komputer
Buka `index.html` dengan browser (Chrome, Edge, Firefox).

## Menerbitkan dengan GitHub Pages
1. Masuk ke https://github.com dan buat akun jika belum punya.
2. Klik tombol **New repository**.
3. Beri nama repository, misalnya `petualangan-pintar`, pilih **Public**, lalu klik **Create repository**.
4. Pada halaman repository, pilih **Add file → Upload files**.
5. Unggah `index.html` (dan README.md jika diinginkan), lalu klik **Commit changes**.
6. Buka **Settings → Pages**.
7. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
8. Pilih branch **main** dan folder **/(root)**, lalu klik **Save**.
9. Tunggu beberapa menit. Alamat situs biasanya menjadi:
   `https://USERNAME.github.io/petualangan-pintar/`
   Ganti `USERNAME` dengan nama akun GitHub milikmu.

## Mengubah soal
Buka `index.html` dengan editor teks (misalnya VS Code atau Notepad). Bank soal berada pada bagian JavaScript di dalam `const subjects`. Setiap soal memiliki urutan:
1. Teks pertanyaan
2. Jawaban benar
3. Pilihan 1
4. Pilihan 2
5. Pilihan 3
6. Pilihan 4
7. Pembahasan singkat

Catatan: materi adalah contoh latihan umum kelas 1 dan perlu dicocokkan dengan urutan materi/buku yang digunakan sekolah. Jika mengubah pilihan jawaban, pastikan jawaban benar juga tersedia di antara empat pilihan.
