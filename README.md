# 📌 e-Presensi  
Aplikasi Presensi Siswa berbasis Google Login & Google Spreadsheet  

✅ Login menggunakan Google OAuth (tanpa database lokal)  
✅ Data tersimpan otomatis ke Google Spreadsheet  
✅ 100% Frontend — tanpa server / backend  
✅ Spreadsheet dibuat otomatis di Google Drive tiap user  
✅ UI sederhana, cepat, dan mobile friendly (React + Tailwind)

---

## 🌐 Demo Online  
🔗 **https://smkyappiwns.github.io/presensi-siswa/**  

---

## 🚀 Fitur Utama

| Fitur | Keterangan |
|-------|------------|
| 🔐 Google Login | Google Identity Services (GIS) — bukan gapi.auth2 lama |
| 📄 Auto Spreadsheet | Nama default: `e-Presensi_Data` |
| 🕒 Presensi Harian | Hadir / Izin / Sakit / Alfa |
| 📊 Rekap Otomatis | Data per hari tersimpan sebagai row |
| 🏫 Multi Kelas | Pilih kelas sebelum presensi |
| 📱 Full Responsive | Bisa pakai HP / Tablet |
| 🔁 Sinkronisasi | Jika spreadsheet sudah ada → tidak dibuat ulang |
| 📌 Local Cache | Menyimpan data siswa agar tidak selalu fetch API |
| ⚠️ Auto Logout | Token expired → logout otomatis |

---

## 🛠️ Tech Stack

| Teknologi | Fungsi |
|-----------|--------|
| React + Vite | UI & App core |
| TypeScript | Type safety |
| TailwindCSS | Styling |
| Google Identity Services | Login OAuth 2.0 |
| Google Drive API | Membuat file spreadsheet |
| Google Sheets API | Menulis & membaca data presensi |
| LocalStorage | Cache spreadsheet & user |
| GitHub Pages | Hosting demo |

---
