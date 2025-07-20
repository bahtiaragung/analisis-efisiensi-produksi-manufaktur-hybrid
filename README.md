# Analisis Efisiensi Produksi di Sistem Manufaktur Hybrid

Proyek ini merupakan analisis sistem manufaktur hybrid yang menggabungkan proses *additive* dan *subtractive manufacturing*. Fokus utama analisis adalah mengevaluasi efisiensi produksi berdasarkan konsumsi energi, waktu proses, dan keterlambatan produksi, serta membangun model prediksi efisiensi menggunakan algoritma machine learning.

---

## 📂 Isi Repositori

- `analisis_produksi_hybrid.Rproj`: File project RStudio.
- `analisis_produksi_hybrid.html`: Hasil laporan HTML dari RMarkdown.
- `hybrid_manufacturing_categorical.csv`: Dataset produksi.
- `README.md`: Deskripsi proyek ini.

---

## 📊 Tujuan Analisis

- Mengukur efisiensi berdasarkan waktu dan energi.
- Menilai status job produksi (Completed, Delayed, Failed).
- Menganalisis keterlambatan produksi.
- Membangun model prediktif menggunakan Random Forest.

---

## 🔗 Sumber Dataset

Dataset tersedia di Kaggle:  
📎 https://www.kaggle.com/datasets/ziya07/manufacturing-production-data

---

## 🔗 Notebook Kaggle

📎 (Tambahkan link setelah kamu upload ke Kaggle)  
https://www.kaggle.com/code/agungbahtiar/analisis-efisiensi-produksi-di-sistem-hybrid

---

## 📈 Ringkasan Hasil Model

- Model: Random Forest
- Akurasi: **95.3%**
- Kappa: **0.9163**
- Fitur paling berpengaruh: `Delay_Minutes`, `Energy_Consumption`, `Processing_Time`

---

## 📌 Catatan Tambahan

Laporan ini dibuat dengan RStudio dan dapat dikembangkan lebih lanjut dengan algoritma lain seperti XGBoost atau penambahan fitur tambahan dari produksi.
