# 📄 Prompt 02 — Laporan & Panduan Belajar Lengkap

> **Kegunaan:** Mengubah materi kuliah menjadi dokumen panduan belajar komprehensif — lengkap dengan ringkasan, peta konsep, cheat sheet, dan glosarium.

---

## 📋 Prompt

```
Buat dokumen panduan belajar komprehensif dari materi ini dengan struktur berikut:

═══ BAGIAN 1: RINGKASAN EKSEKUTIF ═══
Tulis gambaran besar materi ini dalam 3-5 kalimat. Jawab: Apa ini? Kenapa penting? Kapan digunakan?

═══ BAGIAN 2: PETA KONSEP TEKS ═══
Buat hierarki konsep dalam bentuk outline bertingkat:
- Konsep Utama 1
  └── Sub-konsep A → penjelasan singkat
  └── Sub-konsep B → penjelasan singkat
(lanjutkan untuk semua konsep utama)

═══ BAGIAN 3: PENJELASAN KONSEP DASAR ═══
Untuk setiap konsep kunci, jelaskan dengan format:
• Nama Konsep: [nama]
• Definisi sederhana: [1 kalimat tanpa jargon]
• Analogi: [perumpamaan dari kehidupan sehari-hari]
• Contoh konkret: [contoh nyata atau kasus penggunaan]
• Kesalahan umum: [apa yang sering salah dipahami]

═══ BAGIAN 4: CHEAT SHEET ═══
Buat tabel ringkasan siap cetak:
| Konsep | Definisi Singkat | Contoh | Catatan Penting |

═══ BAGIAN 5: PANDUAN BELAJAR STEP-BY-STEP ═══
Susun urutan belajar yang disarankan:
Langkah 1 → [topik] → estimasi waktu: X menit
Langkah 2 → [topik] → estimasi waktu: X menit
(sertakan saran latihan atau aktivitas di setiap langkah)

═══ BAGIAN 6: GLOSARIUM ═══
Daftar semua istilah teknis penting + definisi dalam bahasa mudah dipahami, diurutkan alfabet.

Bahasa: Indonesia. Tone: seperti senior/kakak tingkat yang menjelaskan ke junior.
```

---

## 💡 Tips Penggunaan

- **Untuk materi yang sangat panjang:** Tambahkan `"Fokus pada konsep inti, skip detail teknis yang terlalu dalam"` 
- **Untuk persiapan UTS/UAS:** Tambahkan `"Tekankan bagian yang paling sering keluar di ujian"` 
- **Untuk materi pemrograman:** Tambahkan `"Sertakan contoh pseudocode atau kode di setiap konsep"`
- **Untuk materi hitungan:** Tambahkan `"Tunjukkan langkah perhitungan di setiap rumus"`

---

## 📌 Contoh Output yang Dihasilkan

```
═══ BAGIAN 1: RINGKASAN EKSEKUTIF ═══
[Topik] adalah... Konsep ini penting karena... 
Digunakan ketika...

═══ BAGIAN 2: PETA KONSEP TEKS ═══
- Konsep Utama: Algoritma Sorting
  └── Bubble Sort → membandingkan elemen berdekatan secara berulang
  └── Quick Sort → membagi array dengan pivot
  └── Merge Sort → gabungkan dua array yang sudah terurut

═══ BAGIAN 3: PENJELASAN KONSEP ═══
• Nama Konsep: Bubble Sort
• Definisi sederhana: Algoritma pengurutan yang membandingkan dua elemen bersebelahan dan menukarnya jika tidak berurutan
• Analogi: Seperti gelembung yang naik ke permukaan — elemen terbesar "menggelembung" ke posisi terakhir setiap iterasi
• Contoh: Array [5,3,1,4,2] → setelah 1 pass → [3,1,4,2,5]
• Kesalahan umum: Mengira Bubble Sort efisien untuk data besar — sebenarnya O(n²), sangat lambat

... dst
```

---

## 🔗 Prompt Terkait

- Gunakan [Prompt 01](./01-slide-presentasi.md) untuk membuat presentasi dari panduan ini
- Gunakan [Prompt 03](./03-simulasi-ujian.md) untuk membuat soal latihan dari materi ini
- Gunakan [Prompt 04](./04-tabel-data.md) untuk versi tabel yang lebih ringkas
