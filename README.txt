FINTRACK — Paket aplikasi web untuk iPhone

FILE
- index.html: aplikasi FinTrack
- manifest.json: metadata instalasi web app
- sw.js: cache aset agar aplikasi dapat dibuka saat offline setelah dimuat

CARA MENJALANKAN / MEMASANG DI IPHONE
1. Untuk uji coba cepat, buka index.html di browser komputer.
2. Agar dapat ditambahkan ke Home Screen iPhone sebagai web app, unggah isi folder ini ke layanan hosting statis yang mendukung HTTPS (misalnya GitHub Pages atau layanan hosting statis lain).
3. Buka URL HTTPS hasil hosting di Safari pada iPhone.
4. Tekan tombol Share (ikon kotak dengan panah ke atas), pilih “Add to Home Screen / Tambahkan ke Layar Utama”, lalu tekan Add.
5. Buka ikon FinTrack dari Home Screen.

PENYIMPANAN & PRIVASI
- Transaksi disimpan di localStorage browser pada perangkat yang digunakan.
- Data tidak otomatis tersinkronisasi antarperangkat.
- Menghapus data situs/browser dapat menghapus catatan. Gunakan menu Grafik untuk mengekspor CSV atau membuat cadangan JSON secara berkala.
- Jangan gunakan mode Private Browsing untuk pencatatan permanen.
- Ini adalah aplikasi pencatatan manual, bukan aplikasi bank; saldo dihitung dari transaksi yang dimasukkan.
