👩‍🏫 e-Presensi — Aplikasi Presensi Berbasis Google Sheet
e-Presensi adalah aplikasi berbasis web yang dikembangkan untuk mempermudah proses presensi digital di lingkungan sekolah atau instansi.
Aplikasi ini memanfaatkan Google Authentication untuk login dan Google Sheets API sebagai basis penyimpanan data, sehingga semua data absensi langsung tersimpan di Google Drive pengguna.



# 📌 e-Presensi Lite  
Aplikasi Presensi Siswa berbasis Google Login & Google Spreadsheet

✅ Login menggunakan Google OAuth (tanpa database lokal)  
✅ Data tersimpan otomatis ke Google Spreadsheet  
✅ Satu akun = satu file spreadsheet cloud  
✅ UI simple & mobile friendly (React + Tailwind)  
✅ Tidak perlu server backend (murni frontend + Google API)
---

# 🌐 Demo Online:
## 👉 (https://smkyappiwns.github.io/presensi-siswa/)
---

## 🚀 Fitur Utama

| Fitur | Keterangan |
|-------|------------|
| 🔐 Google Login | Menggunakan Google Identity Services (GIS) |
| 📄 Auto Spreadsheet | Spreadsheet otomatis dibuat di Google Drive pengguna |
| 🕒 Presensi Harian | Input hadir / izin / sakit / alfa |
| 📊 Rekap Otomatis | Data otomatis dihitung dalam Spreadsheet |
| 🏫 Pilihan Kelas | Guru dapat memilih kelas sebelum presensi |
| 💾 Auto Save | Tidak ada tombol submit, data langsung tersimpan |
| 📱 Full Responsive | Bisa dipakai lewat HP |
| 🔁 Sync | Jika file sudah ada, tidak dibuat ulang |
| ⚠️ Token Expired Auto Logout | Jika sesi habis, login ulang otomatis |

---

## 🛠️ Tech Stack

| Teknologi | Digunakan Untuk |
|-----------|-----------------|
| React + Vite | Frontend utama |
| TypeScript | Type safety |
| TailwindCSS | UI styling |
| Google Identity Services | Login OAuth |
| Google Drive API | Membuat file spreadsheet |
| Google Sheets API | Input & update presensi |
| LocalStorage | Cache user & spreadsheet ID |
| Service Worker (optional) | PWA / mode offline |

---

## 📂 Struktur Proyek (Ringkas)


