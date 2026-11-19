ATTENDIFY - WEBSITE ABSENSI (VERSI BARU)

CARA MENJALANKAN
1. Simpan semua file dalam satu folder.
2. Buka siswa.html (siswa) atau admin.html (admin).
3. Password demo admin: admin123 (ubah di admin.js, konstanta PASS).

YANG BARU
Siswa : jam digital, sapaan sesuai waktu, cap "HADIR" animasi + confetti, ring persentase kehadiran,
        streak hari beruntun, kalender bulanan, riwayat dengan filter, notifikasi (bukan alert), data nama diingat.
Admin : kartu statistik, grafik donat, grafik 7 hari, daftar siswa terdaftar sehingga "Belum Absen" kini dihitung,
        ubah status siswa langsung dari tabel, filter kelas, ekspor CSV (termasuk yang belum absen), cetak, login bertahan selama tab dibuka.

FILE
siswa.html, admin.html, style.css, core.js (fungsi bersama), siswa.js, admin.js

BATASAN
Data tersimpan di localStorage browser yang sama (tanpa server). Agar siswa di HP masing-masing dan admin di perangkat lain
bisa saling terhubung, perlu backend (mis. Firebase/Supabase). Login admin hanya proteksi tampilan.
Data lama (key attendify_records_v1) tetap kompatibel.
