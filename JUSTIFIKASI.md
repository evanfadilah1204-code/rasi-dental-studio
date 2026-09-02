# DOKUMEN JUSTIFIKASI DESAIN & PENGEMBANGAN WEB
## Rasi Dental Studio — Bandung (Behel & Veneer Aesthetic Studio)

---

### 1. RINGKASAN PROYEK & TUJUAN
Proyek ini bertujuan untuk membangun website landing page modern, elegan, dan sangat terpercaya bagi **Rasi Dental Studio** di Jl. Cihampelas No. 88, Bandung. Website dirancang khusus untuk memikat calon pasien anak muda, mahasiswa, dan profesional di Bandung yang ingin melakukan perawatan gigi estetik (behel ortodonti, veneer, dan whitening) dengan transparansi estimasi biaya 100% di awal.

---

### 2. JUSTIFIKASI DESAIN & ESTETIKA (MENELIMINASI "LOOK AI")
Untuk menghindari tampilan template generic khas AI (emoji spam, warna flat mencolok, dan tata letak kaku), berikut penyesuaian estetika yang diterapkan:

1. **Sistem Tipografi Editorial & Humanis**:
   - **Heading & UI**: Menggunakan Google Font **`Outfit`** (weight 400–800) yang memiliki geometri sans-serif modern, tajam, dan mewah—standar font studio kecantikan/estetika terkini.
   - **Aksen Editorial**: Menggunakan **`Playfair Display`** (italic) pada kata kunci judul untuk memberikan impresi profesional, ramah, dan manusiawi.
   - **Pembersihan Title Highlight Formulaik**: Menghapus pola warna dua kata di akhir judul yang di-highlight hijau secara kaku (khas prompt AI), digantikan dengan tipografi serif aksen yang alami.

2. **Pembersihan Emoji & Penggunaan SVG Icons**:
   - Menghapus seluruh emoji kaku (seperti 🏥, 💉, 💰, 🙈, ✨, 📅, 🕒, 🛡️, 🎓, 📍, 💬, 🔒).
   - Menggantinya dengan **SVG Icons** bergaris tipis profesional (*Feather/Heroicons style*) untuk menjamin kesan medis yang higienis, bersih, dan tepercaya.

3. **Palet Warna "Warm Dental Studio"**:
   - **Primary**: *Deep Forest Emerald* (`#0D4736`) — Memberikan kesan tenang, medis, dan eksklusif.
   - **Background**: *Warm Sand* (`#FAF8F5`) — Menghindarkan kesan dingin/steril rumah sakit konvensional.
   - **Accent & Badges**: *Soft Sage* (`#EAF2EE`) & *Muted Gold* (`#FEF3C7`) — Memberikan hierarki visual yang lembut dan mudah dipindai mata.

---

### 3. JUSTIFIKASI TATA LETAK RESPONSIF (MOBILE & DESKTOP)
1. **Pendekatan Mobile-First & Fluid Layout**:
   - Menggunakan CSS Grid & Flexbox responsif (`grid-cols-1 md:grid-cols-2 lg:grid-cols-3`).
   - Pada layar smartphone (HP), kartu-kartu disusun menjadi **1 kolom vertikal** dengan ukuran font yang proporsional dan area sentuh tombol (*touch target*) yang nyaman di-tap dengan jempol.
   - Pada layar laptop/desktop, layout melebar secara proporsional hingga 3–4 kolom.

2. **Pengalaman Pengguna (UX) & Navigasi**:
   - Navigasi sticky header dengan menu drawer yang bersih di HP.
   - Tombol reservasi WhatsApp melayang di pojok kanan bawah yang selalu siap membantu calon pasien dari halaman mana pun.
   - Penghapusan istilah kaku dan penyelarasan kata kunci menjadi **"Reservasi"** untuk impresi layanan kesehatan yang sopan.

---

### 4. STRUKTUR KOMPONEN & STRATEGI PEMASARAN MEDIS
Website disusun menjadi 10 komponen terstruktur untuk membangun kepercayaan pasien (*Patient Trust Flow*):

1. **Navbar**: Logo studio minimalis, navigasi halaman, dan tombol reservasi.
2. **Hero Section**: Judul utama estetik, badge izin operasional Dinkes Kota Bandung, dan preview ringkasan estimasi biaya awal.
3. **Services & Pricing**: 3 paket utama (Behel Aesthetic, Veneer Porcelain/Composite, Whitening & Scaling) lengkap dengan fitur, estimasi biaya transparan, dan opsi cicilan per kontrol.
4. **Kenyamanan Pasien (Objection Handling)**: Mengatasi 3 ketakutan terbesar pasien (Takut Sakit, Takut Biaya Tersembunyi, Malu Konsultasi).
5. **Ulasan Pasien (Social Proof)**: Menampilkan rating 4.9/5 Google Reviews dan testimoni nyata dari mahasiswa & profesional di Bandung.
6. **Layanan Spesialis**: Rincian teknis penanganan ortodonti & estetika gigi.
7. **Tim DokterMedik**: Profil `drg. Kirana Ayu, Sp.Ort` & `drg. Bimo Prasetya` beserta nomor STR resmi, lulusan universitas (UNPAD & UI), serta standar sterilisasi alat (*Autoclave Class B*).
8. **Alur Kunjungan (Step-by-Step)**: 4 langkah praktis dari booking reservasi online hingga perawatan.
9. **Lokasi & Jam Operasional**: Alamat Jl. Cihampelas No. 88 Bandung, integrasi Google Maps, dan informasi parkir.
10. **FAQ Accordion & Form Reservasi**: Tanya jawab transparan dan formulir otomatis terhubung ke WhatsApp Resmi studio.

---

### 5. JUSTIFIKASI TEKNIS & PERFORMA
1. **Framework Astro v5 (Static Site Generation / SSG)**:
   - Menghasilkan 0-JavaScript overhead di client side untuk komponen statis.
   - Memastikan waktu muat halaman (*Largest Contentful Paint / LCP*) sangat cepat di koneksi HP.
2. **SEO & Structured Data**:
   - Dilengkapi meta tag Open Graph, Twitter Cards, serta `LocalBusiness Schema JSON-LD (Dentist)` untuk optimasi mesin pencari Google.

---
*Dibuat oleh Tim Pengembang Rasi Dental Studio Bandung*
