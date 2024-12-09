---
title: Probabilitas Diskrit & Bayesian

---

# Probabilitas Diskrit & Bayesian

## Pengertian

#### Probabilitas Diskrit
Probabilitas diskrit adalah distribusi yang menunjukkan bahwa variabel acak memiliki nilai tertentu dengan probabilitas yang telah ditentukan. Variabel acak diskrit memiliki jumlah nilai yang dapat dihitung atau terbatas.

#### Probabilitas Bayesian
Probabilitas Bayesian adalah pendekatan dalam teori probabilitas yang menggabungkan informasi baru dengan pengetahuan sebelumnya untuk memperbarui kepercayaan terhadap suatu hipotesis. Ini didasarkan pada Teorema Bayes, yang menyatakan bahwa probabilitas suatu hipotesis $H$ setelah melihat data $X$ (dikenal sebagai probabilitas posterior) dapat dihitung dengan rumus: 

$P(H|X) = \frac{P(X|H) \cdot P(H)}{P(X)}$

$Keterangan :$

$P(H|X)$ adalah probabilitas hipotesis setelah data diperoleh (posterior).

$P(H)$ adalah probabilitas awal hipotesis (prior).

$P(X|H)$ adalah probabilitas data jika hipotesis benar.

$P(X)$ adalah total probabilitas data 24 

# Teorema Bayes
Teorema Bayes adalah rumus matematika yang digunakan untuk menghitung probabilitas brsyarat, yaitu seberapa besar kemungkinan suatu peristiwa terjadi berdasarkan peristiwa lain.

#### Posterior
Posterior probability adalah distribusi probabilitas yang diperoleh setelah menggabungkan informasi dari prior dan likelihood. Ini mencerminkan keyakinan kita tentang parameter setelah mempertimbangkan data yang baru diperoleh.

#### Likelihood
Likelihood adalah distribusi probabilitas dari data yang diamati diberikan parameter tertentu. Ini menggambarkan seberapa baik model dengan parameter tersebut dapat menjelaskan data yang telah dikumpulkan. Dalam konteks statistik, likelihood dihitung berdasarkan fungsi distribusi dari data yang diperoleh dan parameter yang diasumsikan. Sebagai contoh, jika kita memiliki data tentang hasil tes kesehatan, likelihood akan menunjukkan seberapa besar kemungkinan hasil tersebut terjadi jika parameter kesehatan tertentu benar.

#### Prior
Prior probability adalah distribusi probabilitas yang mencerminkan keyakinan atau pengetahuan awal tentang suatu parameter sebelum data baru diperoleh. Ini menggambarkan asumsi atau informasi yang sudah ada mengenai parameter yang sedang dianalisis. Misalnya, jika kita memperkirakan kemungkinan suatu penyakit, prior dapat didasarkan pada data epidemiologi sebelumnya atau studi populasi.

## CONTOH
Bagaimana kemungkinan/probabilitas usia paruh baya tekanan darah sangat tinggi  kemungkinan penyakit Hipertensi (H) atau Tidak (T)

| No   | Usia | Tekanan Darah | Penyakit (H/T) |
| ---- | ---- | ------------- | --- |
| 1    | Muda | Normal       | T    |
| 2    | Muda | Tinggi       | T    |
| 3    | Paruh Baya | Normal       | T    |
| 4    | Paruh Baya | Tinggi      | H    |
| 5    | Tua | Normal       | H    |
| 6    | Tua | Sangat Tinggi      | H    |
| 7    | Muda | Normal       | T    |
| 8    | Tua | Normal       | H    |


1. Hitunglah probabilitas Hipertensi terhadapa usia paruh baya tekanan darah sangat tinggi 

2. Hitunglah probabilitas Tidak  Hipertensi terhadap usia paruh baya tekanan darah sangat tinggi.

#### RUMUS TEORMA BAYES

$Keterangan :$ 

$P$ = probabilitas 
$H$ = penyakit yang terkena hipertensi
$T$ = penyakit yang tidak hipertensi
$X1$ = usia paruh baya
$X2$ = tekanan darah normal(terdapat pada data di atas)

$Diketahui :$

1. jumlah keselurusahn probabilitas = 8
2. jumlah penyakit hipertensi = 4
3. jumlah penyakit tidak hipertensi = 4
4. usia paruh baya normal yang terkena penyakit hipertensi = 1
5. usia paruh baya yang terkena penyakit hipertensi = 4
6. tekanan darah pada penyakit hipertensi sangat tinggi =4

$Jawaban :$

(penyakit hipertensi) $P(H)$

$P(H|X) = P (X1|H) . P (X2|H) . P (H)$

$= P (1/4) . 1 (1/4) .  (4/8)$

$= P (0,25) . 1 (0,25) .  (0,5)$

$= 0,03125$

(penyakit tidak hipertensi) $P(T)$

$P(T|X) = P (X1|T) . P (X2|T) . P (T)$

$= P (1/4) . (0) .  (4/8)$

$= P (0,25) . (0) .  (0,5)$

$= 0$