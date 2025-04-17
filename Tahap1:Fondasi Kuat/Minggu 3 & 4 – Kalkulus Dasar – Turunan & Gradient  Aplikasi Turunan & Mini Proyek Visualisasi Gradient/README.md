# Minggu 3 & 4 – Kalkulus Dasar – Turunan & Gradient  Aplikasi Turunan & Mini Proyek Visualisasi Gradient
**🎯 Tujuan:**

- Memahami konsep turunan dari sudut pandang perubahan dan kemiringan kurva
- Mengenal gradien sebagai turunan multivariabel dalam konteks machine learning
- Latihan turunan fungsi dasar & aplikasinya dalam optimasi model ML

---

### 📆 Breakdown Harian & Rundown

### ✅ **Hari Senin – Konsep Turunan (Derivatives)**

**📚 Materi:**

- Apa itu turunan?
- Makna geometris: kemiringan garis singgung
- Limit sebagai dasar turunan

**🔗 Referensi:**

- 3Blue1Brown – [The Essence of Calculus, Chapter 2: Derivatives](https://youtu.be/I9GqZDT1iF8)
- Khan Academy – [Intro to Derivatives](https://www.khanacademy.org/math/calculus-1/cs1-derivatives-defn)

**🛠️ Praktik Ringan:**

- Plot fungsi sederhana (misal y = x², y = sin(x)) dan gambar garis singgung manual di titik tertentu

**🎁 Oleh-oleh:**

- Jelaskan apa arti turunan dalam 2 kalimat sederhana
- Ambil 1 fungsi (boleh dari referensi), lalu hitung turunan manualnya

---

### ✅ **Hari Selasa – Aturan Dasar Turunan**

**📚 Materi:**

- Aturan turunan fungsi:
    - Konstanta
    - Pangkat (power rule)
    - Penjumlahan, pengurangan
    - Perkalian (product rule)
    - Pembagian (quotient rule)

**🔗 Referensi:**

- Khan Academy – [Derivative Rules](https://www.khanacademy.org/math/ap-calculus-ab/ab-diff-analytical-applications-new)
- [YouTube: Calculus 1 - Basic Derivatives Rules](https://www.youtube.com/watch?v=_yq7zTQrtGg)

**🛠️ Praktik Ringan:**

- Hitung turunan dari 5 fungsi kombinasi (pakai aturan yang berbeda)

**🎁 Oleh-oleh:**

- Tulis 3 fungsi dan turunan manualnya
- Buat catatan ringkas: kapan pakai product rule vs quotient rule

---

### ✅ **Hari Rabu – Gradien & Turunan Multivariabel**

**📚 Materi:**

- Turunan untuk fungsi multivariabel (∂/∂x, ∂/∂y)
- Gradien sebagai arah perubahan tercepat
- Aplikasi gradien di optimasi model AI

**🔗 Referensi:**

- 3Blue1Brown – [Gradient (partial derivatives)](https://youtu.be/IoUX_3qgV5g)
- Khan Academy – [Multivariable Derivatives](https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives)

**🛠️ Praktik Ringan:**

- Latihan hitung ∂f/∂x dan ∂f/∂y dari fungsi dua variabel sederhana

**🎁 Oleh-oleh:**

- Jelaskan arti gradien dalam konteks “AI belajar dari kesalahan”
- Buat visualisasi atau analogi sendiri soal gradien

---

### ✅ **Hari Kamis – Penerapan Turunan di Machine Learning**

**📚 Materi:**

- Fungsi Loss dan Optimasi
- Gradien Descent
- Peran turunan untuk mencari nilai minimum fungsi

**🔗 Referensi:**

- [YouTube: Gradient Descent Explained](https://www.youtube.com/watch?v=sDv4f4s2SB8)
- Book: Grokking Deep Learning – Chapter on Optimizers

**🛠️ Praktik Ringan:**

- Simulasi konsep loss vs gradient di kertas atau tools online
- Gunakan NumPy untuk menghitung gradien manual fungsi sederhana

**🎁 Oleh-oleh:**

- Jelaskan “gradient descent” seolah-olah kamu menjelaskannya ke anak SD
- Simulasikan loss function dalam bentuk grafik atau tabel

---

### ✅ **Hari Jumat – Mini Proyek: Visualisasi Gradient**

**📚 Tujuan:**

- Menghubungkan antara fungsi, turunan, dan visualisasi
- Memahami peran visualisasi dalam debugging model

**🛠️ Praktik:**

- Buat plot 2D fungsi (misal: y = x², y = sin(x))
- Tambahkan garis turunan/gradien di titik tertentu (pakai Matplotlib)

**🎁 Oleh-oleh:**

- Dokumentasikan langkahmu dalam membuat visualisasi
- Refleksi: hal paling membingungkan dari konsep turunan

---

### ✅ **Hari Sabtu – Review & Refleksi Mingguan**

**📚 Aktivitas:**

- Review seluruh materi
- Coba kuis (bisa dari Khan Academy atau buat sendiri)
- Diskusi poin yang bikin penasaran

**🎁 Oleh-oleh Akhir Minggu:**

- Buat jurnal: “Apa yang sekarang kupahami tentang turunan & gradien yang dulu membingungkan?”
- Buat 3 pertanyaan untuk mentoring minggu depan

---

Kalau kamu butuh versi checklist & tabel seperti sebelumnya, tinggal bilang aja ya biar langsung kukemas buat Notion 🧾✨

Semangat, pejuang turunan dan gradient!

---

🎯 Tujuan:

- Memahami bagaimana turunan digunakan dalam optimasi, terutama dalam konteks AI.
- Membangun intuisi tentang *gradient*, *slope*, dan arah perubahan.
- Menerapkan konsep tersebut dalam visualisasi sederhana menggunakan Python

---

### 🗓️ Rundown Harian:

### 📅 **Hari Senin – Konsep Gradient & Arah Perubahan**

- Intuisi gradient sebagai arah turunan terbesar
- Gradient vs slope (1D vs multi-dimensi)
- Contoh visual fungsi 2D dan arah turunan terbesar
- ▶️ Video: [3Blue1Brown – Gradient descent](https://www.youtube.com/watch?v=IHZwWFHWa-w)
- 📄 Baca: Towards Data Science – [What is Gradient Descent?](https://towardsdatascience.com/what-is-gradient-descent-76b7ec3f0cad)

**🛠️ Praktik Ringan:**

- Gambar grafik fungsi 2D (seperti z = x² + y²) dan tandai arah turunan

---

### 📅 **Hari Selasa – Gradient Descent Step-by-Step**

- Apa itu *Gradient Descent*
- Learning rate & konvergensi
- Peran fungsi loss & minimum lokal/global
- Simulasi langkah-langkah descent

**📚 Referensi:**

- YouTube: [Gradient Descent Explained Simply](https://www.youtube.com/watch?v=sDv4f4s2SB8)
- Baca: [The Gradient Descent Algorithm – Explained](https://ml-cheatsheet.readthedocs.io/en/latest/gradient_descent.html)

**🛠️ Praktik Ringan:**

- Simulasi manual 3 langkah *gradient descent* dari fungsi sederhana (misal y = x²)

---

### 📅 **Hari Rabu – Visualisasi Gradient Descent di Python**

- Coding: Visualisasi permukaan fungsi + jalur descent (contour plot)
- Tools: NumPy + Matplotlib

**🎥 Tutorial:** [Gradient Descent Visualization in Python](https://www.youtube.com/watch?v=54u8P1mZVgo)

**🛠️ Praktik Ringan:**

- Tiru visualisasi descent dari tutorial (gunakan fungsi y = x² + y² atau fungsi buatanmu sendiri)

---

### 📅 **Hari Kamis – Mini Proyek Visualisasi**

- Buat sendiri fungsi loss sederhana (misal: fungsi kuadrat atau fungsi dengan lembah)
- Visualisasikan descent path dari titik awal menuju minimum

**🎯 Target Proyek:**

- Visualisasi permukaan fungsi + jalur descent
- Tandai setiap langkahnya dengan panah

---

### 📅 **Hari Jumat – Refleksi & Interpretasi**

- Tulis penjelasanmu sendiri: Apa itu gradient? Kenapa penting di AI?
- Jawab pertanyaan: Kenapa gradient descent bisa gagal? (Overfitting, local minimum, dsb)
- Opsional: Bandingkan metode lain seperti SGD atau momentum secara singkat

---

### 🎁 Oleh-Oleh Latihan Tambahan:

1. Ceritakan dengan analogi: Apa itu gradient descent dalam kehidupan nyata?
2. Buat ilustrasi/tulisan pendek “Perjalanan dari titik tinggi ke lembah dengan gradient”
3. Apa hubungan gradient descent dengan *belajar manusia* menurutmu?
4. Simulasikan kode descent dengan fungsi lain (misal fungsi sigmoid/logistik)
5. [Opsional] Gunakan `matplotlib.animation` untuk membuat descent path yang bergerak

---

Kalau sudah oke, lanjutkan saja, dan beri tahu aku kalau kamu mau versi templatenya untuk Notion atau format .md-nya!
