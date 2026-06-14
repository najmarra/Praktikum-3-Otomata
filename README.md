# Pushdown Automaton (PDA) Simulator

## Deskripsi

Project ini adalah sebuah simulator Pushdown Automaton (PDA) berbasis Python yang digunakan untuk menguji apakah suatu string termasuk dalam bahasa formal tertentu atau tidak. PDA ini bekerja dengan konsep stack (LIFO) dan mendukung nondeterministic PDA (NPDA), sehingga dapat menangani beberapa kemungkinan transisi dalam satu state. Program ini menyediakan fitur interaktif berbasis terminal (CLI) untuk memudahkan pengguna dalam melakukan simulasi automata.

## Tujuan

Program ini dibuat untuk:

1. Memahami konsep Pushdown Automata (PDA) dalam Teori Bahasa & Automata
2. Mensimulasikan proses stack secara visual dan langkah demi langkah
3. Menguji string terhadap bahasa formal (Accepted / Rejected)
4. Memberikan fleksibilitas untuk membuat PDA sendiri (custom PDA)

## Fitur Utama

### Contoh PDA

Program menyediakan beberapa PDA siap pakai, seperti:

1. aⁿbⁿ (jumlah a sama dengan b)
2. Palindrom wcwᴿ
3. Kurung seimbang (Balanced Parentheses)
4. a²ⁿbⁿ

### PDA Kustom

Pengguna dapat membuat PDA sendiri dengan menentukan:

1. State
2. State awal
3. Final/accept state
4. Simbol stack dasar
5. Transisi (state, input, stack top, next state, push)

### Testing String

Tersedia dua mode pengujian:

1. Single input test
2. Batch test (banyak string sekaligus)

Output akan menunjukkan:

1. ACCEPTED / REJECTED
2. Status akhir stack
3. Jejak eksekusi (step-by-step)

## Cara Kerja

PDA bekerja dengan prinsip:

1. Membaca input string satu per satu
2. Menggunakan stack untuk menyimpan simbol
3. Melakukan transisi berdasarkan:
- State saat ini
- Input karakter
- Top stack
4. Mengubah state + stack sesuai aturan transisi
5. String diterima jika:
- Input habis
- Berada di accept state (dan kondisi stack sesuai aturan PDA)




















