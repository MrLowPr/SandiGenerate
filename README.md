# SandiGenerate
SandiGen Ultra adalah aplikasi praktis untuk membuat dan menguji keamanan kata sandi. Dibuat dengan fokus pada privasi total dan kekuatan acak yang tidak bisa ditebak. Alih-alih menggunakan sistem acak biasa, aplikasi ini menggunakan CSPRNG (angka acak kriptografis) yang setara dengan standar perbankan dan militer.

🚀 Fitur Utama
1. Atomic Scramble (Pengacak Total)
Jika kamu memasukkan kata tertentu (misal: nama kucing atau hobi), sistem tidak akan menaruhnya secara utuh. Kata tersebut akan dipreteli per huruf dan disebar secara acak ke seluruh bagian sandi. Penyerang tidak akan menemukan pola kata aslimu sama sekali.

2. Standar Keamanan CSPRNG
Keamanan inti aplikasi ini mengandalkan window.crypto.getRandomValues(). Ini bukan sekadar angka acak matematika biasa, melainkan hasil olah data sistem komputer yang sangat acak sehingga mustahil diprediksi polanya.

3. Auditor Keamanan (Fitur Dekripsi)
Panel ini berfungsi untuk "membedah" kualitas sandi. Cukup tempel sandi apa pun, dan sistem akan langsung menghitung:

Bit Entropy: Mengukur seberapa banyak informasi unik di dalam sandi.

Crack-Time Estimation: Memberi tahu kamu berapa lama waktu yang dibutuhkan komputer untuk membobol sandi tersebut.

4. Personalisasi UI
Wallpaper Engine: Kamu bisa ganti background sesukamu langsung dari galeri.

Glassmorphism: Tampilan transparan yang modern dan nyaman di mata.

Zero-Server: Tidak ada data yang dikirim ke internet. Semua proses terjadi dan selesai di browser kamu sendiri.

🛠️ Tech Stack
Logic: Pure JavaScript (ES6+) & Web Crypto API.

Design: Tailwind CSS untuk UI yang responsif.

Icons: Lucide Icons untuk visual yang bersih.

📦 Cara Pakai
Clone repo:

Bash
git clone https://github.com/username/sandigen-ultra.git
Buka file:
Jalankan index.html di browser apa pun.

Masuk:
Gunakan akun standar: admin / admin.

🛡️ Analisis Keamanan
SandiGen Ultra dirancang untuk mematikan teknik serangan umum seperti:

Dictionary Attack: Karena kata kustom sudah dihancurkan posisinya.

Brute-Force: Dengan panjang karakter yang fleksibel hingga 100 digit.

Data Breach: Karena aplikasi ini tidak punya database; tidak ada data yang bisa dicuri dari luar.
