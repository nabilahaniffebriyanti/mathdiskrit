---
title: GRAPH

---

# GRAPH
graph adalah kumpulan note yang saling berhubungan. 

Contoh graph seperti jaringan komputer yang saling terhubung, orang orang dalam sosial media yang saling berhubungan.

contoh graph yang berbobot yaitu jarak antar kota, seperti gresik ke surabaya 10 km,surabaya ke madura 20km,gresik ke madura 35km.bobotmenunjukkan jarak jalan, yang dimana akan menghasilkan analisis jarak lintasan terpendek.

#### contoh

![image](https://hackmd.io/_uploads/Hy-mEAem1e.png)

anasila node terpenting dalam graph tersebut : 

## Social network
sebuah jaringan yang berhubungan atau interaksi antara entitas, seperti : individu atau kelompok.

Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network.

terbagi menjadi 4 yaitu : 
- degree centrality
- clossness centrality
- betweness centrality
- eigenvector centrality


### Degree Centrality
adalah jumlah edge yang terkoneksi pada satu note yang mewakili interaksi. atau mengukur jumlah hubungan yang di miliki oleh suatu note.

rumusnya : 
$C'D (vi) = di/(n-1)$

normalisasinya = untuk node 1, degree centrality adalah 3/(9-1)=3/8

### Closeness centrality
nilai kedekatan antara satu node dengan note lainnya dalam suatu jaringan dengan menghitung rata rata dari jarak relasi node node tersebut.

$C_C(v) = \frac{1}{\sum_{u \neq v} d(v, u)}$

$cc3 = 9-1/1+1+1+2+2+3+3+4 = 8/17 =0.47$

9 dari jumlah semua note

### Betweeness centrality
Menghitung jumlah lintasan terpendek yang melewati suatu node.
Node dengan  betweenness  tinggi  adalah  penting dalam komunikasi dan penyebaran informasi.

contoh :
3
1 -> 4 -> 5 -> 7 -> 9
2 ------> 6 -> 8
misal, berapa banyak lintasan terpendek  untuk menuju note 5 yaitu ada 2,untuk mengetahuinya yaitu dengan cara note 1 melewati note 1,3,5 dan note 1,3,4,5

rumusnya :
$C_B(v)=\sum_{s\neq v\neq t}\frac{\sigma_{st}(v)}{\sigma_{st}}$

(st) Jumlah lintasan terpendek antara  s dan t
st(vi) Jumlah lintasan terpendek antara s dan t yang melewati vi

![image](https://hackmd.io/_uploads/B1PQURgXJl.png)

Normalisasi nya : 
$C'B(i)=C'Bi/(n-1)(n-2)/2$
$C'B(i)=15/(9-1)(9-2)/2$
$C'B(i)=15/(8)(7)/2$
$C'B(i)=15/28$
$C'B(i)=0,5357$