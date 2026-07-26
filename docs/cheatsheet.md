# 📘 Cheat Sheet: Pattern Pemula + UMPIRE

## 🧩 UMPIRE — Ringkas

| Tahap | Yang dilakukan |
|---|---|
| **U**nderstand | Pahami input, output, edge case |
| **M**atch | Cari pattern yang cocok |
| **P**lan | Tulis pseudocode |
| **I**mplement | Tulis kode |
| **R**eview | Cek dengan contoh & edge case |
| **E**valuate | Hitung Big-O, cari perbaikan |

---

## 🔑 Pattern Pemula yang Paling Sering Muncul

**1. Two Pointers**
Kapan: array/list sudah terurut, cari pasangan/triplet.
Ciri: dua pointer bergerak dari kiri-kanan atau searah.

**2. Sliding Window**
Kapan: cari substring/subarray terpanjang/terpendek yang memenuhi syarat.
Ciri: "jendela" yang membesar/mengecil sambil geser ke kanan.

**3. Hash Map**
Kapan: perlu cek "sudah pernah lihat?" atau hitung frekuensi dengan cepat.
Ciri: mengubah O(n²) menjadi O(n).

**4. Fast & Slow Pointers**
Kapan: deteksi cycle di linked list, cari elemen tengah.
Ciri: satu pointer bergerak 2x lebih cepat dari yang lain.

**5. Stack**
Kapan: validasi kurung, cari "next greater element".
Ciri: LIFO — cocok untuk parsing/matching.

**6. Binary Search**
Kapan: array terurut (atau bisa dianggap terurut).
Ciri: selalu membagi masalah jadi setengah tiap langkah.

**7. BFS / DFS (Tree & Graph)**
Kapan: traversal pohon/graf, cari jalur terpendek (BFS) atau eksplorasi dalam (DFS).
Ciri: rekursi (DFS) atau queue (BFS).

**8. Backtracking**
Kapan: cari semua kombinasi/permutasi/subset yang mungkin.
Ciri: coba → kalau salah, mundur (undo) → coba lagi.

**9. Dynamic Programming (Dasar)**
Kapan: ada sub-masalah yang berulang dan bisa dioptimalkan.
Ciri: simpan hasil sub-masalah supaya tidak dihitung ulang.

**10. Merge Intervals**
Kapan: ada interval/rentang waktu yang bisa tumpang tindih.
Ciri: sort dulu berdasarkan waktu mulai, baru gabungkan.

**11. Top "K" Elements**
Kapan: cari K elemen terbesar/terkecil/tersering.
Ciri: biasanya pakai heap (priority queue).

---

## 💡 Tips Singkat
- Bingung pattern apa? Cek dua hal: **bentuk input** (array terurut? linked
  list? graf?) dan **apa yang diminta** (terpanjang? terpendek? semua
  kombinasi? top K?).
- Hafalkan **sinyal** kapan pattern dipakai — bukan kode mentahnya.
