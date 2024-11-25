---
title: DERETAN DAN REKURSI

---

# DERETAN DAN REKURSI

### Deretan (Squence)
Suatu urutan atau susunan elemen yang di susun secara teratur berdasarkan suatu aturan tertentu. 

elemen deretan biasa berupa huruf,angka,simbol atau objek lainnya.
sebuah deretan adalah sebagai fungsi dari sebuah himpunan bilangan bulat (N & p)

dalam definisi deretan adalah fungsi dari subject suatu himpunan bilangan bulat (N atau P) ke sebuah himpunan S.

N = (1, 2, 3, 4, 5....)
S = (2, 4, 6, 8, 10....),(1/3, 1/5, 1/7, 1/9...)

notasi deretan : ${an}$
deretan umumnya dinyatakan dalam suatu formula, misalnya :
$an$ = n
$an$ = 1/n
$an$ = 7-3n

### Contoh - contoh deretan

## 1. Deretan Aritmetika
Deret dengan pola kenaikan atau penurunan tetap.
contoh = 2, 5, 8, 11, 14, 
rumus suku ke-$n$ : $U_n = a + (n−1) ⋅ b$

$a$ : suku pertama
$b$ : beda (selisih antar suku)
$n$ : nomor suku

contoh soal =
1. Diketahui deret aritmatika dengan $a$ = 5, $b$ = 3, dan $n$ = 4. Tentukan $Un$?

jawaban : 
$𝑈_𝑛 = a + (𝑛−1) ⋅ b$ 
$𝑈_𝑛 = 5 + (4−1) ⋅ 3$
$𝑈_𝑛 = 5 + 9$ 
$𝑈_𝑛 = 14$
 
 ### 2. Deret Geometri
 Deret dengan pola kelipatan tetap.
 contoh = 3, 6, 12, 24, 48.....
 rumus suku ke-n : $Un = a⋅r (n−1)$
 
 $a$ : suku pertama
 $r$ : rasio (perbandingan antar suku)
 $n$ : nomor suku
 
 contoh soal =
 1. Diketahui deret geometri dengan $a$ =3,$r$ =2, dan $n$= 4. Tentukan $Un$?

jawaban = 
$𝑈_𝑛 = a.r (n-1)$
$𝑈_𝑛 = 3.2 (4-1)$
$𝑈_𝑛 = 3.2 (3)$
$𝑈_𝑛 = 3.8$
$𝑈_𝑛 = 24$

### 3. Deret Bilangan Kuadrat
Deret dengan pola nilai berupa kuadrat bilangan bulat.

- Contoh: 1,4,9,16,25,…
- Rumus suku ke-$n$: $𝑈_𝑛=𝑛^2$

contoh soal = 
1. diketahui deret bilangan kuadrat 1, 4, 9, 16, 25...
tentukan suku ke-8 dalam deret tersebut?

jawaban =
$𝑈_𝑛 =𝑛^2$
$𝑈_8 =64$

### 4. Deret bilangan kubik
Deret dengan pola nilai berupa kubik bilangan bulat.

Contoh: 1, 8, 27, 64, 125,…
Rumus suku ke-n: $𝑈_𝑛=𝑛^3$

contoh soal =
1. diketahui deret bilangan kubik 1, 8, 27, 64, 125...
tentukan suku ke-6 dalam deret tersebut?

jawaban =
$𝑈_𝑛 =𝑛^3$
$𝑈_6 =216$

### 5. Deret Fibonacci

Deret dengan pola di mana setiap suku merupakan jumlah dua suku sebelumnya.
Contoh: 0, 1, 1, 2, 3, 5, 8,…
Rumus suku ke-$n$ (rekursi) :
$𝐹_𝑛=𝐹_(𝑛−1)+𝐹_(𝑛−2),𝐹_0=0,𝐹_1=1$

$F_{n}$ : suku ke-$n$ 
$F_{n-1}$ : suku sebelumnya
$F_{n-2}$ : dua suku sebelumnya

contoh soal =
1. Tentukan suku ke-5 pada deret fibonnaci
gunakan rumus rekursi : 

jawaban =
$F_n = F_{n-1} + F_{n-2}$
$F_5 = F_4 + F_3 = 5$
$F_4 = F_3 + F_2 = 3$
$F_3 = F_2 + F_1 = 2$
$F_2 = 1$
$F_1 = 1$
$F_1 = 1, \, F_2 = 1, \, F_3 = F_2 + F_1 = 2, \, F_4 = F_3 + F_2 = 3, \, F_5 = F_4 + F_3 = 5, \, = 12.$

### Penjumlahan Deretan
  Jumlah deretan 
	am, am+1, am+2, …, an
  adalah
	 am + am+1 + am+2 + … + an
  atau dalam notasi sumasi:
	$∑^𝑛(𝑘=𝑚)$ $𝑎_𝑘$
   
    k adalah indeks summasi, 
    m adalah batas bawah indeks,
    n adalah batas atas indeks

Contoh soal =
Berapa nilai $∑^5_(𝑘=1_)$ $𝑘^2$ ?
Jawaban: 
	$∑^5_(𝑘=1_)𝑘^2$ = 12 + 22 + 32 + 42 + 52 = 1 + 4 + 9 + 16 + 25 = 55

beberapa rumus sumasi sebagai berikut : 
![image](https://hackmd.io/_uploads/SyHh03xXJx.png)

Hitung nilai    $∑100(𝑘=50)𝑘^2$
Jawaban:
$∑100(𝑘=1)𝑘^2 =  ∑49(𝑘=1)𝑘^2 + ∑100(𝑘=50)𝑘^2$

$∑100(𝑘=50)𝑘^2  = ∑100(𝑘=1)𝑘^2 − ∑49(𝑘=1)𝑘^2$

### Sumasi Ganda

Di dalam algoritma, kita perlu menghitung berapa kali suatu operasi tertentu dilakukan di dalam sebuah kalang bersarang (nested loop). Penjumlahan semua operasi di dalam kalang bersarang dinyatakan dalam bentuk sumasi ganda.

Contoh: $∑4(𝑖=1) ∑3(𝑗=1)𝑖𝑗$

Untuk menghitung sumasi ganda, mula-mula ekspansi sumasi terdalam, lalu  dilanjukan dengan sumasi terluar:

$∑4(𝑖=1) ∑3(𝑗=1)𝑖𝑗$
$∑4(𝑖=1)(𝑖+2𝑖+3𝑖)$
$∑4(𝑖=1)6𝑖 = 6 + 12 + 18 + 24 = 60$

### Rekursif

## Pengertian Rekursif
Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 

Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).

## Fungsi Rekursif
1. Basis 
Bagian yang berisi nilai fungsi yang terdefinisi secara eksplisit. 
Bagian ini juga sekaligus menghentikan rekursif (dan memberikan sebuah nilai yang terdefinisi pada fungsi rekursif).
 
2. Rekurens
Bagian ini mendefinisikan fungsi dalam terminologi dirinya sendiri. 
Berisi kaidah untuk menemukan nilai fungsi pada suatu input dari nilai-nilai lainnya pada input yang lebih kecil. 

contoh : Misalkan f didefinsikan secara rekusif sbb
     
Tentukan nilai f(4)!
	
$Solusi$
            $=  2(2f(2) + 4) + 4$
			$=  2(2(2f(1) + 4) + 4) + 4$
			$=  2(2(2(2f(0) + 4) + 4) + 4) + 4$
			$=  2(2(2(2.3 + 4) + 4) + 4) + 4$
			$=  2(2(2(10) + 4) + 4) + 4$
			$=  2(2(24) + 4) + 4$
			$=  2(52) + 4$
			$= 108$	

Cara lain menghitungnya :
		$f(0) = 3$
		$f(1) = 2f(0) + 4 = 2 . 3 + 4 = 10$
		$f(2) = 2f(1) + 4 = 2 . 10 + 4 = 24$
		$f(3) = 2f(2) + 4 = 2 . 24 + 4 = 52$
		$f(4) = 2f(3) + 4 = 2 . 52 + 4 = 108$
		
J$adi, f(4) = 108.$

contoh lain =

$f(n) = 
\begin{cases} 
3 & \text{if } n = 0, \\
2f(n-2) & \text{if } n > 0.
\end{cases}$

$f(4)=2f(2)$
$f(4)=2(2f(0))$
$f(4)=2(2.3)$
$f(4)=12$

$f(6)=2f(4)$
$f(6)=2(12)$
$f(6)=24$

Latihan
1. Definisikan an secara rekursif , yang dalam hal ini a adalah bilangan riil tidak-nol dan n adalah bilangan bulat tidak-negatif.

2. Nyatakan a x b secara rekursif, yang dalam hal ini a dan b adalah bilangan bulat positif.

solusi =
1. $a^n = a \cdot a \cdot a \cdots a \ (\text{n}) = a \cdot a^{n-1}.$

$a^n =$
 \begin{cases} 
 1, & \text n = 0, \\
a \cdot a^{n-1}, & \text n > 0.
 \end{cases}
 
2. $a \cdot b = b + b + b + \cdots + b$ (a kali)
$a \cdot b = b + b + b + \cdots + b$ (a-1 kali)
$a \cdot b = b + (a-1) b$

$a \cdot b =$
     \begin{cases} 
     b, & \text a = 1, \\
     b + (a-1) \cdot b, & \text a > 1.
     \end{cases}