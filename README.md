# 🔐 Aplikasi Form Pengaman Data Mahasiswa (AES-128 CBC secara manual  + Firebase)

Aplikasi mobile berbasis Flutter untuk mengamankan data pribadi mahasiswa menggunakan metode enkripsi **AES 128-bit mode CBC** yang diimplementasikan secara manual tanpa menggunakan library eksternal.

Data yang diinputkan pengguna akan dienkripsi di sisi **frontend**, lalu dikirim ke **Firebase Firestore**. Proses dekripsi hanya dapat dilakukan **di aplikasi (local)** — data yang tersimpan di Firebase tetap terenkripsi.

---

## 🎯 Tujuan Aplikasi

- Menyediakan form input data mahasiswa yang aman
- Menerapkan enkripsi AES CBC 128-bit manual
- Menyimpan hasil enkripsi ke Firebase Firestore
- Membuktikan bahwa data tetap aman saat transit dan tersimpan di server khususnya di databases

---

## 🧰 Teknologi yang Digunakan

| Komponen     | Teknologi                          |
|--------------|------------------------------------|
| Frontend     | Flutter (Dart)                     |
| Backend      | Firebase Firestore (NoSQL)         |
| Enkripsi     | AES 128-bit CBC (tanpa library)    |
| UI Form      | Flutter `TextFormField`, `Form`    |

---

## 📦 Fitur Aplikasi
- 📋 Form Login (username, dan password) ( secara default dan tidak disimpan di firebase)
- 📋 Form input data mahasiswa (Nama, NIM, Email, dsb)
- 🔐 Enkripsi data sebelum dikirim ke Firebase
- ☁️ Simpan hasil enkripsi ke Firestore
- 👀 Tampilkan data terdekripsi di aplikasi (tidak di server)
- 🛡️ Tanpa penggunaan `encrypt`, `crypto`, atau package lain

---

## 📁 Struktur Folder (Contoh)

