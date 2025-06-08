# 🎯 Final Project Komnum IUP_02 – Soal Nomor 43
|    NRP     |      Name      |
| :--------: | :------------: |
| 5025241004 | Razan Widya Reswara |
| 5025241009 | Embun Nabila Rasendriya Az Zahra |
| 5025241013 | Muhammad Ari Fathan Mahardika |
| 5025241007 |  Muhammad Ilyas Rusdi |
| 5025241010 | Muhammad Dzaky Radithya Ryrdi  |

## 📌 Tujuan:
Menghitung luas di bawah kurva fungsi:
$f(x) = -4 + 7x^2$
Menggunakan metode **Simpson 1/3 Rule** dalam interval $[0, 12]$.

---

## 🔢 1. Menentukan nilai h

Gunakan rumus:
$h = \frac{b-a}{n}$

- \( $a = 0$ \)  → batas bawah  
- \( $b = 12$ \) → batas atas  
- \( $n = 2$ \)  → jumlah segmen (karena Simpson 1/3 membutuhkan 2 segmen = 3 titik)

Sehingga:

$h = \frac{12 - 0}{2} = \frac{12}{2} = 6$


---

## 📍 2. Titik Evaluasi

Dengan $h = 6$, kita akan mengevaluasi fungsi pada titik:
-  $f(0)$ 
-  $f(6)$ 
-  $f(12)$ 

---

## 📐 3. Hitung Nilai $f(x)$

### ✅ $f(0)$

$f (0) = -4 + 7(0)**2 = -4 + 0 = -4$


### ✅ $f(6)$

$f (6) = -4 + (7*(6**2)) = -4 +( 7 * 36 ) = -4 + 252 = 248$


### ✅ $f(12)$

$f (12) = -4 + (7*(12**2)) = -4 +( 7 * 144 ) = -4 + 1008 = 1004$


---

## 📊 4. Substitusi ke Rumus Simpson 1/3

Rumus umum Simpson 1/3:

$$
L \approx \frac{b-a}{6} \left[ f(x_0) + 4f(x_1) + f(x_2) \right]
$$

Dengan:
- $a = 0$, $b = 12$
- $f(0) = -4$
- $f(6) = 248$
- $f(12) = 1004$

Substitusi:

$$
L = \frac{12 - 0}{6} \left[ -4 + 4(248) + 1004 \right]
= 2 \left[ -4 + 992 + 1004 \right]
= 2 \times 1992
= \boxed{3984}
$$

---

## 📉 5. Menghitung True Error (ET)

Untuk menghitung **ET (True Error)**, kita gunakan nilai eksak dari integral:

$$
\int_0^{12} (-4 + 7x^2) \, dx = \left[ -4x + \frac{7}{3}x^3 \right]_0^{12}
$$

Hitung:

$$
= -4(12) + \frac{7}{3}(12)^3
= -48 + \frac{7}{3}(1728)
= -48 + 4032
= \boxed{3984}
$$

Lalu:

$$
ET = \left| \frac{3984 - 3984}{3984} \right| \times 100\% = \boxed{0\%}
$$

---

## ✅ 6. Jawaban Akhir

- **Luas area (Simpson 1/3)**: 3984 
- **True Error (ET):** 0%



---
