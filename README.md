<div align="center">
  <h1>Sarana Care - Web Portal 📱</h1>
  <p><strong>Antarmuka modern & dinamis untuk pelaporan fasilitas sarana sekolah.</strong></p>

  [![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
</div>

---

## 📖 Deskripsi
Ini adalah lapisan *Frontend* (Antarmuka Pengguna) dari Ekosistem Pelaporan Sarana Care. Dirancang khusus untuk memanjakan visual pengguna dengan desain **Neumorphism & Glassmorphism**, sistem portal web ini menawarkan pendaftaran keluhan sarana prasarana dengan UX yang lebih intuitif dan transparan bagi siswa dan pengelola (admin).

## ✨ Fitur Utama
- **🎨 UI Canggih & Responsif**: Dibangun dengan `tailwindcss` dan dianimasikan penuh menggunakan `framer-motion` (Motion for React).
- **🔒 Terpusat & Independen**: Memiliki sistem routing Next.js yang terhubung langsung dengan REST API Express Backend. Stateless JWT diamankan sepenuhnya di `localStorage`.
- **📸 Kompresi & Pratinjau Gambar Langsung**: Pengaduan visual kini lebih canggih. Pengguna dapat melakukan "*Drag-and-Drop*" gambar sebelum diunggah ke backend.
- **🔔 Notifikasi & Timeline Interaktif**: Pantau keluhan dengan laporan log *tracker* ala paket e-commerce yang melacak status real-time (Pending -> Proses -> Selesai).

## 🚀 Memulai (*Getting Started*)

### 1. Instalasi
Pastikan Node.js terinstall. Jalankan perintah berikut di direktori `frontend`:
```bash
npm install
```

### 2. Konfigurasi Environment (ENV)
Hubungkan aplikasi ke server backend dengan membuat/mengubah nama file `.env.example` (jika ada) ke `.env.local`  di dalam *root folder*:
```env
NEXT_PUBLIC_API_URL=http://localhost:5000/api
```
*(Sesuaikan domain/port jika backend dikerjakan di remote server/port yang berbeda).*

### 3. Server Development
Jalankan aplikasi di environment developer:
```bash
npm run dev
```
Aplikasi secara otomatis dapat dikunjungi via [http://localhost:3000](http://localhost:3000).

---

## 🗂 Struktur Direktori
- `src/app/`: File dan konfigurasi *App Router* berbasis Next.js generasi terbaru.
- `src/components/`: Kumpulan Reusable-Components UI interaktif yang dibagi menjadi *(AuthPage, Navbar, Sidebar, ComplaintCard, dan Form)*.
- `src/components/ui/`: Komponen *design-system* (Shadcn/UI & Radix).
- `src/lib/`: Fungsi utilitas atau alias penunjang *global variable*.
- `public/`: Aset statis terbuka (Gambar vector logo aplikasi).

---
*Desain dan Pengembangan oleh Tim Sarana Care · 2026*