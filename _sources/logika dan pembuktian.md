---
title: logika dan pembuktian

---

# logika Matematika

## Negasi
adalah operasi yang menghasilkan kebalikan dari nilai kebenaran suatu pernyataan.

Berikut adalah tabel kebenaran Negasi:

| P        |   $\neg P$       |
| -------- | -------- | 
| T        | F        |
| F        | T        |

contoh : 

Jika pernyataan "Besi memuai jika dipanaskan" bernilai benar, maka negasinya adalah "Besi tidak memuai jika dipanaskan" yang bernilai salah.

## konjungsi
Dalam logika matematika, konjungsi adalah operasi logika yang menghubungkan dua pernyataan atau proposisi dengan kata penghubung “dan” $(AND)$. Konjungsi dari dua pernyataan $( p )$ dan $( q )$ dinyatakan sebagai $( p \land q )$ (dibaca: “p dan q”). Konjungsi $( p \land q )$ bernilai benar hanya jika kedua pernyataan $( p )$ dan $( q )$ bernilai benar. Jika salah satu atau kedua pernyataan bernilai salah, maka konjungsi tersebut bernilai salah.

Berikut adalah Tabel Kebenaran :

| P        | q        | p^q      |
| -------- | -------- | -------- |
| T        | T        | T        |
| T        | F        | F        |
| F        | T        | F        |
| F        | F        | F        | 
 
 contoh : 
 
 p: 3 adalah bilangan prima (pernyataan bernilai benar)
q: 3 adalah bilangan ganjil (pernyataan bernilai benar)
p ∧ q: 3 adalah bilangan prima dan ganjil (pernyataan bernilai benar)

## Disjungsi
 Disjungsi adalah operasi logika yang menghasilkan true jika setidaknya satu dari pernyataan input bernilai true. Operasi ini sering dilambangkan dengan simbol ∨ (vel).
 
 Berikut tabel kebenaran disjungsi:
 
| P        | q        | P$\vee$q |
| -------- | -------- | -------- |
| T        | T        | T        |
| T        | F        | T        |
| F        | T        | T        | 
| F        | F        | F        |
## implikasi
implikasi adalah operasi logika yang digunakan untuk mengekspresikan pernyataan bersyarat. Implikasi dilambangkan dengan simbol "→" dan dibaca sebagai "implied" atau "if-then".

Berikut adalah Tabel kebenaran implikasi:

| P        | q        | p→q      |
| -------- | -------- | -------- |
| T        | T        | T        |
| T        | F        | F        | 
| F        | T        | T        |
| F        | F        | T        |

contoh : 

p: ani belajar dengan aplikasi ruangguru. (pernyataan bernilai benar)
q: ani dapat belajar di mana saja. (pernyataan bernilai benar)
p ⇒ q: Jika ani belajar dengan aplikasi ruangguru, maka Ani dapat belajar dari mana saja (pernyataan bernilai benar)
## Biimplikasi
operator logika yang menghubungkan dua pernyataan, misalnya P dan Q, dan dilambangkan dengan simbol ⇔. Dapat dibaca sebagai "P jika dan hanya jika Q" atau "P ekuivalen dengan Q".

Berikut adalah Tabel kebenaran Bimplikasi:


| P        | q        | p ⇔ q   |
| -------- | -------- | -------- |
| T        | T        | T        |
| T        | F        | F        |
| F        | T        | F        |
| F        | F        | T        |

contoh : 

p: 30 x 2 = 60 (pernyataan bernilai benar)
q: 60 adalah bilangan ganjil (pernyataan bernilai salah)
p ⇔ q: 30 x 2 = 60 jika dan hanya jika 60 adalah bilangan ganjil (pernyataan bernilai salah)

Buatlah tabel kebenaran untuk~pernyataan berikut : $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{T}&\text{T}&\text{T}&\text{F}&\text{T}&\text{T}\\\text{T}&\text{T}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{T}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{T}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{T}&\text{}\end{array}$$