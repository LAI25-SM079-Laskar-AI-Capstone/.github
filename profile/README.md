# 🏠 Realestica – Solusi Cerdas Prediksi & Rekomendasi Properti

**ID Grup**: SM079-LAI  
**Tema**: Solusi Cerdas untuk Masa Depan yang Lebih Baik

## 👥 Anggota Tim
| ID Peserta   | Nama Lengkap                             | Institusi             |
|--------------|-------------------------------------------|------------------------|
| A251YBM006   | Abil Khairi                               | Universitas Malikussaleh            |
| A299YBM348   | Muhammad Rizki                            | Universitas Pendidikan Indenesia            |
| A200XBF416   | Ramadhani Sarah Alicya Bilqis             | Universitas Diponegoro            |
| A248YBM468   | Steven C Michael                          | Universitas Lampung    |

---

## 📌 Latar Belakang

Pasar properti di Jakarta sangat dinamis namun sering kali tidak transparan. Banyak platform properti belum mengintegrasikan kecerdasan buatan untuk membantu pengguna menilai kewajaran harga maupun mendapatkan rekomendasi properti yang relevan.

**Realestica** hadir sebagai solusi prediksi harga rumah dan sistem rekomendasi properti berbasis **machine learning**, yang mempertimbangkan:

- Spesifikasi rumah
- Fasilitas tambahan
- Faktor lingkungan sekitar
- Legalitas properti
- Akses ke fasilitas umum

Tujuan kami adalah menghadirkan pengalaman transaksi properti yang lebih **cerdas, efisien, dan adil**.

---
## 🖥️ Demo
- Video/Foto
- Realestica dapat diakses pada tautan berikut: [Realestica Website](https://realestica.netlify.app/)

--
## 🧩 Arsitektur Proyek
Diagram arsitektur Realestica
![image](https://github.com/user-attachments/assets/291e37cd-6e3e-46b5-b4da-a214fbaf22ad)

Realestica terdiri dari beberapa komponen utama:

### 1. 📦 [House Property Data Scraper](https://github.com/MuhammadRizki8/house-property-data-scraper)
Web scraper untuk mengumpulkan data properti dari [Rumah123.com](https://www.rumah123.com).  
> ⚠️ Hanya untuk keperluan edukasi (Capstone Project Laskar AI).

**Teknologi**:
- Python 3
- Requests
- BeautifulSoup
- Pandas
- Logging

---

### 2. 🤖 Realestica Machine Learning

Pengembangan model machine learning untuk prediksi harga rumah di wilayah Jakarta.

**Tahapan Utama**:
- 📄 *Data Cleaning* (ekstraksi fasilitas, spesifikasi, POI, lokasi)
- 📊 *Exploratory Data Analysis*
- 🔍 *Feature Engineering & Selection*
- 🧠 *Model Training & Evaluation*
- 💾 *Model Deployment*

**Dataset**:  
> 50,464 baris dan 57 kolom properti (Jakarta area)

---

### 3. 🔌 Realestica Property Management API

Sistem backend berbasis **FastAPI** untuk CRUD properti dan integrasi model prediksi.

🔗 **Live Demo**:  
[https://realesticebe-production.up.railway.app/docs](https://realesticebe-production.up.railway.app/docs)

**Fitur**:
- ✅ CRUD properti
- 🔍 Filtering & sorting
- 📊 Statistik properti
- 🧠 Prediksi harga rumah
- 🔁 Pagination, Health check, CORS, Validasi Pydantic

**Stack**:
- FastAPI
- SQLAlchemy
- PostgreSQL
- Scikit-learn
- Uvicorn

---

### 4. 🔮 Realestica Price Prediction API

API prediksi harga properti berdasarkan 39+ fitur rumah, lokasi, dan fasilitas.

**Fitur Unggulan**:
- ⚡ Fast prediction (preloaded model)
- 🎯 Akurasi tinggi
- 📍 Lokasi-aware (Jakarta Barat, Timur, Selatan, Utara, Pusat)
- 🔐 Input divalidasi otomatis

---

### 5. 🧭 Realestica Recommendation System

Sistem rekomendasi properti berdasarkan kemiripan dan kriteria pencarian.

🔗 **Live Demo**:  
[https://realestica-recommendation-system-production.up.railway.app](https://realestica-recommendation-system-production.up.railway.app)

**Fitur**:
- 🧬 Similar property matching
- 🔎 Pencarian berbasis kriteria (fitur, lokasi, harga, dsb)
- 📈 Statistik performa sistem
- 🧠 Backend ML untuk clustering & similarity score

---

### 6. 🎨 Realestica Frontend

Antarmuka pengguna berbasis **React**, dengan teknologi modern:
🔗 **Live Demo**:  
[https://realestica.netlify.app/](https://realestica.netlify.app/)
**Stack**:
- React
- TypeScript
- Vite
- TailwindCSS

---


