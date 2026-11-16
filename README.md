# Database Quest: Arsitek Data 🧩

> **Media Pembelajaran Interaktif Microteaching Pengantar Basis Data**  
> Pendidikan Ilmu Komputer — FPMIPA Universitas Pendidikan Indonesia  
> Oleh: **Diva Wahyu Nugraha**

---

## 📖 Deskripsi Proyek
**Database Quest: Arsitek Data** adalah game edukasi interaktif berbasis web yang dirancang khusus untuk mempraktikkan konsep dasar sistem basis data secara nyata dan problem-solving tanpa mengandalkan kuis pilihan ganda biasa.

Game ini mengadaptasi tema visual bersih profesional yang terinspirasi dari skema warna **Maxwell Theme** (kombinasi warna biru laut *Maxwell Blue* `#286090`, kartu putih bersih, dan tata letak terpusat yang ramah proyektor kelas).

---

## 🎮 Fitur & Level Permainan

### 🍞 Level 1: Kasus Toko Roti (Data vs Informasi)
* **Konsep Materi**: Memahami perbedaan fakta mentah (data) dengan data yang telah diolah dan bermakna untuk aksi keputusan (informasi).
* **Mekanisme**: Memilah 6 catatan kasir manual ke Wadah DATA dan Wadah INFORMASI.

### 🖥️ Level 2: Merakit 4 Pilar Sistem Basis Data
* **Konsep Materi**: Memahami 4 pilar komponen basis data: *Hardware*, *Software (DBMS)*, *Data Terintegrasi*, dan *Brainware (User)*.
* **Fitur Uji Nalar**: Menyediakan kartu jebakan (seperti secangkir kopi dan data duplikat/redundansi) yang akan memicu peringatan jika dimasukkan ke rak server.

### 🚀 Level 3: Konsultan DBMS Industri Digital
* **Konsep Materi**: Menjodohkan karakteristik perangkat lunak DBMS populer dengan kebutuhan mitra industri nyata:
  - **Tokopedia / Shopee (E-Commerce Web)** ➔ **MySQL** (Web Open-Source).
  - **Aplikasi Kasir Mobile Android** ➔ **SQLite** (Embedded, Ringan, Serverless).
  - **Netflix & Perbankan** ➔ **PostgreSQL** (Enterprise Skala Besar & Handal).

---

## ⏱️ Fitur Pembelajaran
- **Batas Waktu 10 Menit Tiap Level**: Mengasah kecepatan berpikir dan penalaran siswa dengan countdown dinamis serta peringatan visual otomatis.
- **Interaksi Ganda**: Mendukung *Drag & Drop* dan *Klik/Tap-to-Select* (kompatibel untuk layar sentuh, smartphone, tablet, dan Smartboard kelas).
- **Audio Synthesizer Mandiri**: Efek suara interaktif menggunakan Web Audio API tanpa memerlukan file eksternal (100% offline-ready).
- **Laporan Evaluasi 1-Klik**: Menghasilkan rekap nilai, durasi pengerjaan, dan sisa waktu yang siap disalin langsung ke WhatsApp guru.

---

## 🚀 Cara Menjalankan Secara Lokal

1. Clone repositori ini:
   ```bash
   git clone https://github.com/divaaawahyu12/Basic-basis-data.git
   cd Basic-basis-data
   ```
2. Jalankan server lokal sederhana (misal menggunakan Python):
   ```bash
   python -m http.server 8000
   ```
3. Buka di browser:
   ```
   http://localhost:8000/
   ```
Atau cukup buka file `index.html` langsung di browser Anda.
