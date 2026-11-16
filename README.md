# alanjaelani/media/pembelajaran

Platform Pembelajaran Jaringan Komputer & Telekomunikasi (TKJ / TJKT) Interaktif Berbasis Web.

---

## 📌 Ringkasan Proyek

Aplikasi web ini dirancang sebagai media pembelajaran mandiri dan interaktif untuk siswa SMK jurusan Teknik Jaringan Komputer dan Telekomunikasi (TJKT / TKJ). Dilengkapi dengan ringkasan materi kompetensi, mini simulator praktikum interaktif, kuis evaluasi berbasis skor, dan pelacak progres (progress tracking) berbasis penyimpanan lokal browser (`localStorage`).

### ✨ Fitur Utama:
1. **Dashboard Progres Terpadu**:
   - Menghitung persentase progres belajar secara otomatis.
   - Melacak penyelesaian 4 modul kompetensi inti.
   - Tombol *Reset Progres* untuk mengulang dari awal.

2. **Topik 1: Perangkat Jaringan & VLAN**:
   - Ringkasan konsep perangkat fisik (kabel UTP straight/cross, SFP fiber, switch).
   - **Mini Simulator**: Konfigurasi port switch Cisco/Managed (Access VLAN 10, Access VLAN 20, Trunk 802.1Q, Shutdown).
   - Kuis evaluasi interaktif.

3. **Topik 2: Skema IP Addressing & Routing**:
   - Konsep subnetting IPv4 (CIDR /24 - /30) dan routing protokol (OSPF, RIP, Static).
   - **Mini Simulator**: Kalkulator Subnetting interaktif & pengujian simulasi ping routing.
   - Kuis evaluasi interaktif.

4. **Topik 3: NAT, Proxy & Manajemen Bandwidth**:
   - Pembahasan NAT Masquerade, Web Proxy, dan Queue (PCQ/Simple Queue).
   - **Mini Simulator**: Slider dinamis pengaturan Simple Queue Mikrotik.
   - Kuis evaluasi interaktif.

5. **Topik 4: Metodologi Troubleshooting Jaringan**:
   - Analisis Top-Down vs Bottom-Up, deteksi gangguan fisik vs logis.
   - **Mini Simulator**: Studi kasus interaktif pemecahan masalah koneksi router.
   - Kuis evaluasi interaktif.

---

## 🚀 Cara Menjalankan

Aplikasi ini bersifat **standalone (tanpa instalasi runtime server khusus)**:
1. Buka file [index.html](file:///C:/Users/ALAN/.gemini/antigravity/scratch/alanjaelani-media-pembelajaran/index.html) langsung dengan mengklik dua kali atau klik kanan lalu pilih **Open with Google Chrome / Microsoft Edge / Firefox**.
2. Anda juga dapat menjalankannya lewat live server atau mengunggahnya ke **GitHub Pages**, **Vercel**, atau hosting pribadi.

---

## 🛠️ Teknologi yang Digunakan
- **HTML5 & Vanilla JavaScript**: Ringan, cepat, dan tidak memerlukan build tools.
- **Tailwind CSS (CDN)**: Desain dark modern bernuansa cybersecurity / networking enterprise.
- **Lucide Icons**: Ikon modern dan informatif.
- **LocalStorage API**: Menyimpan progres belajar dan nilai kuis pengguna secara lokal di browser.
