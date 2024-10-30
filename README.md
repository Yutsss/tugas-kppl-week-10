# **Tugas KPPL Week 10**

Nama: Adyuta Prajahita Murdianto

NRP: 5025221186

Kelas: KPPL E

## **Deskripsi Kasus**

PT. Travelo adalah perusahaan yang bergerak di bidang perjalanan dan pariwisata. Untuk meningkatkan pelayanannya, perusahaan ini ingin mengembangkan sistem pemesanan tiket secara online, yang mencakup pemesanan tiket pesawat, kereta api, dan hotel. Mereka ingin sistem ini mudah digunakan, aman, dan dapat diakses di perangkat mobile. Sebagai seorang analis sistem, Anda bertanggung jawab dalam tahap requirement untuk mengidentifikasi kebutuhan dari sistem ini.

Permintaan dan Ekspektasi dari Pemangku Kepentingan:

1. Pengguna (Traveler) menginginkan antarmuka yang mudah digunakan, dapat mencari tiket dengan berbagai filter, dan melakukan pembayaran dengan aman.
2. Administrator Sistem membutuhkan akses untuk mengelola data penerbangan, perjalanan kereta, dan hotel serta memantau transaksi.
3. Tim Manajemen ingin laporan penjualan secara real-time dan data statistik untuk keperluan pengambilan keputusan.
4. Departemen Keamanan IT menginginkan fitur keamanan tambahan, termasuk enkripsi data dan otentikasi ganda untuk pembayaran.

## **Functional Requirements**

### **1. Pengguna (Traveler)**

**Pendaftaran dan Login**

- Pengguna dapat mendaftar akun baru menggunakan email, nomor telepon, atau media sosial.
- Pengguna dapat login ke akun mereka menggunakan email dan kata sandi, atau melalui metode login media sosial.

**Pencarian dan Pemesanan**

- Pengguna dapat mencari tiket pesawat, kereta api, dan hotel berdasarkan berbagai filter (misalnya, lokasi, tanggal, jenis kelas, harga, durasi perjalanan, dll.).

- Pengguna dapat melihat detail tiket (misalnya, harga, waktu keberangkatan, durasi, dan informasi lain).

- Pengguna dapat memilih tiket dan menambahkannya ke keranjang pemesanan.

- Pengguna dapat melakukan pemesanan untuk satu atau lebih tiket dalam satu transaksi.

**Pembayaran**

- Sistem menyediakan berbagai metode pembayaran, termasuk kartu kredit, transfer bank, dan e-wallet.

- Pengguna dapat melihat detail total biaya sebelum melakukan pembayaran.

- Pengguna akan menerima konfirmasi pembayaran dan e-tiket setelah pembayaran berhasil.

**Manajemen Pemesanan**

- Pengguna dapat melihat riwayat pemesanan sebelumnya.

- Pengguna dapat membatalkan atau mengubah pemesanan sesuai dengan kebijakan perusahaan.

- Pengguna dapat mengunduh atau mencetak e-tiket setelah pemesanan dikonfirmasi.

### **2. Administrator Sistem**

**Manajemen Data Penerbangan, Kereta Api, dan Hotel**

- Administrator dapat menambah, mengedit, atau menghapus data terkait penerbangan, kereta api, dan hotel.

- Administrator dapat memperbarui harga, jadwal, dan ketersediaan tempat duduk/kamar.

**Pemantauan Transaksi**

- Administrator dapat memantau dan mengelola semua transaksi pemesanan.

- Administrator dapat meninjau detail pemesanan, status pembayaran, dan riwayat transaksi.

**Manajemen Pengguna**

- Administrator dapat menambah, mengedit, atau menonaktifkan akun pengguna.

- Administrator dapat membantu pengguna dalam pemulihan akun atau permasalahan teknis lainnya.

### **3. Tim Manajemen**

**Laporan Penjualan dan Data Statistik**

- Sistem menghasilkan laporan penjualan tiket dan data statistik terkait penjualan berdasarkan periode waktu tertentu (harian, mingguan, bulanan, tahunan).

- Sistem menyediakan informasi statistik pengguna, seperti jumlah pemesanan berdasarkan kategori tiket, destinasi populer, dan periode puncak.

**Fitur Ekspor Laporan**

- Tim Manajemen dapat mengekspor laporan ke format Excel atau PDF untuk keperluan analisis.

### **4. Departemen Keamanan IT**

**Pengaturan Keamanan**

- Sistem memungkinkan Departemen Keamanan IT untuk mengatur enkripsi data pengguna dan transaksi.

- Departemen IT dapat mengaktifkan atau menonaktifkan fitur otentikasi ganda untuk proses login dan pembayaran.

## **Non-Functional Requirements**

**Usability (Kemudahan Penggunaan)**

- Antarmuka pengguna harus mudah dipahami dan ramah pengguna, terutama pada perangkat mobile.

- Sistem harus memberikan pengalaman pengguna yang intuitif, dengan alur pemesanan yang jelas dan informasi yang mudah diakses.

**Performance (Kinerja)**

- Waktu respon pencarian tiket dan pemesanan tidak lebih dari 3 detik.

- Sistem dapat menangani setidaknya 10.000 pengguna secara bersamaan tanpa penurunan performa.

- Data transaksi harus tersedia untuk Tim Manajemen secara real-time.

**Scalability (Skalabilitas)**

- Sistem harus dapat diperluas untuk menambah layanan pemesanan lainnya di masa depan (misalnya, rental mobil, paket wisata).

- Sistem harus dapat menambah server atau resource lain sesuai dengan peningkatan jumlah pengguna dan transaksi.

**Security (Keamanan)**

- Semua data sensitif (seperti informasi pembayaran) harus dienkripsi selama penyimpanan dan pengiriman.

- Sistem harus mendukung otentikasi ganda (two-factor authentication) untuk proses login dan pembayaran.

- Sistem harus dapat mencegah serangan umum seperti SQL Injection, Cross-Site Scripting (XSS), dan Cross-Site Request Forgery (CSRF).

**Reliability (Keandalan)**

- Sistem harus memiliki uptime minimal 99.9%.

- Sistem harus mendukung failover untuk menjaga ketersediaan layanan jika terjadi kegagalan server.

- Sistem harus memiliki backup data harian untuk menghindari kehilangan data.

Compatibility (Kompatibilitas)

- Sistem harus dapat diakses melalui browser populer seperti Chrome, Firefox, Safari, dan Edge.

- Sistem harus mendukung berbagai resolusi layar dan kompatibel dengan perangkat mobile (responsive design).

**Maintainability (Pemeliharaan)**

- Kode sistem harus mudah di-maintain dan di-update dengan dokumentasi yang lengkap.

- Sistem harus mendukung logging dan monitoring untuk membantu dalam proses troubleshooting.

## **Dokumentasi**

### **Functional Requirements**

- Pendaftaran dan Login

- Pencarian dan Pemesanan

- Pembayaran

- Manajemen Pemesanan

- Pemberitahuan dan Notifikasi

- Manajemen Data Penerbangan, Kereta Api, dan Hotel

- Pemantauan Transaksi

- Manajemen Pengguna

- Laporan Penjualan dan Data Statistik

- Fitur Ekspor Laporan

- Pengaturan Keamanan

### **Non-Functional Requirements**

- Usability (Kemudahan Penggunaan)

- Performance (Kinerja)

- Scalability (Skalabilitas)

- Security (Keamanan)

- Reliability (Keandalan)

- Compatibility (Kompatibilitas)

- Maintainability (Pemeliharaan)
