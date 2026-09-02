# Laporan Justifikasi Desain dan Pengembangan Website
## Rasi Dental Studio (Bandung)

### 1. Latar Belakang & Tujuan
Website ini dibuat sebagai landing page resmi untuk **Rasi Dental Studio**, sebuah studio perawatan gigi estetik yang berlokasi di Jl. Cihampelas No. 88, Bandung. 

Tujuan utama dari website ini adalah memberikan informasi yang jelas, transparan, dan terpercaya bagi calon pasien—khususnya anak muda dan mahasiswa di Bandung—yang ingin melakukan perawatan behel ortodonti, veneer gigi, maupun whitening tanpa perlu khawatir adanya biaya tersembunyi.

---

### 2. Keputusan Desain & Estetika Visual

Untuk menghasilkan tampilan yang unik, profesional, dan tidak terlihat seperti template buatan AI / generik, berikut beberapa keputusan desain yang diambil:

* **Pilihan Tipografi (Font)**:
  * Teks utama dan tombol menggunakan font **`Outfit`**, sebuah font sans-serif modern yang bersih dan sangat nyaman dibaca di layar smartphone maupun laptop.
  * Untuk aksen judul section, digunakan font serif **`Playfair Display`** (*italic*) agar memberikan sentuhan elegan dan ramah khas studio perawatan estetik.

* **Penggunaan SVG Icons (Bukan Emoji)**:
  * Seluruh emoji yang sebelumnya terkesan ramai (seperti 🏥, 💉, 💰, 🙈, ✨, 📅, 🕒) diganti menggunakan **SVG Icons** bergaris tipis. Hal ini dilakukan agar tampilan terlihat lebih bersih, higienis, dan mencerminkan standar klinik kesehatan modern.

* **Skema Warna Natural (Warm Studio)**:
  * Menggunakan warna hijau *Forest Emerald* (`#0D4736`) sebagai warna utama untuk memberikan kesan medis yang tenang dan terpercaya.
  * Latar belakang menggunakan warna *Warm Sand* (`#FAF8F5`) untuk menciptakan suasana yang hangat dan nyaman, tidak terkesan dingin seperti rumah sakit konvensional.

* **Penyelarasan Bahasa & Bahasa Komunikasi**:
  * Mengganti istilah "booking" menjadi **"Reservasi"** agar terdengar lebih sopan dan profesional dalam konteks pelayanan kesehatan.

---

### 3. Tampilan Responsif (Mobile & Desktop)

* **Tata Letak Adaptif**:
  * Menggunakan CSS Grid responsif (`grid-cols-1 md:grid-cols-2 lg:grid-cols-3`).
  * Pada layar HP, kartu layanan dan harga otomatis menyusun ke **1 kolom vertikal** dengan ukuran tombol yang besar dan mudah di-tap dengan jempol.
  * Pada layar laptop/desktop, layout melebar secara otomatis menjadi 3 kolom yang seimbang.

* **Navigasi & Kemudahan Kontak**:
  * Dilengkapi tombol melayang WhatsApp (*Floating WA*) di pojok kanan bawah agar calon pasien dapat dengan mudah menghubungi admin kapan saja.
  * Formulir reservasi terhubung secara otomatis ke nomor WhatsApp resmi studio.

---

### 4. Struktur Halaman Utama

Halaman dibuat mengalir secara sistematis untuk membangun kepercayaan calon pasien:
1. **Header & Navbar**: Menu navigasi dan tombol reservasi cepat.
2. **Hero Banner**: Penjelasan utama layanan studio, izin resmi Dinkes Bandung, dan ringkasan estimasi biaya awal.
3. **Daftar Paket & Harga**: Estimasi biaya transparan untuk behel, veneer, dan whitening lengkap dengan keterangan opsi cicilan.
4. **Pilar Kenyamanan Pasien**: Penjelasan mengenai penanganan minim nyeri, transparansi biaya, dan pelayanan ramah tanpa menghakimi.
5. **Ulasan Pasien (Google Reviews 4.9/5)**: Testimoni dari mahasiswa dan profesional di Bandung.
6. **Profil Dokter & Kredensial Medis**: Informasi mengenai dokter spesialis (alumni UNPAD & UI) serta jaminan sterilisasi alat medis (*Autoclave Class B*).
7. **Alur Kunjungan & Lokasi**: 4 langkah praktis reservasi hingga lokasi studio di Cihampelas Bandung.
8. **FAQ & Form Reservasi**: Pertanyaan umum dan form pemesanan jadwal langsung ke WA admin.

---

### 5. Aspek Teknis & Performa

* **Framework Astro v5**: Dipilih karena mampu menghasilkan halaman web yang sangat ringan dan cepat diakses di perangkat seluler (HP).
* **Optimasi SEO**: Dilengkapi meta tag Open Graph dan Structured Data (`Schema.org Dentist`) agar lokasi studio mudah ditemukan di pencarian Google Maps dan search engine.

---
**Rasi Dental Studio — Cihampelas, Bandung**
