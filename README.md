**Dokumentasi Aplikasi: Prompt Generator Powered by AI**

### 1\. Deskripsi Aplikasi

**Prompt Generator Powered by AI** adalah sebuah aplikasi web canggih yang dirancang untuk membantu pengguna dari berbagai latar belakang dalam membuat _prompt_ (perintah teks) yang detail dan terstruktur untuk platform AI generatif. Aplikasi ini berfungsi sebagai jembatan antara ide kreatif pengguna dan hasil optimal dari AI, baik untuk pembuatan gambar maupun video.

Aplikasi ini bisa diakses melalui : [https://generatorprompt.isparmo.com/](https://generatorprompt.isparmo.com/) 

Dengan antarmuka yang intuitif, pengguna dapat dengan mudah memasukkan detail-detail spesifik sesuai kebutuhan mereka, dan AI akan menyusunnya menjadi sebuah prompt profesional yang siap digunakan pada platform seperti Midjourney, DALL-E, Google Veo, dan lainnya.

**Kategori Utama yang Didukung:**

*   Promosi Produk
    
*   Desain Packaging
    
*   Kartu Ucapan
    
*   Konten Sosial Media
    
*   Fotografi Makanan
    
*   Properti & Arsitektur
    
*   Desain Karakter
    

### 2\. Teknologi yang Digunakan

Aplikasi ini dibangun sepenuhnya sebagai _front-end application_ (berjalan di sisi klien/browser) tanpa memerlukan _backend_ khusus.

*   **Framework Utama:** React.js (dimuat melalui CDN untuk kemudahan).
    
*   **Styling:** Tailwind CSS untuk desain antarmuka yang modern, bersih, dan responsif.
    
*   **Bahasa:** HTML, CSS, dan JavaScript (JSX ditranspilasi oleh Babel di browser).
    
*   **Integrasi AI:**
    
*   **Google Gemini 1.5 Flash:** Untuk memproses input pengguna dan menghasilkan prompt teks yang detail.
    
*   **Google Gemini 2.0 Flash Image Generation:** Untuk fitur "Pratinjau Visual" yang membuat contoh gambar dari prompt yang dihasilkan.
    
*   **Penyimpanan Lokal:** Memanfaatkan localStorage browser untuk fitur "Riwayat" dan "Favorit".
    

### 3\. Target Pengguna

Aplikasi ini dirancang untuk memberdayakan berbagai kalangan pengguna, antara lain:

*   **Digital Marketer:** Untuk membuat materi promosi, iklan, dan konten kampanye.
    
*   **Manajer Sosial Media:** Untuk menghasilkan visual yang menarik untuk postingan harian.
    
*   **Desainer Grafis & Produk:** Untuk mencari inspirasi dan membuat konsep desain packaging atau karakter.
    
*   **Pemilik Usaha Kecil (UKM):** Untuk membuat materi pemasaran profesional tanpa perlu keahlian desain yang mendalam.
    
*   **Content Creator:** Untuk membuat thumbnail, ilustrasi, atau elemen visual untuk video dan blog.
    
*   **Agen Properti & Arsitek:** Untuk membuat visualisasi bangunan dan interior yang menakjubkan.
    
*   **Pengguna Umum:** Siapa saja yang ingin bereksperimen dan memaksimalkan potensi AI generatif untuk kebutuhan pribadi.
    

### 4\. Cara Menggunakan Aplikasi

Berikut adalah panduan langkah demi langkah untuk menggunakan aplikasi ini secara efektif:

1.  **Pengaturan API Key:**
    

*   Dapatkan API Key Anda dari **Google AI Studio**.
    
*   Masukkan API Key tersebut pada kolom yang tersedia di bagian "Pengaturan AI". Tanpa API Key, fitur AI tidak akan berfungsi.
    

2.  **Pilih Kategori:**
    

*   Gunakan menu dropdown "Pilih Kategori Prompt" untuk memilih tujuan Anda. Formulir akan berubah secara dinamis sesuai dengan kategori yang dipilih.
    

3.  **Isi Detail Spesifik:**
    

*   Lengkapi semua kolom pada bagian "Isi Detail". Semakin spesifik informasi yang Anda berikan, semakin akurat dan relevan prompt yang akan dihasilkan.
    

4.  **Atur Pengaturan Umum:**
    

*   Pilih output yang diinginkan: **Gambar/Foto** atau **Video**.
    
*   Tentukan **Nada Suara (Tone of Voice)** dan **Gaya Visual** dari dropdown. Jika pilihan yang ada tidak sesuai, pilih "Lainnya..." dan ketik sendiri gaya yang Anda inginkan.
    

5.  **Lakukan Pengaturan Spesifik:**
    

*   **Untuk Gambar:** Pilih aspek rasio dari tombol ikon yang tersedia atau ketik rasio kustom Anda sendiri (misal: 2:3).
    
*   **Untuk Video:** Isi detail mengenai karakter dan dialog yang akan muncul dalam video.
    

6.  **Hasilkan Prompt:**
    

*   Klik tombol **"Buat Detail Prompt dengan AI"**. Aplikasi akan mengirimkan semua informasi Anda ke AI dan menghasilkan prompt dalam beberapa saat.
    

7.  **Gunakan Hasilnya:**
    

*   **Lihat Hasil:** Prompt akan tersedia dalam versi Bahasa Indonesia dan Inggris di panel kanan.
    
*   **Salin & Simpan:** Gunakan tombol "Salin Teks" untuk menyalin ke clipboard atau "Simpan ke File" untuk mengunduhnya sebagai file .txt.
    
*   **Pratinjau Visual:** Klik "Pratinjau Gambar" untuk melihat contoh hasil visual dari prompt Anda (hanya untuk output gambar).
    

8.  **Manfaatkan Fitur Tambahan:**
    

*   **Riwayat:** Klik tombol "Riwayat" untuk melihat, memuat ulang, atau memfavoritkan prompt yang pernah Anda buat.
    
*   **Bantuan & Kontak:** Gunakan tombol "Bantuan" untuk panduan atau "Laporkan Error" jika Anda menemukan masalah.
    

### 5\. Usulan 5 Ide Pengembangan Fitur

Untuk membuat aplikasi ini lebih hebat di masa depan, berikut adalah 5 ide pengembangan fitur:

1.  **Integrasi Multi-Model:** Menambahkan pilihan untuk menggunakan model AI lain selain Gemini, misalnya DALL-E 3 dari OpenAI atau Stable Diffusion, memberikan pengguna fleksibilitas untuk membandingkan hasil.
    
2.  **Analisis & Peringkat Prompt:** Fitur di mana pengguna bisa mengetik prompt mereka sendiri, dan AI akan memberikan skor serta saran perbaikan untuk meningkatkan kualitasnya.
    
3.  **Manajemen Proyek Berbasis Folder:** Daripada satu daftar riwayat, pengguna bisa membuat folder-folder proyek (misal: "Kampanye Lebaran", "Konten Instagram Harian") untuk mengorganisir prompt mereka dengan lebih baik.
    
4.  **Fitur Kolaborasi Tim:** Kemampuan untuk membagikan sebuah prompt yang telah dibuat melalui tautan unik, memungkinkan anggota tim lain untuk melihat, memberi komentar, atau bahkan menyempurnakan prompt tersebut.
    
5.  **"Rantai Prompt" (Prompt Chaining):** Fitur lanjutan di mana pengguna bisa membuat serangkaian prompt yang saling berhubungan. Misalnya, prompt pertama untuk membuat desain karakter, dan prompt kedua secara otomatis menggunakan deskripsi karakter tersebut untuk menempatkannya dalam sebuah adegan cerita.
