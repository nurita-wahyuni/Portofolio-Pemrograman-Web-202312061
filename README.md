# Portofolio Pemrograman Web - 202312061

Repositori ini adalah kumpulan hasil kerja saya selama praktikum Pemrograman Web, dari Modul 1 hingga Modul 7, sebagai bagian dari pembangunan portofolio digital pribadi.

---

## 📑 Daftar Isi

1. [Deskripsi Proyek](#🧾 deskripsi-proyek)
2. [Prasyarat](#✅ prasyarat)
3. [Setup Proyek](#⚙️ setup-proyek)
   - [Modul 1-3 - Struktur Awal](#modul-1-3---struktur-awal)
   - [Modul 4-6 - Pengembangan Berkelanjutan](#modul-4-6---pengembangan-berkelanjutan)
4. [Struktur Folder](#🗂️ struktur-folder)
5. [Penutup] (#penutup)

---

## 🧾 Deskripsi Proyek

Pada praktikum ini, saya membangun sebuah repositori GitHub publik yang akan menjadi pusat dokumentasi dan penyimpanan hasil praktikum dari Modul 1 hingga Modul 7. Langkah-langkahnya mencakup inisialisasi Git, pengelolaan branch, penyusunan folder per modul, serta pembuatan dokumentasi.

---

## ✅ Prasyarat

Untuk menjalankan dan mengelola repositori ini, pastikan lingkungan kerja sudah siap:

1. Akun GitHub  
   - Daftar di https://github.com jika belum punya akun.

2. Git  
   - Windows: Download dari https://git-scm.com/download/win dan install dengan pengaturan default.

3. Visual Studio Code (VS Code)  
   - Unduh dari https://code.visualstudio.com  
   - Rekomendasi ekstensi:
     - GitLens
     - GitHub Pull Requests and Issues

4. Konfigurasi Git  
   Jalankan perintah berikut di terminal:

   ```bash
   git config --global user.name "Nurita Wahyuni"
   git config --global user.email "nuritawahyuni4@gmail.com"

---

## ⚙️Setup Proyek 

### Modul 1-3 - Struktur Awal

#Clone repositori dari GitHub
git clone https://github.com/nurita-wahyuni/Portofolio-Pemrograman-Web-202312061.git
cd Portofolio-Pemrograman-Web-202312061

#Membuat branch baru untuk tugas Modul 1-3
git branch tugas/modul-1-3

#Berpindah ke branch tersebut
git switch tugas/modul-1-3

#Tambahkan semua file dan lakukan commit
git add .
git commit -m "menambahkan modul 1-3"
git push -u origin tugas/modul-1-3

---

### modul 4-6 pengembangan-berkelanjutan 
Setiap kali modul selesai, lakukan langkah berikut:

#Pastikan berada di main dan menarik update terbaru
git checkout main
git pull origin main

#Membuat branch baru untuk tugas Modul 4
git branch tugas/modul-4-javascript

#Berpindah ke branch tersebut
git switch tugas/modul-4-javascript

#Tambahkan file tugas (copy dilakukan manual via File Explorer/VS Code)
git add .
git commit -m "menambahkan modul4 javascript"
git push -u origin tugas/modul-4-javascript


#Membuat branch baru untuk tugas Modul 5
git branch tugas/modul-5-dasarphp
git switch tugas/modul-5-dasarphp
git add .
git commit -m "menambahkan modul5 dasar php"
git push -u origin tugas/modul-5-dasarphp

#Membuat branch baru untuk tugas Modul 6
git branch tugas/modul-6-phpdanMysql
git switch tugas/modul-6-phpdanMysql
git add .
git commit -m "menambahkan modul 6 php dan mysql"
git push -u origin tugas/modul-6-phpdanMysql

## 🗂️ Struktur Folder

- [Modul1](./modul1/)
- [Modul2](./modul2/)
- [Modul3](./modul3/)
- [Modul4](./modul4/)
- [Modul5](./modul5/)
- [Modul6](./modul6/)
- [README.md](./README.md)

## penutup
Dokumentasi ini diharapkan membantu proses tracking, review, dan showcase dari semua proses pembelajaran selama praktikum Pemrograman Web. Semua kode dapat dicek dan diuji ulang sesuai struktur yang telah dibuat.
Terima kasih sudah membaca! ✨