---
title: UAS

---

### 1. Buatlah tabel kebenaran untuk pernyataan berikut : 

$(P -> Q) -> (R -> S)$

| NO  | P   | Q   | R   | S   | (P->Q)->(R->S) |
| --- | --- | --- | --- | --- | ----------- | 
| 1   | T   | T   | T   | F   |  F   |
| 2   | T   | F   | F   | T   |  T   |
| 3   | T   | T   | T   | F   |  T   |
| 4   | F   | T   | T   | T   |  T   |
| 5   | T   | T   | F   | T   |  F   |
| 6   | T   | T   | T   | T   |  T   |
| 7   | F   | T   | F   | T   |  F   |
| 8   | T   | F   | T   | T   |  F   |

### 2. buatlah graph
![uas graph](https://hackmd.io/_uploads/HJsd0GV4ye.jpg)


| node | a    | b    | c   | d   | e   | f   | g   |
| ---- | ---- | ---- | --- | --- | --- | --- | --- |
| a    | 0 | 1 |  3   |     |     |     |     |
| b    | 1 | 1 |     |     |     |     |     |
| c    | 1 | 1 |     |     |     |     |     |
| d    | 1 | 0 |     |     |     |     |     |
| e    | 0 | 0 |     |     |     |     |     |
| f    | 0 | 3 |     |     |     |     |     |
| g    | 0 | 4 |     |     |     |     |     |

### hitung closnesscentrality 
$C_C(v) = \frac{1}{\sum_{u \neq v} d(v, u)}$

$cc3 = 7-1/1+1+1+2+2+3+3+4 = 6/17 =0.235$
### hitung Betweeness centrality
$C'B(i)=C'Bi/(n-1)(n-2)/2$
$C'B(i)=10/(7-1)(7-2)/2$
$C'B(i)=10/(6)(5)/2$
$C'B(i)=10/15$
$C'B(i)=0,6666$
