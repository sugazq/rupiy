# 💰 RUPIY — Personal Finance & Smart Expense Tracker

RUPIY adalah aplikasi manajemen keuangan pribadi berbasis **Flutter** yang membantu pengguna mencatat pemasukan & pengeluaran, memindai struk belanja menggunakan **OCR**, melihat statistik keuangan secara visual, serta (opsional) melakukan pengecekan saldo e-money melalui **NFC**.

Aplikasi ini dirancang dengan arsitektur **scalable**, UI modern, dan siap untuk dipublikasikan ke **Google Play Store**.

---

## 🚀 Fitur Utama

### 📌 1. Manajemen Transaksi
- Tambah, edit, dan hapus transaksi
- Pemasukan & pengeluaran
- Kategori transaksi otomatis & manual
- Catatan dan tanggal transaksi

### 📷 2. Scan Struk (OCR)
- Scan struk via kamera atau galeri
- Ekstraksi otomatis:
  - Nama merchant
  - Total pembayaran
  - Tanggal
  - Kategori (auto-detect)
- Data bisa diedit sebelum disimpan
- Menampilkan raw text hasil OCR

### 📊 3. Statistik Keuangan
- Ringkasan saldo
- Pie Chart distribusi pengeluaran per kategori
- Bar Chart pengeluaran 7 hari terakhir

### 🗂️ 4. Kategori Transaksi
- Daftar kategori pengeluaran
- Detail transaksi per kategori
- Filter & grouping otomatis

### 📡 5. NFC Scan Saldo (Mock / Experimental)
- Dukungan (konsep):
  - Flazz BCA
  - e-Money Mandiri
  - TapCash BNI
  - Brizzi BRI
  - JakCard
- Digunakan hanya untuk **cek saldo**
- Implementasi real tergantung dukungan perangkat & kartu

---

## 🧭 Struktur Navigasi

Aplikasi menggunakan **Bottom Navigation Bar** dengan 4 menu utama:

- 🏠 Beranda  
- 📊 Statistik  
- 🗂️ Kategori  
- 📷 Scan Struk  

---
