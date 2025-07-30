# Aulia Snack App 🍱

Aplikasi pemesanan makanan ringan berbasis web dan Android. Frontend ditampilkan melalui WebView Android Studio, backend menggunakan Node.js dan database SQLite.

---

## 🎯 Fitur Utama

- Input nama pembeli dan jumlah pesanan per item.
- Perhitungan otomatis total harga per item dan total keseluruhan.
- Penyimpanan data pesanan ke backend menggunakan `fetch()`.
- Disimpan ke database SQLite via backend Node.js.
- Kompatibel dengan Android melalui **WebView** dan **Genymotion emulator**.

---

## 💻 Teknologi

| Bagian     | Teknologi                        |
|------------|----------------------------------|
| Frontend   | HTML, CSS, JavaScript            |
| Backend    | Node.js, Express.js              |
| Database   | SQLite                           |
| Android    | Kotlin, WebView, Android Studio  |
| Emulator   | Genymotion                       |

---

## 🚀 Cara Menjalankan

### 1. Menjalankan Backend (Node.js)

```bash
cd backend
npm install
node server.js
