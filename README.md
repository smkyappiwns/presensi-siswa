👩‍🏫 e-Presensi — Aplikasi Presensi Berbasis Google Sheet
e-Presensi adalah aplikasi berbasis web yang dikembangkan untuk mempermudah proses presensi digital di lingkungan sekolah atau instansi.
Aplikasi ini memanfaatkan Google Authentication untuk login dan Google Sheets API sebagai basis penyimpanan data, sehingga semua data absensi langsung tersimpan di Google Drive pengguna.

🌐 Demo Online:
👉 (https://smkyappiwns.github.io/presensi-siswa/)

🚀 Fitur Utama
🔐 Login dengan Akun Google — menggunakan integrasi Google OAuth2.0
📋 Template Presensi Otomatis — sistem otomatis membuat file presensi-app di Google Sheets
📤 Upload Template Presensi — bisa mengimpor file .xlsx atau .csv untuk memperbarui data
🧾 Rekap Otomatis — data presensi langsung disimpan dan direkap di Google Sheet pengguna
🌙 Mode Gelap & Terang — tampilan dinamis sesuai preferensi pengguna
📱 Responsif — bisa digunakan di komputer, tablet, maupun smartphone
🧠 Teknologi yang Digunakan
Teknologi	Keterangan
React 19	Framework utama UI
Vite	Build tool cepat dan ringan
Tailwind CSS	Styling modern dan responsif
Google API Client (gapi-script)	Autentikasi & komunikasi dengan Google Sheet
xlsx.js	Mengolah dan membaca file Excel
Framer Motion	Animasi transisi UI
Lucide React	Koleksi ikon SVG ringan
React Router DOM	Navigasi antar halaman
