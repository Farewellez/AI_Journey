# **Hari Senin: Konsep Turunan (Derivatives)**

---

### 🎯 **Tujuan Hari Ini:**

- Memahami konsep dasar turunan secara visual dan matematis.
- Mengenal turunan sebagai pondasi teknik optimasi dalam machine learning, terutama untuk pelatihan model.
- Menumbuhkan intuisi tentang "bagaimana perubahan kecil di input memengaruhi output" — kunci utama dalam training neural network dengan **gradient descent**.

---

### 📚 **Materi Inti:**

1. **Apa itu Turunan?**
    - Definisi formal turunan dari limit:
    - Intuisi: "seberapa cepat perubahan terjadi".
    
    $$
    f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}
    $$
    
2. **Makna Geometris Turunan:**
    - Turunan sebagai **kemiringan garis singgung** di suatu titik pada kurva.
3. **Limit sebagai Dasar Turunan:**
    - Limit → dasar konseptual turunan, jadi ini membantu memperkuat logika perubahan kecil dalam input.

---

### 🔁 **Keterkaitan dengan Roadmap AI-mu:**

- **Training Model AI** (misalnya neural network) menggunakan algoritma **Gradient Descent**, yang *inti mekanismenya adalah turunan*.
- **Loss function** akan dihitung turunan parsialnya terhadap parameter model → digunakan untuk *update* parameter agar error makin kecil.
- Di dunia nyata, hampir semua algoritma AI modern seperti **backpropagation**, **logistic regression**, **SVM**, pakai konsep ini.

⏳ Jadi kalau kamu paham *turunan hari ini*, kamu sedang meletakkan pondasi *training model AI secara matematis*. 🔧

---

### 🔗 **Referensi Materi:**

- 🎥 3Blue1Brown – [Essence of Calculus Chapter 2: Derivatives](https://youtu.be/I9GqZDT1iF8) → **Visual terbaik** untuk memahami turunan.
- 📘 Khan Academy – [Intro to Derivatives](https://www.khanacademy.org/math/calculus-1/cs1-derivatives-defn) → **Dasar teori + latihan soal.**
- 📄 Artikel ringan – [Derivatives in Machine Learning – GeeksForGeeks](https://www.geeksforgeeks.org/derivatives-in-machine-learning/) → Penjelasan khusus turunan dalam ML.

---

### 🛠️ **Praktik Ringan (Aktif & Visual):**

1. **Plot & Garis Singgung Manual:**
    
    $$
    
    \text{Gambar grafik fungsi} \hspace{0.1 cm} y = x^2 \hspace{0.1 cm} \text{dan} y = \sin{x}
    $$
    
    - Pilih titik, lalu gambarlah garis singgung → temukan kemiringannya secara manual.
    - ✏️ **Tools rekomendasi**:
        - [Desmos Graphing Calculator (Online & Gratis)](https://www.desmos.com/calculator)
        - GeoGebra: [Graphing Calculator](https://www.geogebra.org/graphing)
2. **Eksplorasi Interaktif:**
    - [Derivative Grapher by Intmath](https://www.intmath.com/functions-and-graphs/interactive-derivative.php)
    - Ubah fungsi & lihat langsung perubahan grafik turunannya.

---

### 🎁 **Oleh-Oleh (Latihan Reflektif & Konkrit):**

1. Jelaskan **apa arti turunan** dalam **2 kalimat sederhana** pakai kata-katamu sendiri.

$$
\text{Ambil 1 fungsi dari referensi (misal}\hspace{0.1 cm} f(x)=x^ 2\hspace{0.1 cm}\text{atau}\hspace{0.1 cm}f(x) = \sin⁡(x)), \text{lalu hitung turunannya secara manual.}
$$

1. Temukan contoh perubahan kecil (contoh real life) yang bisa dimodelkan dengan konsep turunan (misalnya: kecepatan mobil → posisi).
2. [Opsional] Coba latihan soal turunan interaktif di Khan Academy:
    
    👉 [Latihan soal turunan dasar](https://www.khanacademy.org/math/calculus-1/cs1-derivatives-defn)
