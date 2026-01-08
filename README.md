# 💰 Financial Pro (FinPro) - PWA Financial Tracker

Aplikasi pencatat keuangan pribadi modern berbasis web (**Progressive Web App**) yang dirancang dengan antarmuka mewah (Glassmorphism) dan performa tinggi menggunakan **Tailwind CSS** dan **Firebase**.

## ✨ Fitur Utama
- 🛡️ **Autentikasi Aman**: Masuk menggunakan Email & Password melalui Firebase Auth.
- ☁️ **Real-time Sync**: Data tersimpan di Cloud Firestore dan tersinkronisasi secara otomatis di semua perangkat.
- 📱 **PWA Ready**: Dapat diinstal di layar utama (Home Screen) Android atau iOS seperti aplikasi native.
- 💎 **Glassmorphism UI**: Tampilan modern dengan efek blur kaca yang nyaman di mata.
- 📊 **Ringkasan Cerdas**: Penghitungan otomatis Total Saldo, Pemasukan, dan Pengeluaran.
- 🌑 **Dark Mode**: Desain default yang elegan untuk penggunaan di malam hari.

## 🚀 Teknologi yang Digunakan
- **Frontend**: HTML5, Tailwind CSS (via CDN).
- **Backend/Database**: Firebase Firestore (NoSQL).
- **Authentication**: Firebase Auth.
- **Font**: Plus Jakarta Sans (Google Fonts).

## 🛠️ Persiapan & Instalasi

### 1. Prasyarat
Anda memerlukan proyek Firebase. Jika belum punya:
1. Buka [Firebase Console](https://console.firebase.google.com/).
2. Buat proyek baru.
3. Tambahkan "Web App" ke proyek Anda.
4. Aktifkan **Authentication** (Email/Password) dan **Firestore Database**.

### 2. Konfigurasi Firebase
Buka file `index.html`, cari bagian `const firebaseConfig`, dan ganti dengan kredensial milik Anda:

```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_PROJECT_ID.appspot.com",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID"
};
