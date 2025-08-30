RafMailer - Alat Pengirim Email Gmail Massal 🚨
Alat CLI berbasis Node.js untuk mengirim email massal via Gmail dengan nama pengirim acak dan ID pesan unik.
Peringatan Penting:RafMailer adalah alat untuk keperluan pengujian dan otomatisasi pengiriman email. Alat ini dapat disalahgunakan untuk spamming atau aktivitas hacking, yang melanggar kebijakan Gmail dan hukum yang berlaku. Gunakan hanya untuk tujuan sah seperti pengujian sistem atau otomatisasi internal. Penyalahgunaan dapat menyebabkan pemblokiran akun Gmail atau konsekuensi hukum. Kami tidak bertanggung jawab atas penyalahgunaan alat ini.

✨ Fitur

Pengiriman Email Massal: Kirim banyak email ke satu penerima dengan cepat dan mudah.
Nama Pengirim Acak: Pilih dari daftar nama pengirim bertema teknologi untuk setiap email.
ID Pesan Unik: Membuat header Message-ID unik untuk setiap email agar terdeteksi sebagai pesan valid.
Antarmuka CLI Profesional: Prompt berwarna dengan chalk dan tampilan teks keren dengan figlet.
Pencatatan Log: Riwayat pengiriman dan error disimpan ke file history.log.
Kustomisasi Mudah: Tambahkan nama pengirim sendiri atau sesuaikan kode sesuai kebutuhan.


🛠️ Prasyarat
Pastikan Anda memiliki:

Node.js (v16 atau lebih tinggi) - Unduh Node.js
NPM (sudah include dengan Node.js)
Akun Gmail dengan App Password (jika 2FA aktif) atau kata sandi Gmail biasa.


📦 Instalasi
RafMailer dirancang untuk dijalankan dengan langkah super sederhana dan profesional. Ikuti langkah berikut:

Clone Repositori:
git clone https://github.com/rafashacodeid/rafmailer.git
cd rafmailer


Instal Dependensi:
npm install


Konfigurasi Gmail:Edit file index.js dan masukkan kredensial Gmail Anda di bagian berikut:
let transporter = nodemailer.createTransport({
  service: "gmail",
  auth: {
    user: "your-gmail@gmail.com", // Ganti dengan alamat Gmail Anda
    pass: "your-app-password-or-password", // Ganti dengan App Password atau kata sandi Gmail
  },
});

Untuk membuat App Password:

Buka pengaturan Akun Google Anda.
Aktifkan Verifikasi 2 Langkah jika belum aktif.
Kunjungi Keamanan > Kata Sandi Aplikasi dan buat kata sandi baru untuk "Mail".




🚀 Cara Menjalankan

Jalankan RafMailer:
npm start

⚠️ Peringatan

Batas Pengiriman Gmail: Gmail membatasi pengiriman (biasanya 500 email/hari untuk akun gratis). Hindari pengiriman berlebihan agar akun tidak diblokir.
Keamanan: Jaga kerahasiaan kredensial Gmail di index.js. Jangan bagikan file tersebut.
Penyalahgunaan: Spamming atau aktivitas ilegal melanggar hukum dan kebijakan Gmail. Gunakan hanya untuk pengujian sah.
Kustomisasi: Ubah array senderNames di index.js untuk menambahkan nama pengirim sesuai selera.


📜 Lisensi
Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file LICENSE untuk detailnya.
