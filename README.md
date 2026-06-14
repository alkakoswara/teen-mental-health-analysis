# Analisis Kesehatan Mental Remaja & Gaya Hidup Digital

## 📌 Gambaran Proyek
Proyek ini menandai langkah besar pertama saya di bidang Analitik Data. Dikembangkan sebagai tugas kuliah yang menantang, proyek ini mengeksplorasi korelasi penting antara kebiasaan digital remaja (seperti waktu menatap layar dan penggunaan platform) dengan kesejahteraan psikologis mereka (stres, kecemasan, dan depresi). Tujuan dari proyek ini adalah untuk mengubah data mentah yang berantakan menjadi wawasan bisnis yang dapat ditindaklanjuti untuk mendukung inisiatif kesejahteraan digital (digital wellbeing).

## 🛠️ Alat & Teknologi
* **Bahasa Pemrograman:** Python
* **Library:** Pandas (untuk manipulasi dan pembersihan data)
* **Visualisasi:** Google Looker Studio.
* **Environment:** Google Colab.

## 🧹 Alur Pemrosesan Data
Data di dunia nyata jarang sekali sempurna. Tanpa menggunakan bantuan AI tingkat lanjut, saya secara manual membangun alur (pipeline) pembersihan data secara *end-to-end* yang terstruktur:
* **Menangani Nilai Kosong & Duplikat:** Menghapus 151 baris nilai NaN dan 53 entri duplikat untuk memastikan integritas data.
* **Eliminasi Outlier:** Menerapkan metode statistik Interquartile Range (IQR) untuk menyaring anomali ekstrem pada durasi tidur dan usia responden.
* **Feature Encoding:** Mengubah data teks kategorikal menjadi format numerik yang dapat diproses oleh mesin menggunakan Ordinal, Binary, dan One-Hot Encoding.
* **Hasil Akhir:** Berhasil menyaring dataset mentah menjadi 972 baris data bersih dan valid yang siap untuk dianalisis secara matematis.

## 📊 Wawasan & Temuan Utama
Data divisualisasikan melalui dasbor interaktif, yang berhasil mengungkap beberapa pola krusial:
1. **Dampak Waktu Layar (Screen Time):** Terdapat korelasi positif yang kuat antara tingginya durasi penggunaan media sosial harian dengan peningkatan tingkat kecemasan pada remaja.
2. **Kekuatan Interaksi Fisik:** Sebuah anomali menarik ditemukan di mana remaja dengan tingkat interaksi sosial di dunia nyata yang rendah justru menunjukkan rata-rata tingkat stres yang jauh lebih tinggi dibandingkan rekan-rekan mereka yang aktif bersosialisasi.
3. **Validasi Virtual Tidaklah Cukup:** Data memberikan bukti empiris bahwa interaksi daring (online) tidak dapat menggantikan manfaat psikologis dari sosialisasi fisik di dunia nyata sebagai peredam stres alami.

## 🔗 Tautan & Sumber Daya
* **Dasbor Interaktif:** [Lihat di Looker Studio](https://datastudio.google.com/s/naAb8084Bak)
* **Script Python:** [Lihat di Google Colab](https://colab.research.google.com/drive/1B_zBLAjbQjqS7ZtWFtdtlIF1bb7g2Kk9?usp=sharing)[cite: 3]
* **Laporan Lengkap:** Silakan merujuk pada dokumen PDF Laporan Akhir yang disertakan dalam repositori ini untuk rincian mendalam mengenai metodologi dan rekomendasi bisnis.
