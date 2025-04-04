# Pengenalan Vektor dalam Aljabar Linear
### 📌 Pendahuluan 
<p align="justify">Vektor adalah salah satu konsep fundamental dalam aljabar linear yang merepresentasikan besaran dengan magnitude (panjang) dan arah. Dalam berbagai aplikasi matematika, fisika, dan kecerdasan buatan (AI), vektor digunakan untuk merepresentasikan data, posisi, dan transformasi di berbagai ruang. <br> <br>
Dalam aljabar linear, kita mempelajari operasi-operasi dasar pada vektor yang menjadi dasar dari banyak konsep lebih lanjut seperti sistem persamaan linear, transformasi linear, dan ruang vektor.</p>

----
### 🔹 1. Representasi Vektor
<p align="justify">Secara matematis, vektor dapat direpresentasikan sebagai daftar angka (komponen) dalam suatu ruang vektor. Sebuah vektor di ruang dua dimensi (R²) dan tiga dimensi (R³) dapat ditulis sebagai:</p>

- Ruang 2D (R²):

$$
\mathbf{v} =
\begin{bmatrix}
v_1 \\
v_2
\end{bmatrix}
$$

- Ruang 3D (R³):

$$
\mathbf{v} =
\begin{bmatrix}
v_1 \\
v_2 \\
v_3
\end{bmatrix}
$$

Sebagai contoh, untuk vektor:

$$
\mathbf{v} = \begin{bmatrix} 
3 \\ 
4 
\end{bmatrix}
$$

adalah vektor di R² yang memiliki panjang 5 berdasarkan rumus panjang vektor.

---
### 🔹 2. Operasi Dasar pada Vektor
#### 2.1 Penjumlahan dan Pengurangan Vektor
Dua vektor dapat dijumlahkan atau dikurangkan dengan menjumlahkan atau mengurangkan masing-masing komponennya:

$$
\mathbf{a} + \mathbf{b} = \begin{bmatrix} 
a_1 \\ 
a_2 
\end{bmatrix} + \begin{bmatrix}
b_1 \\
b_2
\end{bmatrix} = \begin{bmatrix}
a_1 + b_1 \\
a_2 + b_2
\end{bmatrix}
$$

$$
Contoh: \begin{bmatrix}
2 \\
3
\end{bmatrix} + \begin{bmatrix}
1 \\
4
\end{bmatrix} = \begin{bmatrix}
3 \\
7
\end{bmatrix}
$$

#### 2.2 Perkalian Skalar dengan Vektor
Perkalian skalar dengan vektor mengubah panjang vektor tanpa mengubah arahnya (kecuali jika skalar negatif, yang membalik arah vektor):

$$
\mathbf{C} \mathbf{v} = \mathbf{C} \begin{bmatrix}
\mathbf{x} \\
\mathbf{y}
\end{bmatrix} = \begin{bmatrix}
\mathbf{C}\mathbf{x} \\
\mathbf{C}\mathbf{y} 
\end{bmatrix}
$$

$$
Contoh: \mathbf{2} \text{x} \begin{bmatrix}
\mathbf{3} \\
\mathbf{4}
\end{bmatrix} = \begin{bmatrix}
\mathbf{6} \\
\mathbf{8}
\end{bmatrix}
$$

---
### 🔹 3. Linear Combination & Span
#### 3.1 Kombinasi Linear
Kombinasi linear dari dua vektor $\mathbf{a}$ dan $\mathbf{b}$ dinyatakan sebagai:

$$
\mathbf{C_1} \mathbf{a} + \mathbf{C_2} \mathbf{b} 
$$

Dimana $\mathbf{C_1}, \mathbf{C_2}$ adalah skalar Jika kita mengambil semua kemungkinan kombinasi linear dari dua vektor, kita mendapatkan <strong><i>span</i></strong> dari vektor tersebut.
#### 3.2 Span
Span dari dua vektor dalam R² adalah himpunan semua vektor yang dapat dibentuk dari kombinasi linear kedua vektor tersebut. Jika dua vektor <strong><i>tidak sejajar</strong></i> atau bisa disebut <strong><i>tidak colinier</strong></i>, maka span-nya mencakup seluruh bidang R².

---
### 🔹 4. Basis dan Dimensi
Sebuah himpunan vektor dikatakan sebagai basis dari ruang vektor jika:
  1. Vektor-vektor tersebut independen secara linear (tidak bisa dinyatakan sebagai kombinasi linear dari yang lain).
  2. Vektor-vektor tersebut mencakup seluruh ruang (span-nya adalah seluruh ruang vektor).
Di R², basis standar adalah:

$$\mathbf{e_1} = \begin{bmatrix} 
1 \\
0 
\end{bmatrix}, \mathbf{e_2} = \begin{bmatrix}
0 \\
1
\end{bmatrix}
$$

Di R³, basis standar adalah:

$$\mathbf{e_1} = \begin{bmatrix} 
1 \\
0 \\
0
\end{bmatrix}, \mathbf{e_2} = \begin{bmatrix}
0 \\
1 \\
0
\end{bmatrix}, \mathbf{e_3} = \begin{bmatrix}
0 \\
0 \\
1
\end{bmatrix}
$$

Dimensi ruang vektor adalah jumlah vektor dalam basisnya. Misalnya, R² memiliki dimensi 2 karena basisnya terdiri dari 2 vektor.

---
### 🔹 5. Representasi Parametrik dari Garis
Garis dalam ruang vektor dapat dinyatakan dengan rumus parametrik:

$$
\mathbf{p} (\mathbf{t}) = \mathbf{p_0} + \mathbf{td}
$$

Di mana:

- $\mathbf{p_0}$ adalah titik awal garis,
- $\mathbf{d}$ adalah arah vektor,
- $\mathbf{t}$ adalah skalar.

Contoh dalam R²: Jika $\mathbf{p_0}$ didefinisikan sebagai berikut:

$$
\mathbf{p_0} = \begin{bmatrix} 1 \\ 
2 
\end{bmatrix}
$$

dan $\mathbf{d}$:

$$
\mathbf{d} = \begin{bmatrix} 3 \\ 
-1 
\end{bmatrix}, \text{maka garisnya adalah:}
$$

$$
\mathbf{p(t)} = \begin{bmatrix}
1 \\
2 \end{bmatrix} + \mathbf{t} \begin{bmatrix}
3 \\
-1 \end{bmatrix}
$$

---

### 🎯 Kesimpulan
- Vektor merepresentasikan besaran dengan magnitude dan arah.
- Operasi vektor mencakup penjumlahan, pengurangan, dan perkalian skalar.
- Kombinasi linear & span membantu memahami struktur ruang vektor.
- Basis & dimensi menunjukkan jumlah vektor independen minimum yang dapat merepresentasikan suatu ruang.
- Representasi parametrik garis menunjukkan bagaimana garis dinyatakan dalam ruang vektor.

<p align="justify">Materi ini merupakan fondasi penting dalam Machine Learning karena vektor sering digunakan dalam representasi data, model linear, dan transformasi ruang fitur.</p>
