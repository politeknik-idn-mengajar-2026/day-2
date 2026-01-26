# Day-2: Responsive Landing Page with Tailwind CSS 🚀

Pada hari kedua ini, saya meng-upgrade project biodata statis menjadi sebuah *Landing Page* yang modern dan responsif menggunakan **Tailwind CSS**. Fokus utama adalah memahami konsep *Utility-First CSS* dan *Responsive Design*.

## 📝 Deskripsi Project
Project ini terdiri dari tiga bagian utama yang dirancang untuk tampil maksimal di layar HP maupun Laptop:
- **Navbar:** Navigasi tetap (fixed) di bagian atas dengan bayangan (*shadow*) agar terlihat kontras.
- **Hero Section:** Bagian pembuka dengan teks ajakan (CTA) dan foto profil yang menggunakan efek animasi *blob* di latar belakang.
- **Keahlian Utama (Features):** Menggunakan sistem grid untuk menampilkan fokus skill (Frontend, Backend, dan IoT).

## 🛠️ Materi & Teknologi yang Digunakan
- **Tailwind CSS (via CDN):** Menggunakan kelas utility seperti `flex`, `grid`, `bg-blue-600`, dan `shadow-lg`.
- **Responsive Breakpoints:** Implementasi class `md:` untuk mengatur tata letak yang berbeda antara tampilan mobile dan desktop.
- **Google Fonts:** Mengintegrasikan font **Poppins** untuk tipografi yang lebih modern.
- **CSS Animations:** Menambahkan animasi halus pada latar belakang foto profil.

## 🚀 Cara Menjalankan Project
1. **Clone** repositori ini ke komputer lokal kamu.
2. Pastikan kamu memiliki koneksi internet (karena Tailwind dimuat melalui CDN).
3. Buka file `index.html` menggunakan browser atau ekstensi **Live Server** di VS Code.
4. Kamu juga bisa melihat versi live di **GitHub Pages** repositori ini.

## 📌 Point Penting Sebelum Mengambil Code
- **Struktur Gambar:** Pastikan terdapat file bernama `foto.jpg` di folder yang sama. Gambar telah diatur dengan class `object-cover` agar tetap rapi dalam bentuk kotak/persegi.
- **Z-Index:** Navbar menggunakan `z-50` agar tidak tertutup oleh foto profil saat halaman di-scroll ke bawah.
- **Kustomisasi:** Kamu bisa mengganti warna utama dengan mengubah class `text-blue-600` atau `bg-blue-600` sesuai dengan preferensi warnamu.

---
Dibuat dengan ❤️ oleh Faridz - Mahasiswa di Politeknik IDN.
