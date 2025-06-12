# 🏠 Realestica – Solusi Cerdas Prediksi & Rekomendasi Properti

**ID Grup**: SM079-LAI  
**Tema**: Solusi Cerdas untuk Masa Depan yang Lebih Baik  

---

## 📚 Daftar Isi
- [👥 Anggota Tim](#-anggota-tim)
- [📌 Latar Belakang](#-latar-belakang)
- [🖥️ Demo](#️-demo)
- [🧩 Arsitektur Proyek](#-arsitektur-proyek)
  - [1. 📦 Data Scraper](#1--data-scraper)
  - [2. 🤖 Machine Learning](#2--machine-learning)
  - [3. 🔌 API Manajemen Properti](#3--api-manajemen-properti)
  - [4. 🔮 API Prediksi Harga](#4--api-prediksi-harga)
  - [5. 🧭 Sistem Rekomendasi](#5--sistem-rekomendasi)
  - [6. 🎨 Frontend Realestica](#6--frontend-realestica)

---

## 👥 Anggota Tim

| ID Peserta   | Nama Lengkap                             | Institusi                          | Kontak                                                                 |
|--------------|-------------------------------------------|------------------------------------|------------------------------------------------------------------------|
| A251YBM006   | Abil Khairi                               | Universitas Malikussaleh           | [![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:abil@example.com) [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/abilkhairi) [![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://instagram.com/abil_ig) |
| A299YBM348   | Muhammad Rizki                            | Universitas Pendidikan Indonesia   | [![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mrizki135790@gmail.com) [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rizki-muhammad-32b4b4203) [![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://instagram.com/rizki.ig) |
| A200XBF416   | Ramadhani Sarah Alicya Bilqis             | Universitas Diponegoro             | [![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sarah@example.com) [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/sarahbilqis) [![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://instagram.com/sarah.ig) |
| A248YBM468   | Steven C Michael                          | Universitas Lampung                | [![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:steven@example.com) [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/stevencm) [![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://instagram.com/steven.ig) |



---

## 📌 Latar Belakang

Pasar properti di Jakarta sangat dinamis namun belum sepenuhnya transparan. Banyak platform belum memanfaatkan kecerdasan buatan (AI) untuk membantu pengguna:

- Menilai kewajaran harga rumah
- Mendapatkan rekomendasi properti yang relevan

### 🎯 Solusi: **Realestica**
Realestica adalah platform prediksi harga rumah & sistem rekomendasi berbasis **Machine Learning**, dengan mempertimbangkan:

- 🏠 Spesifikasi rumah
- 🏢 Fasilitas tambahan
- 🌳 Faktor lingkungan sekitar
- 📜 Legalitas properti
- 🚇 Akses ke fasilitas umum

Tujuan kami adalah menciptakan transaksi properti yang **cerdas, efisien, dan adil**.

---

## 🖥️ Demo

- 📸 Video & Foto dokumentasi
- 🌐 Website: [https://realestica.netlify.app](https://realestica.netlify.app)

---

## 🧩 Arsitektur Proyek

![image](https://github.com/user-attachments/assets/291e37cd-6e3e-46b5-b4da-a214fbaf22ad)

---

### 1. 📦 [Data Scraper](https://github.com/MuhammadRizki8/house-property-data-scraper)

Web scraper untuk mengambil data properti dari [Rumah123.com](https://www.rumah123.com)  
> ⚠️ Hanya untuk keperluan edukasi (Capstone Project Laskar AI).

**Teknologi**:
- Python 3
- Requests
- BeautifulSoup
- Pandas
- Logging

---

### 2. 🤖 Machine Learning

Model ML untuk prediksi harga rumah wilayah Jakarta.

**Langkah-langkah**:
- 📄 *Data Cleaning* (fasilitas, lokasi, POI)
- 📊 *Exploratory Data Analysis*
- 🧠 *Model Training & Evaluation*
- 🚀 *Deployment*

**Dataset**:  
> 50.464 baris, 57 kolom properti (Jakarta area)

---

### 3. 🔌 API Manajemen Properti

Backend FastAPI untuk operasi CRUD properti & integrasi model prediksi.

🔗 [API Docs](https://realesticebe-production.up.railway.app/docs)

**Fitur**:
- ✅ Tambah, edit, hapus properti
- 🔍 Filtering & sorting
- 📈 Statistik properti
- 🧠 Prediksi harga rumah
- 🔁 Pagination, health check, validasi

**Stack**:
- FastAPI, SQLAlchemy, PostgreSQL, Uvicorn, Scikit-learn

---

### 4. 🔮 API Prediksi Harga

API untuk prediksi harga properti berdasarkan 39+ fitur.

**Fitur**:
- ⚡ Prediksi cepat (model preloaded)
- 📍 Lokasi-aware: Jakarta Barat, Timur, Selatan, Utara, Pusat
- 🧠 Akurasi tinggi
- 🔐 Validasi input otomatis

---

### 5. 🧭 Sistem Rekomendasi

Sistem rekomendasi properti berdasarkan kemiripan dan kriteria pencarian.

🔗 [Live Recommendation System](https://realestica-recommendation-system-production.up.railway.app)

**Fitur**:
- 🧬 Pencarian properti serupa
- 🗺️ Kriteria lokasi, harga, fitur
- 📊 Statistik performa sistem
- 🤖 Backend ML untuk clustering & similarity scoring

---

### 6. 🎨 Frontend Realestica

Tampilan antarmuka pengguna berbasis React.

🔗 [Frontend Website](https://realestica.netlify.app)

**Stack**:
- React
- TypeScript
- Vite
- TailwindCSS

---

