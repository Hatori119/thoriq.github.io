# 🎨 Portofolio Muhammad Thoriqull Rizqy

Portofolio web statis bergaya **Retro OS + Creative Scrapbook** milik Muhammad Thoriqull Rizqy — siswa SMK Negeri 10 Surabaya, jurusan Desain Komunikasi Visual (DKV).

Dibangun dengan satu file HTML, Tailwind CSS (CDN), dan JavaScript murni. Tidak memerlukan build tool atau server khusus.

---

## ✨ Fitur Utama

### 🪪 Hero & Identitas
- **Kartu ID interaktif** dengan foto formal, status `OPEN TO WORK`, dan efek ayunan
- **Kartu bisa dibalik (3D flip)** dengan klik / tekan `Enter` / `Spasi` untuk menampilkan QR Instagram
- **Quick Contact** — nomor WhatsApp dan email bisa disalin sekali klik
- **Status ketersediaan** dengan titik berkedip dan jam real-time WIB (UTC+7)
- **Soft skills** lengkap dengan penjelasan singkat, tersusun rapi ke bawah

### 📚 Profil & Keahlian
- Timeline pendidikan (SMK, SMP, SD) dengan catatan fokus belajar
- 9 tools kreatif: Illustrator, Blender, UI/UX, Sketsa, Canva, After Effects, Premiere Pro, CapCut, Figma
- Pengalaman & pencapaian (kompetisi, proyek klien, seleksi lomba 3D)

### 🏢 Pengalaman PKL
- **Periode 1** — Program Design ITS Tekno Sains Academy (Feb–Apr 2026), dokumentasi 2 foto polaroid
- **Periode 2** — Faculty Design Creativity & Business Digital (Jul–Okt 2026), dokumentasi 1 foto polaroid

### 🖼️ My Projects
- 15 karya dalam 4 kategori: Desain 3D, Desain Grafis & UI, Seni Lukis & Sketsa, Video Graphic
- Filter kategori interaktif
- Lightbox modal untuk detail proses, tools, dan deskripsi lengkap
- Pemutar video MP4 langsung di browser

### 📄 Unduhan & Kontak
- Download CV (PDF) dengan animasi dan notifikasi toast
- Download sertifikat PRODES (`sertifikat-torik-bener-1.png`)
- Download sertifikat FDKBD (`sertifikat-magang-Thoriq-1-F.png`)
- Tombol WhatsApp dan email di footer

---

## 🛠️ Teknologi

| Komponen | Keterangan |
|---|---|
| HTML5 | Struktur halaman (satu file `index.html`) |
| Tailwind CSS | Styling via CDN `cdn.tailwindcss.com` |
| JavaScript | Filter, modal, flip kartu, jam WIB, toast, salin teks |
| Google Fonts | Press Start 2P, Space Grotesk, Space Mono |
| CSS kustom | Animasi ayun, kedip, flip 3D, efek kertas & masking tape |

Tidak ada dependensi `npm`, `package.json`, atau proses build.

---

## 📁 Struktur Folder

```
porofolio-thoriq/
├── index.html                          # Halaman utama (semua konten & logika)
├── README.md                           # Dokumentasi ini
│
├── Aset yang dipakai index.html
│   ├── Foto-Formal-Thoriq.jpeg
│   ├── QR-IG.png
│   ├── Prodes-1.jpg, Prodes-2.jpg
│   ├── DOKUMENTASI-MAGANG.jpeg
│   ├── Logo-Blender.jpg, Logo-Canva.jpeg, Logo-CapCut.png, Logo-Figma.png
│   ├── 3D-Character-*.png, 3D-Gerobak-Ramen.png, 3D-Ruang-Rumah.png, 3D-Tangan-Blender.png
│   ├── Group-*.jpeg, Sablon-*.jpeg, MODUL-3-*.jpg, Harvest-Tiga-Perkasa.jpg
│   ├── Logo-AE-SABER.mp4, Video-opticalflare.mp4
│   ├── sertifikat-torik-bener-1.png
│   ├── sertifikat-magang-Thoriq-1-F.png
│   └── CV-M-Thoriqull Rizqy-1.pdf
│
└── assets-cadangan/                    # Aset cadangan (belum dipakai halaman)
    ├── Desain Kemerdekaan Thoriq-1-01.png
    ├── Design-Kemerdekaan-Belakang-1-02.png
    ├── NUSANTARA-COFFE.mp4
    ├── sertifikat-torik-bener-2.png
    └── sertifikat-magang-Thoriq-2-F.png
```

> Semua path relatif, jadi cukup upload seluruh folder apa adanya — tidak perlu mengubah kode.

---

## 🚀 Cara Menjalankan

### Opsi 1 — Langsung dibuka
Klik dua kali `index.html` di browser.

### Opsi 2 — Server lokal (disarankan)
```bash
# Python 3
python -m http.server 8000
```
Lalu buka `http://localhost:8000`.

Server lokal disarankan agar video MP4 dan file PDF ter-load dengan baik di semua browser.

---

## 🌐 Deploy ke GitHub Pages

1. Buat repository baru di GitHub (misalnya `portofolio-thoriq`).
2. Upload semua file dan folder di atas ke repository (boleh lewat **Add file → Upload files** di GitHub Web).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` / `(root)`
5. Simpan, lalu tunggu beberapa menit.
6. Situs akan tersedia di `https://<username>.github.io/portofolio-thoriq/`.

Catatan: semua tautan di `index.html` sudah relatif, sehingga aman dipakai di GitHub Pages (path `/repo/`).

---

## 📞 Kontak

- **WhatsApp:** +62 857-3284-4066
- **Email:** rizqy3492@gmail.com
- **Lokasi:** Sukolilo, Kota Surabaya, Jawa Timur 60118
- **Instagram:** scan QR pada kartu ID di halaman utama

---

## 📄 Lisensi

Konten dan desain dibuat oleh Muhammad Thoriqull Rizqy. Silakan dilihat sebagai referensi; penggunaan kembali karya secara komersial memerlukan izin pemilik.

---

<div align="center">

Dibuat dengan estetika **Retro OS** &amp; **Creative Scrapbook** ✨

</div>
