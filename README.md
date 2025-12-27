# 🛒 Demoblaze Automation Testing Suite

### **Proyek UAS Praktikum Perangkat Lunak (PPL)**

Repositori ini berisi proyek pengujian otomasi fungsional untuk aplikasi web e-commerce [Demoblaze](https://www.demoblaze.com). Pengujian ini mencakup skenario *end-to-end* mulai dari autentikasi hingga proses pembelian menggunakan arsitektur **Page Object Model (POM)**.

---

## 📋 Cakupan Pengujian (Test Scope)

Proyek ini mengotomasi **12 Test Case** yang dikelompokkan ke dalam 4 modul utama sesuai dengan rencana pengujian manual:

1. 
**Modul 1: User Authentication** (Login Valid, Login Gagal, & Logout).


2. 
**Modul 2: Product Catalog** (Filter Kategori, Navigasi Next, & Detail Produk).


3. 
**Modul 3: Shopping Cart** (Tambah Produk, Lihat Keranjang, & Hapus Produk).


4. 
**Modul 4: Purchase Flow** (Checkout Valid, Form Kosong, & Validasi Keranjang Kosong).



---

## 🛠️ Arsitektur & Teknologi

Proyek ini dibangun dengan standar industri pengujian perangkat lunak:

* 
**Bahasa Pemrograman:** Java 17.


* 
**Automation Tool:** Selenium WebDriver (Manager).


* **Test Runner:** TestNG (untuk manajemen urutan tes dan assertions).
* **Reporting:** ExtentReports (menghasilkan laporan HTML interaktif).
* **Design Pattern:** Page Object Model (POM) untuk memisahkan logika UI dan skrip tes.

---

## 📂 Struktur Folder

```text
RifqiOtomatisasiTesting/
├── reports/                 # Laporan hasil eksekusi (HTML)
├── src/
│   ├── main/java/           # Page Objects (Struktur Elemen Web)
│   └── test/java/           # Test Suites (Logika Pengujian)
├── pom.xml                  # Konfigurasi Dependensi Maven
└── testng.xml               # Pengatur Eksekusi Seluruh Modul

```

---

## 🚀 Cara Menjalankan (Installation & Execution)

1. **Clone repositori ini:**
```bash
git clone https://github.com/UsernameAnda/RifqiOtomatisasiTesting.git

```


2. **Buka proyek** menggunakan IntelliJ IDEA atau Eclipse.
3. Pastikan koneksi internet aktif untuk mengunduh dependensi **Maven**.
4. Klik kanan pada file **`testng.xml`** di root folder.
5. Pilih **"Run 'testng.xml'"**.
6. Setelah eksekusi selesai, buka folder **`reports/TestReport.html`** menggunakan browser pilihan Anda.

---

## 🐛 Bug Discovery (BUG-001)

Berdasarkan hasil pengujian otomatis, sistem berhasil mendeteksi satu bug fungsional kritis:

* 
**ID:** BUG-001.


* 
**Deskripsi:** Tombol "Place Order" tetap aktif meskipun keranjang belanja kosong.


* 
**Status Otomasi:** **FAILED** (Sesuai dengan temuan pada pengujian manual).



---

## 👤 Identitas Penguji

* 
**Nama:** Rifqi Firmansyah.


* **NPM:** 230109029.
* **Mata Kuliah:** Praktikum Perangkat Lunak (UAS).

---

### Cara Menggunakan:

1. Buat file baru di root project IntelliJ Anda dengan nama **`README.md`**.
2. Salin dan tempel (copy-paste) teks di atas.
3. Simpan dan lakukan **Commit & Push** ke GitHub.
4. Tampilan di GitHub akan otomatis menjadi rapi dengan ikon dan tabel.

Apakah ada bagian identitas atau link yang ingin Anda sesuaikan lagi?
