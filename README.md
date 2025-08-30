# RafMailer - Alat Pengirim Email Gmail Massal 🚨

**RafMailer** adalah alat **CLI berbasis Node.js** untuk mengirim email massal via Gmail dengan **nama pengirim acak** dan **ID pesan unik**.  

⚠️ **Peringatan Penting**  
RafMailer dibuat untuk **keperluan pengujian dan otomatisasi**. Penyalahgunaan untuk **spam** atau aktivitas ilegal akan melanggar **kebijakan Gmail** serta **hukum yang berlaku**. Gunakan hanya untuk tujuan sah.  
Kami **tidak bertanggung jawab** atas penyalahgunaan alat ini.  

---

## ✨ Fitur
- 📧 **Pengiriman Email Massal** – Kirim banyak email ke satu penerima dengan cepat.  
- 👤 **Nama Pengirim Acak** – Nama pengirim diacak dari daftar bertema teknologi.  
- 📨 **ID Pesan Unik** – Setiap email punya `Message-ID` unik agar lebih valid.  
- 🎨 **Antarmuka CLI Profesional** – Warna dari `chalk` + teks keren dari `figlet`.  
- 📝 **Pencatatan Log** – Riwayat pengiriman & error otomatis tersimpan di `history.log`.  
- ⚙️ **Kustomisasi Mudah** – Bisa tambah nama pengirim atau edit kode sesuai kebutuhan.  

---

## 🛠️ Prasyarat
Pastikan sudah terpasang:
- [Node.js](https://nodejs.org/) **versi 16 atau lebih tinggi**  
- **NPM** (otomatis terpasang dengan Node.js)  
- Akun Gmail dengan:
  - **App Password** (jika 2FA aktif), atau  
  - **Password Gmail biasa** (jika tanpa 2FA)  

---

## 📦 Instalasi

1. **Clone repositori**
   ```bash
   git clone https://github.com/rafashacodeid/rafmailer.git
   cd rafmailer
Instal dependensi

bash
Copy code
npm install
Jalankan RafMailer

bash
Copy code
npm start
⚠️ Peringatan
⏳ Batas Gmail – Gmail membatasi ~500 email/hari untuk akun gratis.

🔐 Keamanan – Jangan bagikan kredensial Gmail (index.js).

🚫 Penyalahgunaan – Spam/aktivitas ilegal bisa kena blokir atau masalah hukum.

🎨 Kustomisasi – Edit array senderNames di index.js untuk nama pengirim unik.

📜 Lisensi
Proyek ini dilisensikan di bawah MIT License – lihat file LICENSE untuk detail.
``
