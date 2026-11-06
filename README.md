🚀 SiKerja



SiKerja adalah sebuah workspace personal dan pusat kumpulan mini-tools berbasis web yang dirancang khusus untuk eksperimen dan efisiensi kerja. Berawal dari proyek pengisi waktu luang, repositori ini berkembang menjadi hub untuk berbagai aplikasi yang mempermudah pencatatan operasional sehari-hari.
🌍 Live Apps: pekerja.netlify.id
💡 Motivasi Proyek
Proyek ini dibangun dengan prinsip "Kerja Cerdas, Bukan Hanya Kerja Keras".
Sistem operasional terkadang membutuhkan alat pencatatan yang cepat dan spesifik. Daripada mengandalkan catatan manual yang rawan hilang atau aplikasi pihak ketiga yang terlalu rumit, SiKerja hadir sebagai wadah eksperimen untuk menciptakan tools mandiri yang ringan, mudah diakses, dan langsung menyelesaikan inti permasalahan di lapangan.
✨ Fitur & Modul Utama
Di dalam repositori ini, terdapat beberapa alat yang sudah dan sedang dikembangkan:
 * 📦 Stock Opname (SO) Tracker
   Sistem pencatatan barang instan yang mendukung multi-satuan (Pack, Pcs, Dus/Box). Dilengkapi dengan fitur pencarian nama barang dan export data.
 * 🗂️ Database Produk & Logistik
   Penyimpanan data barang sederhana untuk mengecek ketersediaan dan detail produk dengan cepat.
 * ⚡ Offline-First & Local Caching
   Sebagian besar alat di sini mengandalkan LocalStorage pada browser, sehingga data tetap aman tersimpan sementara tanpa perlu koneksi database eksternal yang lambat.
 * 📱 Mobile-Optimized
   Desain antarmuka difokuskan untuk penggunaan di layar smartphone, memudahkan pencatatan sambil terus bergerak (mobilitas tinggi).
🛠️ Teknologi yang Digunakan
SiKerja dibangun menggunakan stack yang ringan dan cepat untuk memfasilitasi pembuatan ide seketika:
 * HTML5 & CSS3 (Vanilla / Tailwind CSS untuk styling cepat)
 * Vanilla JavaScript (ES6+)
 * Web Storage API (LocalStorage) untuk persistensi data klien
 * Netlify untuk continuous deployment dan hosting
🚀 Cara Menjalankan Secara Lokal
Jika ingin mengkloning dan menjalankan proyek ini di perangkatmu sendiri untuk bereksperimen:
 * Clone repositori ini:
   git clone https://github.com/username/sikerja.git

 * Masuk ke direktori proyek:
   cd sikerja

 * Jalankan aplikasi:
   Tidak perlu install dependencies yang rumit. Cukup buka file index.html (atau modul spesifik yang ingin dites) langsung di browser pilihanmu, atau gunakan ekstensi seperti Live Server di VS Code.
📂 Struktur Direktori
sikerja/
├── index.html          # Halaman utama / Hub navigasi
├── css/                # File styling global
├── js/                 # Script logika utama
├── modules/            # Kumpulan aplikasi spesifik
│   ├── stock-opname/   # Aplikasi SO
│   └── data-produk/    # Aplikasi pendataan produk
└── assets/             # Ikon, gambar, dll

📝 Lisensi
Proyek ini bersifat terbuka untuk eksperimen pribadi. Jangan ragu untuk menjadikannya referensi jika kamu memiliki kebutuhan operasional yang serupa!
Dibuat untuk mempermudah hidup saat jam kerja. ☕
