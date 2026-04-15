# 📝 Prompt 03 — Simulasi Ujian Kampus

> **Kegunaan:** Membuat soal ujian simulasi lengkap dengan 4 tipe soal (pilihan ganda, benar/salah, isian, essay) mirip format ujian komputer di kampus — lengkap dengan kunci jawaban dan pembahasan.

---

## 📋 Prompt

```
Buat soal ujian simulasi berdasarkan materi ini. Format seperti ujian komputer resmi di kampus.

INSTRUKSI SOAL:
Waktu: 90 menit | Total: 50 poin

━━━ BAGIAN A: PILIHAN GANDA (20 soal × 1 poin) ━━━
Tingkat kesulitan bertahap:
- Soal 1-7: Mudah (definisi, fakta langsung, konsep dasar)
- Soal 8-14: Sedang (aplikasi konsep, analisis)
- Soal 15-20: Sulit (evaluasi, kasus kompleks, gabungan konsep)

Format tiap soal:
[Nomor]. [Pertanyaan yang spesifik dan jelas]
A) [pilihan]   B) [pilihan]   C) [pilihan]   D) [pilihan]

Hindari pilihan seperti "semua benar" atau "tidak ada jawaban yang benar".
Buat semua pilihan terdengar masuk akal (distractors yang kuat).

━━━ BAGIAN B: BENAR/SALAH + KOREKSI (10 soal × 1 poin) ━━━
Tulis pernyataan. Jika salah, siswa harus mengoreksi kata/frasa yang salah.
Format: [Nomor]. [Pernyataan] → (Benar / Salah, koreksi: ___)

━━━ BAGIAN C: ISIAN SINGKAT (5 soal × 2 poin) ━━━
Pertanyaan yang jawabannya 1-3 kata atau 1 rumus/definisi.

━━━ BAGIAN D: ESSAY / URAIAN (3 soal × 10 poin) ━━━
Soal yang menguji pemahaman mendalam dan kemampuan menjelaskan:
- 1 soal: Jelaskan konsep dan berikan contoh penerapan
- 1 soal: Analisis atau bandingkan 2 hal
- 1 soal: Studi kasus atau soal hitungan (jika ada)

━━━ KUNCI JAWABAN & PEMBAHASAN ━━━
Setelah semua soal, berikan:
• Kunci jawaban lengkap (A-D untuk pilihan ganda)
• Pembahasan singkat untuk setiap soal yang mungkin membingungkan
• Untuk essay: contoh jawaban ideal + kriteria penilaian

Catatan: buat soal yang benar-benar menguji pemahaman, bukan sekadar hafalan.
```

---

## 💡 Tips Penggunaan

- **Untuk 1 topik spesifik:** Tambahkan `"Fokus hanya pada topik [nama topik]"` di awal prompt
- **Untuk tingkat kesulitan lebih tinggi:** Ganti distribusi menjadi `"Soal 1-5: Mudah, Soal 6-14: Sedang, Soal 15-20: Sulit"`
- **Untuk mata kuliah pemrograman:** Tambahkan `"Sertakan soal trace kode dan analisis output program"`
- **Untuk waktu ujian berbeda:** Ganti `"Waktu: 90 menit"` sesuai ujian kampusmu (60/120 menit)
- **Minta soal baru:** Setelah dapat soal pertama, ketik `"Buat set soal baru dengan soal yang berbeda"` untuk variasi

---

## 📌 Contoh Format Output

```
UJIAN SIMULASI — [NAMA MATA KULIAH]
Waktu: 90 Menit | Total Nilai: 50 Poin
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

BAGIAN A — PILIHAN GANDA (20 × 1 poin)

1. Apa yang dimaksud dengan [konsep]?
   A) Definisi salah tapi masuk akal
   B) Definisi yang benar ✓
   C) Definisi yang mirip tapi berbeda
   D) Definisi yang jauh salah

2. [Soal tingkat sedang — aplikasi konsep]
   A) ...  B) ...  C) ...  D) ...

...

BAGIAN D — ESSAY (3 × 10 poin)

1. (10 poin) Jelaskan perbedaan antara [konsep A] dan [konsep B]. 
   Berikan masing-masing 2 contoh penerapan dalam dunia nyata!

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
KUNCI JAWABAN

Bagian A: 1-B, 2-C, 3-A, 4-D, ...

Pembahasan No.5: 
Jawaban B benar karena... Pilihan A salah karena...
```

---

## 🔗 Prompt Terkait

- Belum paham materinya? Gunakan [Prompt 02](./02-laporan-panduan.md) dulu untuk belajar
- Butuh tabel rangkuman rumus sebelum ujian? Gunakan [Prompt 04](./04-tabel-data.md)
