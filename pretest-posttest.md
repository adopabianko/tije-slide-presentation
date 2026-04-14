# Pre-Test & Post-Test

## Standardizing Go Services with Clean Architecture

Jawab pertanyaan berikut dengan memilih **a** atau **b**.
---
### Soal 1
Dalam Clean Architecture, bagaimana arah dependency antar layer? (Jawaban b)
- a) Layer dalam boleh depend ke layer luar
- b) Layer luar yang depend ke layer dalam

---
### Soal 2
Di mana business logic seharusnya ditempatkan?  (Jawaban b)
- a) Di Handler / Delivery layer
- b) Di UseCase layer

---
### Soal 3
Apa tanggung jawab utama Repository layer? (Jawaban b)
- a) Menerima HTTP request dan mengirim response
- b) Menangani semua interaksi dengan data storage

---
### Soal 4
Apa tujuan penggunaan DTO (Data Transfer Object)? (Jawaban a)
- a) Memisahkan shape data API dari entity internal agar internal structure tidak bocor ke client
- b) Menyimpan business logic agar bisa digunakan ulang di berbagai handler

---
### Soal 5
Mengapa Clean Architecture membuat unit testing lebih mudah?  (Jawaban b)
- a) Karena semua kode ada dalam satu file sehingga mudah di-test sekaligus
- b) Karena setiap layer berkomunikasi lewat interface yang bisa di-mock

---
## Kunci Jawaban
| Soal | Jawaban |
|------|---------|
| 1 | b |
| 2 | b |
| 3 | b |
| 4 | a |
| 5 | b |