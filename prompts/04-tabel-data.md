# 📊 Prompt 04 — Tabel Data & Referensi Cepat

> **Kegunaan:** Mengekstrak materi kuliah menjadi 6 jenis tabel terstruktur yang bisa berdiri sendiri sebagai referensi cepat — cocok untuk cheat sheet, belajar last-minute, atau dokumentasi.

---

## 📋 Prompt

```
Ekstrak dan visualisasikan semua data penting dari materi ini dalam bentuk tabel-tabel terstruktur. Buat tabel berikut (skip jika tidak relevan dengan materi):

📊 TABEL 1 — Perbandingan Konsep/Metode
Kolom: | Nama | Definisi | Kelebihan | Kekurangan | Kapan Digunakan |
(isi dengan semua konsep/metode yang ada di materi)

📊 TABEL 2 — Ringkasan Rumus & Formula (jika ada)
Kolom: | Nama Rumus | Formula/Notasi | Variabel | Keterangan | Contoh Penggunaan |

📊 TABEL 3 — Kronologi / Timeline (jika materi berisi sejarah/proses)
Kolom: | Tahun/Fase | Peristiwa/Langkah | Dampak/Hasil | Tokoh/Komponen Kunci |

📊 TABEL 4 — Matriks Perbandingan Cepat
Buat tabel dengan konsep di baris dan atribut di kolom.
Gunakan simbol: ✓ (ya/ada), ✗ (tidak/tidak ada), ~ (sebagian)
Contoh atribut: efisiensi, kemudahan implementasi, skalabilitas, dll.

📊 TABEL 5 — Panduan Pengambilan Keputusan
Kolom: | Situasi/Kondisi | Gunakan | Alasan | Contoh Kasus |
(bantu pembaca tahu kapan menggunakan konsep mana)

📊 TABEL 6 — Daftar Istilah Kunci
Kolom: | Istilah | Singkatan (jika ada) | Definisi Singkat | Contoh |

FORMAT:
- Gunakan tabel Markdown yang rapi
- Urutkan baris dari yang paling dasar/umum ke yang kompleks
- Jika ada data numerik, pastikan satuannya tercantum
- Tambahkan catatan kaki di bawah tabel jika ada hal penting yang tidak muat di kolom

Tujuan: tabel ini harus bisa berdiri sendiri sebagai referensi cepat tanpa perlu membaca materi asli.
```

---

## 💡 Tips Penggunaan

- **Minta tabel spesifik:** Tidak semua tabel relevan untuk setiap materi. Kamu bisa minta hanya tabel tertentu, misal `"Buat hanya Tabel 1 dan Tabel 4"`
- **Untuk algoritma/kode:** Tambahkan `"Di Tabel 1, sertakan kolom Time Complexity dan Space Complexity"`
- **Untuk mata kuliah jaringan:** Tambahkan `"Di Tabel 6, sertakan kolom Layer OSI terkait"`
- **Export ke spreadsheet:** Copy tabel Markdown, lalu paste ke [tabletomarkdown.com](https://tabletomarkdown.com/convert-spreadsheet-to-markdown/) untuk convert ke Excel/Google Sheets
- **Cetak sebagai cheat sheet:** Copy semua tabel ke Google Docs, atur font kecil, dan print 2-in-1

---

## 📌 Contoh Output yang Dihasilkan

```
📊 TABEL 1 — Perbandingan Algoritma Sorting

| Nama         | Definisi                          | Kelebihan              | Kekurangan          | Kapan Digunakan          |
|--------------|-----------------------------------|------------------------|---------------------|--------------------------|
| Bubble Sort  | Tukar elemen berdekatan berulang  | Sederhana, mudah dipahami | O(n²), lambat     | Data kecil, tujuan belajar |
| Quick Sort   | Partisi dengan pivot              | Rata-rata O(n log n)   | Worst case O(n²)    | Data besar, general use  |
| Merge Sort   | Bagi & gabung rekursif            | Stabil, O(n log n)     | Butuh memori ekstra | Data besar, butuh stabilitas |

📊 TABEL 4 — Matriks Perbandingan Cepat

| Algoritma    | Stabil | In-place | O(n log n) avg | Cocok data besar |
|--------------|--------|----------|----------------|------------------|
| Bubble Sort  | ✓      | ✓        | ✗              | ✗                |
| Quick Sort   | ✗      | ✓        | ✓              | ✓                |
| Merge Sort   | ✓      | ✗        | ✓              | ✓                |
```

---

## 🔗 Prompt Terkait

- Mau penjelasan lebih dalam tiap baris tabel? Gunakan [Prompt 02](./02-laporan-panduan.md)
- Mau diuji pemahamannya? Gunakan [Prompt 03](./03-simulasi-ujian.md)
- Mau dijadikan slide? Gunakan [Prompt 01](./01-slide-presentasi.md)
