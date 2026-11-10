# Portofolio
## 📂 Ringkasan Proyek Utama

### 1. 📈 Crypto Market & Sentiment Dynamics Analysis (BTC vs. ETH)
* **Fokus:** Behavioral Finance, Financial Data Analysis, NLP Sentiment Analysis.
* **Deskripsi:** Menganalisis korelasi antara skor sentimen harian berita finansial terhadap *daily return* dan volatilitas harga Bitcoin (BTC) dan Ethereum (ETH) menggunakan `TextBlob` dan `yfinance`.
* **Temuan Utama:** 
  - Sentimen berita harian memiliki korelasi linear yang lemah terhadap *daily return* (BTC $r=0.09$, ETH $r=-0.03$), menunjukkan pasar lebih didorong oleh likuiditas makroekonomi.
  - Hasil *Lag-1 Analysis* menunjukkan pasar kripto sangat efisien dalam menyerap informasi publik tanpa jeda hari berikutnya.
* **Tech Stack:** Python, Pandas, TextBlob, Seaborn, yfinance.
* 🔗 **[Lihat Detail Proyek & Kode]()**

---

### 2. 🌧️ pemodelan Kejadian Banjir Jawa Tengah Menggunakan Regresi Poisson (GLM)
* **Fokus:** Statistical Modeling, Spatial/Environmental Data Analysis, Disaster Mitigation.
* **Deskripsi:** Memodelkan faktor-faktor yang memengaruhi frekuensi kejadian banjir di 35 Kabupaten/Kota Jawa Tengah tahun 2024 menggunakan *Generalized Linear Model* (GLM) distribusi Poisson.
* **Temuan Utama:**
  - Ketinggian wilayah ($p = 0.000$) dan total deforestasi lahan ($p = 0.023$) terbukti berpengharuh signifikan terhadap kejadian banjir.
  - Curah hujan dan kepadatan penduduk tidak signifikan secara statistik dalam model count data ini.
  - Seluruh variabel bebas terbebas dari multikolinearitas ($VIF < 10$).
* **Tech Stack:** Python, Statsmodels, Pandas, Matplotlib.
* 🔗 **[Lihat Detail Proyek & Kode]()**

---

### 3. 🔐 Kriptografi Berbasis Grup Permutasi ($S_n$)
* **Fokus:** Applied Mathematics, Cryptography, Group Theory.
* **Deskripsi:** Mengimplementasikan algoritma enkripsi dan dekripsi pesan berbasis **Grup Simetri/Permutasi $S_n$** untuk mengamankan teks informasi.
* **Fitur Utama:**
  - Pengacakan posisi karakter harian per blok dengan *padding* otomatis (`$`) dan penanganan spasi (`#`).
  - Proteksi otomatis dari permutasi identitas agar *ciphertext* tidak persis sama dengan *plaintext*.
  - Dekripsi presisi tinggi menggunakan invers permutasi $\theta^{-1}$.
* **Tech Stack:** Python (Pure Python / Standard Libraries).
* 🔗 **[Lihat Detail Proyek & Kode]()**

---
