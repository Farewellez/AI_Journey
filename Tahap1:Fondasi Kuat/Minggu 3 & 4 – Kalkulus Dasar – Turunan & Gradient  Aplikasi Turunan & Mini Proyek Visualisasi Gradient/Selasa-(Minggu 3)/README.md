# **🧠Hari Selasa – Aturan Dasar Turunan & Aplikasinya di AI**

## 🎯 **Tujuan Pembelajaran:**

- Memahami aturan-aturan dasar turunan (power rule, penjumlahan, product, quotient).
- Menguasai teknik menurunkan fungsi kompleks untuk bekal memahami **fungsi kerugian (loss function)** dan **aktivasi** dalam AI.
- Menyambungkan konsep turunan ke proses optimasi model AI (gradient descent).

---

### 📚 **Materi yang Dipelajari:**

### 🔧 Aturan Turunan Dasar:

- Konstanta
- Pangkat / Power Rule
- Penjumlahan & Pengurangan
- Perkalian (Product Rule)
- Pembagian (Quotient Rule)

### 🧠 Penerapan di Dunia AI:

- Digunakan saat menghitung **gradient dari fungsi kerugian** saat training model (ML & DL).
- Product & quotient rule sering muncul saat model melibatkan **fungsi komposit**.
- **Backpropagation di neural network** bergantung penuh pada ini!

---

### 🔗 **Referensi Terstruktur:**

- 📘 Khan Academy – [Derivative Rules](https://www.khanacademy.org/math/ap-calculus-ab/ab-diff-analytical-applications-new)
- 📺 YouTube – [Calculus 1 - Basic Derivatives Rules](https://www.youtube.com/watch?v=_yq7zTQrtGg)
- 🧠 Towards Data Science – Why Derivatives Matter in Deep Learning
- 🧮 **Simulasi & Visualisasi Praktik:**
    - Symbolab – Derivative Calculator
    - Desmos – Graph Calculator

---

### 🛠️ **Praktik Ringan:**

> 🎯 Tujuan praktik: mengasah intuisi dan ketelitian menghitung turunan fungsi kompleks
> 

Coba hitung turunan fungsi berikut secara manual:



$f(x) = 4x^3 - 2x^2 + 7$

$f(x) = (x^2 + 1)(x - 3)$

$f(x) = \frac{x^2 + 5}{2x - 1}$

$f(x) = \sin(x) \cdot e^x$

$f(x) = \ln(x^2 + 1)$




→ Setelah dihitung manual, verifikasi hasilmu di Symbolab

→ Buat sketsa grafik di Desmos dan amati bentuk kurva & kemiringannya

---

### 🎁 **Oleh-Oleh Latihan:**

1. Tulis 3 fungsi bebas, lalu turunkan manual, beri keterangan langkahnya.
2. Buat catatan singkat:
    - Apa beda **kapan pakai product rule vs quotient rule?**
    - Mengapa **power rule** jadi fondasi semua?
3. Jelaskan dengan contoh kecil bagaimana aturan turunan ini dipakai dalam **backpropagation** (boleh analogi).
4. (Opsional bonus) – Gambar kurva loss function sederhana dan tandai **titik minimum** menggunakan konsep turunan.
