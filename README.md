# Project_Freelancer
# Exploratory Data Analysis (EDA) – Freelancer Dataset (Fiktif)

Dataset ini berisi data fiktif mengenai profil 1.001 freelancer dari berbagai negara di dunia.  
Tujuan utama dari project ini adalah latihan proses EDA (*Exploratory Data Analysis*) termasuk penanganan data duplikat, missing value, normalisasi data, dan deteksi outlier.

## Tentang Dataset
- **Jumlah baris:** 1.001  
- **Jumlah kolom:** 12  
- **Sumber data:** Dibuat secara fiktif (bukan data asli).  
- **Catatan:** Dataset aslinya terdiri dari 1.000 baris unik, kemudian sengaja ditambahkan 1 baris duplikat untuk keperluan demonstrasi tahap *handle duplicate*.

### Variabel Utama
- `name` : Nama freelancer (fiktif)
- `age` : Usia
- `country` : Negara asal
- `primary_skill` : Keahlian utama (contoh: DevOps, Data Scientist)
- `years_of_experiance` : Lama pengalaman (tahun)
- `hourly_rate (USD)` : Tarif per jam
- `is_active` : Status aktif (0/1)
- `client_satisfaction` : Persentase kepuasan klien

## ✨ Tujuan Project
- Melakukan ringkasan awal dataset (jumlah baris, kolom, tipe data)
- Menangani **missing value** (imputasi dengan mean, median, atau modus sesuai variabel)
- Menormalisasi data (contoh: menghapus simbol `%` pada `client_satisfaction`)
- Menangani **data duplikat** (menghapus 1 baris duplikat yang sengaja ditambahkan)
- Deteksi **outlier** pada variabel numerik dengan boxplot
- Analisis sederhana seperti:
  - Jumlah freelancer per negara
  - Negara dengan freelancer DevOps terbanyak
  - Distribusi variabel numerik
