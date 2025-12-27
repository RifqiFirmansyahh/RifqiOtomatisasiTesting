Rifqi Demoblaze Automation Testing (UAS PPL)
Proyek ini adalah implementasi pengujian otomasi untuk aplikasi e-commerce Demoblaze. Pengujian mencakup 12 skenario yang terbagi ke dalam 4 modul utama menggunakan Selenium WebDriver, Java, dan TestNG.

🚀 Fitur Pengujian
Arsitektur Page Object Model (POM): Memisahkan logika pengujian dengan elemen UI untuk kemudahan pemeliharaan.


Modul Terintegrasi: Mencakup Autentikasi, Katalog Produk, Keranjang Belanja, dan Alur Pembelian.


Pelaporan ExtentReports: Menghasilkan laporan HTML interaktif di folder reports/TestReport.html.


Deteksi Bug Otomatis: Skrip dikonfigurasi untuk mendeteksi BUG-001 pada fitur Checkout.


🛠️ Tech Stack
Language: Java 17+

Automation: Selenium WebDriver 4.x

Test Runner: TestNG

Report: ExtentReports 5.x

Build Tool: Maven

📂 Struktur Proyek
Plaintext

RifqiOtomatisasiTesting/
├── reports/                 # Hasil laporan pengujian (HTML)
├── src/
│   ├── main/java/           # Page Object Classes
│   └── test/java/           # Test Script Classes
├── pom.xml                  # Dependensi Maven
└── testng.xml               # Konfigurasi eksekusi
⚙️ Cara Menjalankan
Clone Repositori:

Bash

git clone https://github.com/UsernameAnda/RifqiOtomatisasiTesting.git
Buka di IntelliJ IDEA: Pastikan Maven melakukan reload untuk mengunduh semua dependensi.

Eksekusi Pengujian: Klik kanan pada file testng.xml di root project, lalu pilih Run.

Lihat Laporan: Setelah selesai, buka file reports/TestReport.html menggunakan browser.

📊 Ringkasan Hasil (Summary)

Total Kasus Uji: 12 



Lulus (Passed): 11 



Gagal (Failed): 1 (BUG-001 pada TC-PURCH-03)
