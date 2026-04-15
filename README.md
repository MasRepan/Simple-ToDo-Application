# Simple ToDo List
Aplikasi ToDo List sederhana berbasis HTML, CSS, dan JavaScript murni (tanpa framework) untuk menambah dan menghapus daftar tugas harian.
## Preview Fitur
- Menambahkan todo baru dengan teks tugas dan tanggal.
- Validasi input agar todo dan tanggal tidak kosong.
- Menampilkan daftar todo secara dinamis.
- Menghapus seluruh todo dengan tombol **Delete All**.
- Tampilan UI ringan dengan kombinasi CSS custom dan Tailwind CSS (CDN).
## Teknologi yang Digunakan
- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Tailwind CSS via CDN
## Cara Penggunaan
1. Isi kolom todo dengan tugas yang ingin ditambahkan.
2. Pilih tanggal pada kolom date.
3. Klik tombol **Add Todo** untuk menambahkan ke daftar.
4. Klik **Delete All** untuk menghapus semua todo.
## Catatan Pengembangan
- Tombol **Filter** sudah tersedia di antarmuka, namun fungsi filternya belum diimplementasikan pada `Flow.js`.
- Data todo saat ini hanya tersimpan sementara (di memori browser selama halaman aktif), belum menggunakan `localStorage`/database.
