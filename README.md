# 🔐 CRYPTA-X - Secure Multi-Layer Encryption

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Telegram Bot](https://img.shields.io/badge/Telegram-Bot-blue.svg)](https://core.telegram.org/bots)

Alat enkripsi/dekripsi berlapis dengan sistem kunci dinamis dan manajemen akses terpusat. Dirancang untuk operasi keamanan tingkat tinggi dengan fitur:

- Enkripsi 4 lapis (Caesar, Atbash, Playfair, Base64)
- Pergantian algoritma otomatis harian
- Manajemen pengguna berbasis Google Sheets
- Audit log real-time

> Warning  
> Alat ini hanya untuk tujuan keamanan dan edukasi.  
> Penyalahgunaan untuk aktivitas ilegal akan ditindak sesuai hukum!

## 🛡️ Fitur Keamanan

| Fitur | Deskripsi |
|-------|-----------|
| 🔄 Dynamic Key Rotation | Pergeseran Caesar & kunci Playfair berubah setiap hari |
| 👥 Centralized Access Control | Manajemen pengguna via Google Sheets |
| 📜 Audit Trail | Log waktu pendaftaran pengguna |
| 🚨 Admin Alerts | Notifikasi aktivitas mencurigakan (dalam pengembangan) |
| 🔒 Multi-Layer Encryption | Proteksi berlapis dengan 4 algoritma berbeda |
| 💻 CLI & Bot Support | Antarmuka Telegram Bot dan Command Line |

## 🚀 Instalasi

### Prasyarat
- Python 3.7+
- Akun Google Cloud (untuk Google Sheets API)
- Token Bot Telegram ([@BotFather](https://t.me/BotFather))
- Akses server (direkomendasikan)

### Langkah Instalasi

`bash
# 1. Clone repositori
git clone https://github.com/yourusername/CRYPTA-X.git
cd CRYPTA-X

# 2. Setup environment
python3 -m venv venv
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Konfigurasi credentials
cp config.example.py config.py
nano config.py  # Edit dengan detail akun Anda

# 5. Download Google Service Account credentials
#    Simpan sebagai 'credentials.json' di direktori utama

# 6. Jalankan bot
python bot.py

### 
