# 📓 NotebookLM Prompt Pack

> Koleksi prompt siap pakai untuk memaksimalkan NotebookLM sebagai alat belajar mahasiswa — dari slide presentasi, dokumen panduan, simulasi ujian, hingga tabel referensi.

<p align="center">
  <img src="https://img.shields.io/badge/NotebookLM-Compatible-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Bahasa-Indonesia-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Ready%20to%20Use-22c55e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Prompts-4%20Pack-orange?style=for-the-badge" />
</p>

---

## ✨ Apa Ini?

Repo ini berisi **4 prompt yang sudah dioptimasi** untuk digunakan di [Google NotebookLM](https://notebooklm.google.com/). Cukup upload materi kuliah kamu, lalu paste salah satu prompt ini — dan NotebookLM akan menghasilkan output yang jauh lebih terstruktur, informatif, dan siap digunakan.

---

## 🗂️ Daftar Prompt

| # | Prompt | Kegunaan | File |
|---|--------|----------|------|
| 01 | 🎨 **Slide Presentasi** | Buat slide dengan tema minimalis retro, visual enak dilihat | [`prompts/01-slide-presentasi.md`](./prompts/01-slide-presentasi.md) |
| 02 | 📄 **Laporan & Panduan Belajar** | Dokumen lengkap: ringkasan, peta konsep, cheat sheet, glosarium | [`prompts/02-laporan-panduan.md`](./prompts/02-laporan-panduan.md) |
| 03 | 📝 **Simulasi Ujian** | Soal ujian 4 tipe seperti ujian kampus + kunci jawaban | [`prompts/03-simulasi-ujian.md`](./prompts/03-simulasi-ujian.md) |
| 04 | 📊 **Tabel Data & Referensi** | Ekstrak materi jadi 6 jenis tabel terstruktur | [`prompts/04-tabel-data.md`](./prompts/04-tabel-data.md) |

---

## 🚀 Cara Pakai

### Langkah-langkah:

```
1. Buka  →  https://notebooklm.google.com/
2. Upload materi kuliah kamu (PDF, slide, dokumen, dll.)
3. Buka file prompt yang kamu butuhkan dari folder /prompts
4. Copy seluruh isi prompt
5. Paste di kolom chat NotebookLM
6. Tekan Enter — dan tunggu hasilnya ✨
```

### Tips Penggunaan:

- **Satu materi, banyak prompt** — kamu bisa pakai semua 4 prompt pada satu materi yang sama untuk hasil maksimal
- **Kustomisasi prompt** — setiap prompt bisa dimodifikasi, misalnya tambahkan `"Fokus hanya pada topik X"` di awal
- **Urutan yang disarankan:** Mulai dari Prompt 02 (pahami materi) → 01 (presentasi) → 03 (latihan ujian) → 04 (referensi cepat)

---

## 📁 Struktur Folder

```
notebooklm-prompt-pack/
│
├── README.md                    ← kamu di sini
│
└── prompts/
    ├── 01-slide-presentasi.md   ← prompt slide presentasi
    ├── 02-laporan-panduan.md    ← prompt laporan & panduan belajar
    ├── 03-simulasi-ujian.md     ← prompt simulasi ujian kampus
    └── 04-tabel-data.md         ← prompt tabel data & referensi
```

---

## 🎯 Cocok Untuk

- 📚 Mahasiswa yang ingin belajar lebih efisien
- 🎓 Persiapan ujian tengah/akhir semester
- 📊 Membuat materi presentasi dari modul kuliah
- 🔍 Merangkum buku teks atau jurnal yang panjang
- 💡 Siapa saja yang ingin memaksimalkan NotebookLM

---

## 📋 Preview Output

<details>
<summary><b>01 — Slide Presentasi</b> (klik untuk expand)</summary>

Output yang dihasilkan:
- Slide cover dengan judul dan info mata kuliah
- Slide daftar isi visual
- Slide konten per topik (max 5 poin/slide)
- Slide diagram atau tabel jika relevan
- Slide ringkasan poin kunci
- Slide penutup + pertanyaan diskusi

Tema: minimalis retro (krem, cokelat tua, aksen amber)

</details>

<details>
<summary><b>02 — Laporan & Panduan Belajar</b> (klik untuk expand)</summary>

Output yang dihasilkan:
- Ringkasan eksekutif (gambaran besar materi)
- Peta konsep dalam format outline bertingkat
- Penjelasan tiap konsep + analogi + contoh
- Cheat sheet dalam bentuk tabel siap cetak
- Panduan belajar step-by-step + estimasi waktu
- Glosarium istilah teknis

</details>

<details>
<summary><b>03 — Simulasi Ujian</b> (klik untuk expand)</summary>

Output yang dihasilkan:
- **Bagian A:** 20 soal pilihan ganda (mudah → sulit)
- **Bagian B:** 10 soal benar/salah + koreksi
- **Bagian C:** 5 soal isian singkat
- **Bagian D:** 3 soal essay/uraian mendalam
- Kunci jawaban + pembahasan lengkap

</details>

<details>
<summary><b>04 — Tabel Data & Referensi</b> (klik untuk expand)</summary>

Output yang dihasilkan:
- Tabel perbandingan konsep/metode
- Tabel rumus & formula
- Tabel timeline/kronologi
- Matriks perbandingan cepat (✓/✗/~)
- Tabel panduan pengambilan keputusan
- Tabel glosarium istilah

</details>

---

## 🤝 Kontribusi

Punya prompt yang lebih baik atau ide tambahan? Pull request selalu disambut!

1. Fork repo ini
2. Buat branch baru: `git checkout -b improve/nama-prompt`
3. Commit perubahan: `git commit -m "improve: deskripsi perubahan"`
4. Push dan buat Pull Request

---

## 📄 Lisensi

[MIT License](./LICENSE) — bebas digunakan, dimodifikasi, dan dibagikan.

---

<p align="center">
  Dibuat dengan ☕ untuk mahasiswa Indonesia yang mau belajar lebih efisien.<br/>
  <i>Star ⭐ repo ini kalau bermanfaat!</i>
</p>
