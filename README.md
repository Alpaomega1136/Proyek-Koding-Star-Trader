# Proyek-Koding-Star-Trader

# 🚀 Star-Trader: Simulasi Perdagangan Luar Angkasa

Selamat datang di repositori **Star-Trader**, sebuah game simulasi perdagangan luar angkasa berbasis konsol yang dikembangkan menggunakan C++. Proyek ini merupakan implementasi dari tantangan coding yang kompleks, berfokus pada desain modular, manajemen data dari file eksternal, dan pemrograman prosedural.

Jadilah seorang kapten kapal kargo, jelajahi galaksi, beli murah dan jual mahal, selesaikan misi, dan bangun imperium perdagangan Anda dari nol!

## 📜 Latar Belakang

Di abad ke-25, Anda adalah seorang pilot pemula dengan kapal kargo tua, "The Rusty Comet". Tujuan Anda adalah menjadi pedagang antarplanet yang sukses. Game ini mensimulasikan tantangan dalam mengelola bisnis perdagangan, mulai dari melacak inventaris, bahan bakar, hingga menavigasi pasar yang dinamis di seluruh galaksi.

## ✨ Fitur Utama

- **Eksplorasi Galaksi**: Bepergian antar planet yang unik, masing-masing dengan pasar dan peluangnya sendiri.
- **Sistem Ekonomi**: Beli dan jual berbagai komoditas. Harga bervariasi antar planet, menciptakan peluang arbitrase yang menantang.
- **Manajemen Kapal**: Lacak status kapal Anda, termasuk bahan bakar, kapasitas kargo, dan muatan saat ini.
- **Upgrade & Kustomisasi**: Kunjungi bengkel untuk mengisi bahan bakar dan meningkatkan komponen kapal Anda seperti mesin dan ruang kargo.
- **Sistem Misi**: Ambil dan selesaikan misi pengiriman untuk mendapatkan hadiah dan reputasi.
- **Simpan & Muat Progres**: Simpan progres permainan Anda kapan saja dan lanjutkan petualangan Anda nanti.

## 📖 Dokumentasi Lengkap

Untuk penjelasan yang lebih mendalam mengenai setiap fitur, alur kerja, dan detail teknis proyek, silakan kunjungi halaman dokumentasi lengkap kami.

➡️ **[Kunjungi Dokumentasi Proyek Star-Trader](https://alpaomega1136.github.io/Proyek-Koding-Star-Trader/)**

## 📁 Struktur Proyek

Proyek ini dirancang dengan struktur modular untuk menjaga keterbacaan dan kemudahan pengembangan.

```
star-trader/
│
├── src/                # Folder berisi semua file source code
│   ├── main.cpp
│   ├── player.h
│   ├── player.cpp
│   ├── ship.h
│   ├── ship.cpp
│   ├── galaxy.h
│   ├── galaxy.cpp
│   ├── market.h
│   ├── market.cpp
│   ├── mission.h
│   ├── mission.cpp
│   ├── utility.h
│   └── utility.cpp
│
├── data/               # Folder berisi data game eksternal
│   ├── planets.csv
│   ├── goods.csv
│   └── missions.csv
│
├── save_data/          # Folder untuk menyimpan file progres pemain
│   └── (file save akan dibuat di sini)
│
├── makefile            # File untuk kompilasi proyek
│
└── README.md           # Anda sedang membacanya
```

## ⚙️ Prasyarat

Sebelum memulai, pastikan lingkungan pengembangan Anda memenuhi persyaratan berikut:

1.  **Sistem Operasi**: Linux atau Windows dengan WSL (Windows Subsystem for Linux).
2.  **Compiler**: `g++` (bagian dari `build-essential`).
3.  **Build Tool**: `make`.

Jika Anda belum menginstalnya di lingkungan Linux/WSL, jalankan perintah berikut:
```bash
sudo apt update
sudo apt install build-essential
```

## 🚀 Cara Menjalankan

Ikuti langkah-langkah ini untuk mengompilasi dan menjalankan proyek:

1.  **Clone Repositori**
    Buka terminal Anda dan clone repositori ini:
    ```bash
    git clone [https://github.com/username/star-trader.git](https://github.com/username/star-trader.git)
    cd star-trader
    ```
    *(Ganti `username` dengan nama pengguna GitHub Anda)*

2.  **Kompilasi Proyek**
    Gunakan `make` untuk mengompilasi semua file source code. Perintah ini akan membuat file eksekusi bernama `startrader` di direktori utama.
    ```bash
    make
    ```

3.  **Jalankan Game**
    Setelah kompilasi berhasil, jalankan game dengan perintah berikut:
    ```bash
    ./startrader
    ```

## 🎮 Cara Bermain

Setelah program berjalan, Anda akan disambut dengan menu utama. Berikut adalah beberapa perintah dasar untuk memulai:

-   `KARAKTER_BARU`: Membuat profil pemain baru.
-   `MUAT_PERMAINAN`: Memuat permainan yang sudah tersimpan.
-   `STATUS`: Menampilkan status kapal dan kapten saat ini.
-   `NAVIGASI`: Melihat daftar planet dan melakukan perjalanan.
-   `PASAR`: Melihat komoditas yang tersedia di pasar planet saat ini.
-   `BELI <NAMA_BARANG> <JUMLAH>`: Membeli barang.
-   `JUAL <NAMA_BARANG> <JUMLAH>`: Menjual barang.
-   `BANTUAN`: Menampilkan semua perintah yang tersedia.
-   `KELUAR`: Keluar dari permainan.

Selamat bertualang di galaksi Star-Trader, Kapten!
