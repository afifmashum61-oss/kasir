# Kasirku POS - Aplikasi Kasir Modern

Aplikasi Kasir (Point of Sale / POS) berbasis web modern dengan tampilan antarmuka visual (UI/UX) presisi terinspirasi dari aplikasi pemesanan & layanan profesional modern (skema warna hijau-putih bersih, rounded cards, ikon kategori, promo banner, keranjang belanja, kalkulator tunai & QRIS, cetak struk thermal, riwayat transaksi, serta laporan penjualan).

## 🚀 Cara Menjalankan Aplikasi

Ada dua cara mudah untuk menjalankan aplikasi ini:

### Cara 1: Langsung Buka di Browser (Tanpa Server)
1. Buka folder `C:\Users\HP\.gemini\antigravity\scratch\kasir-app`.
2. Klik ganda file `index.html` untuk langsung membukanya di browser favorit Anda (Google Chrome, Edge, Safari, Firefox).

### Cara 2: Menjalankan Local Web Server
1. Jalankan perintah berikut di terminal:
   ```bash
   node server.js
   ```
2. Buka peramban di alamat: **[http://localhost:3000](http://localhost:3000)**

---

## ✨ Fitur-Fitur Utama

1. **Dual Device View Toggle**:
   - Mode Smartphone (Frame iPhone seperti pada gambar referensi).
   - Mode Full Screen Desktop / Tablet Kasir.
2. **Katalog Produk & Layanan Interaktif**:
   - Filter berdasarkan 8 Kategori (House Cleaning, AC Repair, Plumbing, Electrical, Washing Machine, Refrigerator, Microwave, More Services).
   - Pencarian real-time (*Search Bar*).
   - Kartu produk lengkap dengan rating, durasi/stok, harga normal, harga diskon, dan badge *Verified Professional* & *Bestseller*.
3. **Keranjang Belanja (Cart Drawer)**:
   - Pengaturan jumlah kuantitas (`+` / `-`).
   - Catatan khusus per item.
   - Pemasangan kupon promo (`PROMO20` untuk diskon 20%, `KASIR10` untuk 10%).
   - Hitung otomatis Subtotal, Diskon, PPN 11%, dan Grand Total.
4. **Kalkulator Pembayaran Kasir**:
   - **Tunai**: Tombol cepat nominal uang pas, Rp 50.000, Rp 100.000, Rp 1.000.000, serta perhitungan uang kembalian otomatis.
   - **QRIS**: Tampilan QR Code scan interaktif untuk pembayaran via GoPay/OVO/ShopeePay/DANA.
   - **Debit/Kredit & Transfer Bank**.
5. **Cetak Struk Thermal (Receipt Printer)**:
   - Struk kasir dengan nomor transaksi otomatis (`#TRX-XXXXXX`), tanggal, rincian produk, diskon, PPN, nominal diterima & kembalian.
   - Siap dicetak langsung ke printer thermal 58mm/80mm atau diunduh sebagai PDF (`Ctrl + P`).
6. **Riwayat Pesanan & Transaksi (Bookings)**:
   - Daftar transaksi tersimpan lengkap dengan opsi Cetak Ulang Struk.
7. **Laporan & Analytics (Support)**:
   - Ringkasan total omset harian, total transaksi, dan *Average Order Value (AOV)*.
8. **Kelola Produk (Account / Inventory)**:
   - Tambah produk/layanan baru, edit harga & stok, serta hapus produk dengan penyimpanan otomatis di `localStorage`.
