# **Hari Rabu – Turunan Parsial & Gradien**

### 🎯 **Tujuan Pembelajaran:**

- Memahami konsep **turunan parsial** untuk fungsi banyak variabel (multivariable function).
- Mengenal **gradien** sebagai arah perubahan tercepat.
- Menyambungkannya ke konsep **Gradient Descent** dalam proses *training* model Machine Learning & Deep Learning.

---

### 📚 **Materi yang Dipelajari:**

### 📌 Konsep Utama:

- Apa itu **turunan parsial**?
    - Turunan dari fungsi dengan lebih dari satu variabel.
    - Misal: $f(x,y)= x^2 + y^2$, maka ∂f/∂x dan ∂f/∂y.
- Apa itu **gradien (gradient)**?
    - Vektor dari semua turunan parsial:
        
        $∇f(x,y)= \left[ \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y} \right]$
        
    - Menunjukkan arah *kenaikan tercepat* dari fungsi.

### 🧠 Kenapa penting di AI?

- Digunakan dalam **gradient descent** untuk meminimalkan *loss function* saat training model.
- Di deep learning, **backpropagation** menggunakan gradien untuk update bobot.
- Contoh kasus:
    - Model regresi: loss tergantung banyak parameter (w₁, w₂, ..., b)
    - Optimasi: cari turunan parsial dari setiap parameter → gabungkan jadi gradien

---

### 🔗 **Referensi Terstruktur:**

- 📺 [3Blue1Brown – Partial Derivatives & Gradient](https://youtu.be/I9n3K5E4FZg)
- 📘 Khan Academy – [Multivariable Derivatives](https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives)
- 📘 Towards Data Science – Why Gradient is Everything in Deep Learning
- 🧮 **Simulasi & Visualisasi:**
    - GeoGebra 3D Calc – Gradient Visual
    - Symbolab – Partial Derivative Calculator

---

### 🛠️ **Praktik Ringan:**

> 🎯 Tujuan praktik: membentuk intuisi spasial dari gradien dan arah pergerakan optimasi
> 
1. Hitung turunan parsial dari:
    - $f(x,y)= x^2 + y^2$
    - $f(x,y)=xy + y^2$
    - $f(x,y)= e^{x+y}$
2. Visualisasi gradien dengan GeoGebra 3D – gambar fungsi kuadrat dan arah vektor gradien.
3. Simulasikan 1 langkah **gradient descent** dari titik awal (x,y)=(1,1)(x, y) = (1, 1)(x,y)=(1,1) menuju minimum (0,0)(0, 0)(0,0).

---

### 🎁 **Oleh-Oleh Latihan:**

1. Hitung manual:
    - ∂f/∂x dan ∂f/∂y untuk 3 fungsi dari praktik tadi.
2. Tulis jurnal mini:
    - Apa makna gradien bagimu dalam proses pelatihan AI model?
    - Jelaskan dengan analogi: gradien itu seperti apa dalam kehidupan nyata?
3. Buat gambar sederhana:
    - Fungsi 2 variabel dan arah vektor gradien (boleh sketsa tangan).
4. (Bonus) – Jika kamu membuat AI yang bisa belajar dari suhu & kelembapan (2 variabel), bagaimana peran turunan parsialnya?
