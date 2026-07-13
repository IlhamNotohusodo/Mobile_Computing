# Stelan

**Stelan** adalah aplikasi mobile berbasis AI untuk membantu pengguna menemukan dan mencoba kombinasi outfit secara virtual (*virtual try-on*), lengkap dengan fitur rekomendasi pakaian dan manajemen wardrobe pribadi.

## 📱 Preview

Desain UI/UX dapat dilihat pada file Figma berikut:
[Tugas.project - Figma](https://www.figma.com/design/fOnfMLX3cYcjVJxjfTtekg/Tugas.project)

##  Fitur Utama

### 1. Autentikasi (Sign In / Sign Up)
- Login menggunakan email & password
- Opsi login cepat melalui **Instagram**, **Apple**, dan **Google**
- Fitur "Forgot Password" dan pendaftaran akun baru

### 2. Home
- Sapaan personal (contoh: *"Good Morning, Ilham what's your look today?"*)
- Banner **Virtual Try-On** untuk langsung mencoba fitur AI
- Kategori pakaian: **All, Tops, Bottoms, Shoes**, dll.
- Daftar koleksi pakaian pengguna (wardrobe preview)

### 3. Virtual Try-On (Kamera)
- Mengambil foto tubuh penuh menggunakan kamera dengan garis bantu (grid guide) agar posisi badan pas
- Tombol capture foto dengan opsi switch kamera

### 4. Pose Guide
- Menampilkan hasil foto yang telah diambil
- Tombol **"Change Outfit"** untuk mengganti pakaian yang dikenakan pada foto

### 5. Rekomendasi Pakaian (Recommend Clothes)
- Sistem menampilkan rekomendasi outfit berdasarkan foto pengguna (jaket, sweater, celana, sepatu)
- Tombol **"Next"** untuk melanjutkan ke tahap hasil akhir

### 6. Hasil (Result)
- Menampilkan visualisasi akhir pengguna mengenakan kombinasi outfit yang direkomendasikan/dipilih

## 🧭 Navigasi Utama (Bottom Navigation Bar)
Tersedia di sebagian besar halaman utama:
- 🏠 **Home**
- 👔 **Wardrobe**
- 📷 **Camera** (Virtual Try-On, ikon ditonjolkan/highlight merah)
- 🛍️ **Shop**
- 👤 **Profile**

## 🎨 Alur Pengguna (User Flow)

```
Welcome / Sign In
      │
      ▼
    Home  ──────► Categories & Wardrobe
      │
      ▼
Virtual Try-On (Kamera)
      │
      ▼
   Pose Guide  ──► Change Outfit
      │
      ▼
Recommend Clothes
      │
      ▼
     Result
```

Link Figma : https://www.figma.com/design/fOnfMLX3cYcjVJxjfTtekg/Tugas.project?node-id=0-1&t=wQdMPkBzIs5YCQPf-1
