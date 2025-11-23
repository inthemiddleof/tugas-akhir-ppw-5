# 🧮 Kalkulator

Aplikasi Kalkulator berbasis web dengan desain antarmuka **Neo-Brutalism** yang unik, modern, dan responsif. Dibangun menggunakan HTML, Tailwind CSS, dan Vanilla JavaScript murni tanpa build tools yang rumit.

## ✨ Fitur Utama

### 🎨 Desain & Antarmuka

- **Gaya Neo-Brutalism:** Menggunakan garis tepi tebal, bayangan keras (_hard shadows_), dan warna kontras tinggi untuk estetika retro-modern.
- **Single-File Deployment:** Seluruh kode (HTML, CSS, JS) digabung dalam satu file `index.html` agar mudah dijalankan di mana saja.
- **Responsive:** Tampilan menyesuaikan diri dengan baik di desktop maupun layar sentuh (mobile).
- **Font Monospace:** Menggunakan Google Font 'Space Mono' untuk kesan teknikal.

### 🧠 Logika & Fungsionalitas

- **Smart Calculation (KABATAKU):** Menghormati urutan operasi matematika.
  - _Contoh:_ `5 + 5 × 2` akan menghasilkan `15` (bukan 20).
- **Operasi Berantai:** Menampilkan seluruh persamaan yang sedang diketik (misal: `10 + 20 ÷ 5`) di layar atas.
- **Penanganan Error:** Mencegah pembagian dengan nol dan input yang tidak valid.
- **Bilangan Negatif:** Dukungan penuh untuk operasi bilangan negatif menggunakan tombol `+/-`.

### 🛠️ Alat Tambahan

- **Riwayat (History):** Menyimpan 10 perhitungan terakhir. Riwayat dapat diakses melalui tombol jam, dan item riwayat bisa diklik untuk digunakan kembali.
- **Memori (M+, M-, MR, MC):** Fitur standar kalkulator untuk menyimpan nilai sementara.

## 🚀 Cara Menjalankan

1.  **Download** file `index.html`.
2.  **Klik dua kali** file tersebut untuk membukanya di browser favorit Anda (Chrome, Firefox, Safari, Edge).
3.  **Selesai!** Aplikasi siap digunakan (pastikan terkoneksi internet saat pertama kali membuka untuk memuat Tailwind CSS & Font).

## ⌨️ Dukungan Keyboard (Shortcuts)

Aplikasi ini mendukung input keyboard penuh untuk produktivitas:

| Tombol Keyboard    | Fungsi                        |
| :----------------- | :---------------------------- |
| `0` - `9`          | Memasukkan Angka              |
| `.`                | Desimal                       |
| `Enter` atau `=`   | Hitung Hasil (=)              |
| `Backspace`        | Hapus satu karakter (⌫)       |
| `Esc`              | Clear All (C) / Tutup History |
| `+`, `-`, `*`, `/` | Operasi (+, -, ×, ÷)          |
| `n` atau `_`       | Negasi / Minus (+/-)          |

## 🛠️ Teknologi yang Digunakan

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Tailwind CSS](https://tailwindcss.com/)
- [JavaScript (ES6+)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [FontAwesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)

## 🎨 Kustomisasi Warna

Jika Anda ingin mengubah tema warna, cari kode Hex berikut di dalam file `index.html` dan ubah sesuai selera:

- **Latar Belakang:** `#f3f4f6` (Ubah di tag `body`)
- **Warna Aksen (Pink):** `#ff90e8` (Tombol C, CE, Delete)
- **Warna Aksen (Kuning):** `#ffc900` (Operator)
- **Layar (Hitam/Hijau):** `bg-black`, `text-[#00FF41]`

---
