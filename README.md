# Kalibrasi Penetas Yontech

Aplikasi web sederhana untuk membantu proses **kalibrasi suhu mesin penetas telur** secara cepat dan akurat.  
Dibuat menggunakan HTML, CSS, dan JavaScript tanpa framework tambahan.

---

## ✨ Fitur

- Input suhu standar (acuan)
- Input suhu terbaca alat
- Input nilai offset kalibrasi saat ini
- Perhitungan otomatis realtime
- Menampilkan:
  - Nilai koreksi
  - Status suhu
  - Setting kalibrasi baru
- Tampilan dark mode modern
- Efek display digital merah
- Responsive dan ringan

---

## 📸 Tampilan

Tambahkan screenshot aplikasi di folder repo:

```bash
/assets/screenshot.png
```

Lalu tampilkan di README:

```md
![Preview](assets/screenshot.png)
```

---

## 🧮 Cara Kerja Kalibrasi

Rumus yang digunakan:

```text
Koreksi = Suhu Standar - Suhu Terbaca Alat

Kalibrasi Baru = Offset Saat Ini + Koreksi
```

Contoh:

| Input | Nilai |
|---|---|
| Suhu Standar | 37.5°C |
| Suhu Alat | 36.8°C |
| Offset Saat Ini | 0.5 |

Hasil:

```text
Koreksi = +0.7
Kalibrasi Baru = +1.2
```

---

## 🚀 Cara Menjalankan

### 1. Clone Repository

```bash
git clone https://github.com/username/kalibrasi-penetas.git
```

### 2. Masuk Folder

```bash
cd kalibrasi-penetas
```

### 3. Jalankan

Cukup buka file:

```bash
index.html
```

di browser.

---

## 🌐 Deploy ke GitHub Pages

1. Upload project ke GitHub
2. Buka:

```text
Settings → Pages
```

3. Pada bagian:

```text
Source → Deploy from branch
```

4. Pilih:

```text
Branch: main
Folder: /root
```

5. Save

GitHub Pages akan aktif di:

```text
https://username.github.io/kalibrasi-penetas/
```

---

## 📁 Struktur Project

```text
kalibrasi-penetas/
│
├── index.html
├── README.md
└── assets/
    └── screenshot.png
```

---

## 🛠️ Teknologi

- HTML5
- CSS3
- JavaScript Vanilla
- Font Awesome
- Digital-7 Font

---

## 📌 Status Kalibrasi

| Status | Arti |
|---|---|
| Rendah | Suhu alat lebih rendah dari standar |
| Tinggi | Suhu alat lebih tinggi dari standar |
| Akurat | Suhu sudah sesuai |

---

## 👨‍💻 Developer

**Yontech**  
© 2026

---

## 📜 License

Project ini bebas digunakan untuk kebutuhan pribadi maupun edukasi.
