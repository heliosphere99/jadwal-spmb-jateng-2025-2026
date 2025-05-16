# jadwal-spmb-jateng-2025-2026
# Jadwal SPMB SMA/K Jawa Tengah 2025/2026

Aplikasi web untuk menampilkan jadwal Seleksi Penerimaan Murid Baru (SPMB) SMA/SMK Jawa Tengah Tahun Ajaran 2025/2026.

## Fitur Utama

✅ **Tampilan Responsif**  
   - Optimal untuk desktop, tablet, dan mobile  
   - Tampilan tabel (desktop) dan kartu (mobile)  

✅ **Fitur Interaktif**  
   - Filter berdasarkan kategori: Semua, Daring, Luring, Penting  
   - Pencarian kegiatan  
   - Tampilan timeline visual  

✅ **Integrasi Kalender**  
   - Script untuk menambahkan jadwal ke Google Calendar  
   - Opsi berbagi ke multiple calendar  

## Cara Menggunakan

### 1. Mengakses Aplikasi Web
Akses melalui browser di perangkat apa saja. Aplikasi akan menyesuaikan tampilan secara otomatis.

### 2. Filter Jadwal
Gunakan tombol filter untuk melihat:
- Semua jadwal
- Hanya kegiatan daring
- Hanya kegiatan luring
- Hanya kegiatan penting

### 3. Pencarian
Ketik di search box untuk mencari kegiatan tertentu.

### 4. Menambahkan ke Google Calendar
1. Buka [Google Apps Script](https://script.google.com/)
2. Buat proyek baru
3. Salin kode dari bagian `integrasi-google-calendar.js`
4. Sesuaikan calendar ID jika perlu
5. Jalankan fungsi `addSPMBScheduleToCalendar()`

## Struktur Proyek
spmb-jateng-2025/
├── index.html # File utama aplikasi web
├── style.css # Stylesheet
├── script.js # Logika aplikasi
└── README.md # Dokumentasi ini

## Persyaratan Sistem

- Browser modern (Chrome, Firefox, Edge, Safari)
- Akun Google untuk integrasi kalender

## Kontribusi

1. Fork repository
2. Buat branch fitur (`git checkout -b fitur-baru`)
3. Commit perubahan (`git commit -am 'Tambahkan fitur'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).
