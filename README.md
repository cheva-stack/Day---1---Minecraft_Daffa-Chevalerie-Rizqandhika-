# Dokumentasi Day 1 - Proyek Workshop 2026

* **Nama Lengkap:** Daffa Chevalerie Rizqandhika
* **Kelompok:** Minecraft
* **Pemateri:** Nugi Farhan (Senior Product Designer)
* **Topik Workshop:** Building with AI, Managing Change with GitHub

---

## 1. Deskripsi Repository
Repository ini dibuat untuk mendokumentasikan seluruh materi, alur kerja teknis, poin-poin penting, serta refleksi pribadi selama mengikuti **Day 1 Proyek Workshop 2026** tentang pemanfaatan AI dan pengelolaan *version control* menggunakan Git & GitHub.

## 2. Tujuan & Kegunaan Repository
* Menjadi wadah catatan terstruktur mengenai konsep Prompt Engineering dan alur kerja Git/GitHub.
* Mempraktikkan langsung alur pembuatan proyek web sederhana (*Student Task Planner*) yang dibantu oleh AI.
* Memenuhi ketentuan tugas dan kriteria penilaian dari panitia workshop.

## 3. Informasi Kegiatan Workshop
Dokumentasi lengkap mengenai rangkuman materi, poin pengetahuan baru, dan refleksi kegiatan workshop disajikan pada poin-poin di bawah ini.

---

## 4. Dokumentasi Kegiatan Workshop

### A. Rangkuman Materi Workshop
1. **Prompt Engineering & Building with AI:**
   * **Definisi:** Cara merancang instruksi agar AI memberikan jawaban yang tepat, relevan, dan layak digunakan.
   * **Struktur Prompt yang Baik:** Mengandung 4 elemen utama yaitu *Role* (peran), *Task* (tugas utama), *Context* (latar belakang & batasan), serta *Format/Output* (bentuk hasil akhir yang diinginkan).
   * **Manfaat:** Meningkatkan kinerja model AI, mengurangi *bias*, serta meningkatkan kontrol dan kepastian respon.

2. **Git vs GitHub:**
   * **Git:** Sistem *Version Control* terdistribusi (DVCS) berbasis lokal untuk melacak dan mengelola perubahan kode.
   * **GitHub:** Platform berbasis web untuk menyimpan repository Git secara *online* dan mendukung kolaborasi tim.

3. **Git Workflow & Area Kerja:**
   * **Working Directory:** Folder lokal tempat pengembang mengedit file proyek secara langsung.
   * **Staging Area (Index):** Tempat penampungan sementara perubahan file sebelum dimasukkan ke dalam commit (`git add`).
   * **Git Directory (Repository):** Tempat penyimpanan metadata dan riwayat *commit* proyek (`git commit`).

---

### B. Poin-Poin Penting & Pengetahuan Baru
* **Perintah Dasar Git:**
  * `git init`: Memulai/membuat repository Git lokal baru.
  * `git clone <url>`: Mengunduh repository dari GitHub ke komputer lokal.
  * `git add .`: Memindahkan seluruh perubahan file ke *Staging Area*.
  * `git commit -m "pesan"`: Menyimpan snapshot perubahan dari *Staging Area* ke repository lokal.
  * `git push origin main`: Mengirimkan *commit* dari lokal ke repository remote di GitHub.
* **Integrasi Keamanan SSH:** Penggunaan perintah `ssh-keygen -t ed25519` untuk membuat SSH Key dan menghubungkannya dengan akun GitHub agar autentikasi aman tanpa perlu mengetik kata sandi berulang kali.
* **Eksperimen Aplikasi:** Alur pembuatan aplikasi web sederhana (*Student Task Planner*) menggunakan bantuan AI (seperti ChatGPT/Claude) yang kemudian diintegrasikan langsung ke GitHub.

---

### C. Pendapat Pribadi tentang Day 1 Proyek Workshop
Materi Day 1 Proyek Workshop ini sangat membuka wawasan baru. Terutama untuk *Prompt Engineering* mempercepat pengembangan proyek dan penggunaan Git/GitHub untuk manajemen kode memberikan gambaran nyata alur kerja standar industri bagi mahasiswa software engineering/teknik multimedia.