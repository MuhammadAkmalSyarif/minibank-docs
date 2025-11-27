Mini Bank - Aplikasi Keuangan Digital
Aplikasi layanan keuangan digital (Web dan Mobile) yang dirancang untuk memfasilitasi transaksi perbankan dasar bagi nasabah secara efisien, aman, dan tersedia 24/7. Sistem ini berfokus pada pengalaman pengguna yang intuitif, keamanan data yang kuat, serta kepatuhan terhadap regulasi keuangan.

1. Deskripsi Proyek
Mini Bank adalah platform perbankan digital yang menyediakan solusi self-service untuk kebutuhan keuangan harian. Aplikasi ini bertujuan mendigitalisasi layanan dasar bank, memungkinkan nasabah untuk mengelola rekening, melakukan transfer, dan membayar tagihan melalui perangkat mereka secara real-time.

Fitur utama:
Pendaftaran dan Autentikasi: Proses Onboarding Nasabah (KYC Digital) dan login multi-faktor (Username/Password, Biometrik, OTP).

Akses Rekening Real-time: Menampilkan saldo terkini dan riwayat transaksi secara instan.

Transfer Dana: Transfer dana antar-bank, ke sesama Mini Bank, dan integrasi dengan Dompet Digital (E-Wallet).

Pembayaran Tagihan: Layanan pembayaran untuk berbagai tagihan (Listrik, Air, Internet, Pulsa, dll.) dengan fitur pembayaran berulang otomatis.

Laporan Keuangan: Generasi laporan mutasi rekening bulanan dalam format PDF atau CSV.

Keamanan Data: Enkripsi data standar industri dan pemantauan transaksi untuk deteksi anomali (fraud detection).

Dukungan Pelanggan: Fitur live chat atau helpdesk terintegrasi dalam aplikasi untuk bantuan 24/7.

Tujuan utama: Mendigitalisasi layanan perbankan dasar, meningkatkan efisiensi operasional bank, dan memberikan kemudahan bertransaksi yang aman dan terjamin bagi nasabah.

2. Arsitektur Sistem
Mini Bank menggunakan arsitektur Microservices modern untuk memastikan skalabilitas, ketahanan, dan kemudahan dalam pengembangan fitur. Arsitektur ini memisahkan komponen utama sebagai berikut: Mobile/Web Frontend, API Gateway, Core Banking Services, Security & Authentication Service, dan Database Cluster.

Alur kerja sistem (Contoh: Proses Transfer Dana Antar-Bank):
Frontend Memulai Transaksi: Pengguna memasukkan detail transfer (bank tujuan, nomor rekening, nominal) melalui aplikasi Frontend (Mobile/Web).

Validasi Backend: Permintaan diterima oleh API Gateway dan diteruskan ke Core Banking Service. Layanan memvalidasi format data dan mengecek batas transaksi (limit harian).

Verifikasi Keamanan: Security Service memproses permintaan otorisasi (misalnya, verifikasi PIN Transaksi atau OTP).

Pengecekan dan Debit Saldo: Core Banking Service mengecek ketersediaan dana di Database Transaksional. Jika dana cukup, dana didebit sementara (hold) dari rekening pengirim.

Pemrosesan Kliring: Core Banking Service mengirim instruksi transfer ke Payment Gateway atau Sistem Kliring (misalnya BI-FAST/SKN/RTGS).

Pencatatan Transaksi: Setelah konfirmasi keberhasilan dari Payment Gateway, status transaksi dicatat sebagai Success di Database Transaksional dan saldo diperbarui secara permanen.

Respon ke Frontend: Core Banking Service mengirimkan notifikasi status transaksi (berhasil/gagal) dan bukti transaksi (e-receipt) kembali ke Frontend.

3. Team Member
   1.Muhammad Naufal Fauza1n
     https://www.linkedin.com/in/naufal-fauzan-121b80248/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
   2.Muhammad Akmal Syarif
     https://www.linkedin.com/in/muhammad-akmal-syarif-063898396/
   3.Siti Tahtia Ainun Zahra
     https://www.linkedin.com/in/ainun-zahra-73a877392?utm_source=share_via&utm_content=profile&utm_medium=member_android
   4.Rackisha Dhia Ezelly Lathief
     https://www.linkedin.com/in/rackishaaa-e-511886321/
