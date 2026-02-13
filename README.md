# 🖐️ Finger Explosion: Game AI Berbasis Gerakan

Game web bertema neon yang seru di mana jari telunjukmu berubah menjadi senjata! Menggunakan **MediaPipe Hands AI**, pemain akan bertarung dalam uji kecepatan dan presisi secara real-time langsung di browser.

![Lisensi](https://img.shields.io/badge/license-MIT-blue.svg)
![Teknologi](https://img.shields.io/badge/AI-MediaPipe-green.svg)
![Library](https://img.shields.io/badge/Library-jQuery-orange.svg)

---

## 🚀 Fitur Utama

-   **AI Motion Tracking:** Pelacakan tangan real-time menggunakan MediaPipe (tidak butuh stik/controller!).
-   **Mode Dual Player:** Duel lawan teman dalam satu layar (split-screen).
-   **Estetika Neon:** UI bertema Cyberpunk dengan animasi canvas yang halus dan efek partikel ledakan.
-   **HUD Interaktif:** Skor real-time, pengaturan target kemenangan, dan sistem countdown arcade.
-   **Efek Suara Dinamis:** Feedback audio saat memotong target, memulai game, dan saat menang.

## 🛠️ Dibuat Menggunakan

* **MediaPipe Hands:** Untuk deteksi titik jari tangan yang akurat.
* **HTML5 Canvas:** Untuk rendering game dan sistem partikel berperforma tinggi.
* **jQuery:** Untuk manipulasi UI dan transisi menu.
* **Google Fonts (Orbitron):** Memberikan tampilan futuristik ala sci-fi.

---

## 📖 Panduan Pemakaian (User Guide)

Agar pengalaman bermain maksimal, ikuti langkah berikut:

### 1. Persiapan Perangkat
* Pastikan laptop/komputer kamu memiliki **Webcam** yang berfungsi.
* Pastikan pencahayaan di ruangan cukup agar AI bisa mendeteksi tangan dengan jelas.

### 2. Memulai Game
* Buka file `index.html` di browser (Disarankan Google Chrome atau Safari).
* Klik **"Allow/Izinkan"** saat browser meminta akses kamera.
* Pilih kamera yang ingin digunakan pada menu dropdown.
* Masukkan jumlah skor target kemenangan (default: 10).
* Klik tombol **"ENTER ARENA"**.

### 3. Cara Bermain
* Tunggu hitungan mundur (3, 2, 1, GO!).
* Gunakan **Jari Telunjuk** kamu untuk menyentuh bola-bola yang muncul di layar.
* **Pemain 1 (Biru):** Meledakkan bola biru di sisi kanan (layar sudah di-mirror).
* **Pemain 2 (Pink):** Meledakkan bola pink di sisi kiri (layar sudah di-mirror).
* Siapa yang paling cepat mencapai target skor, dialah pemenangnya!

## 📜 Kredit & Atribusi Suara
Proyek ini menggunakan aset suara gratis dari Pixabay. Terima kasih kepada para kreator:

Sfx Slice: Sword Blade Slicing oleh Pixabay.
Sfx Start: Arcade Countdown oleh Pixabay.
Sfx Over: Winning oleh Pixabay.

## ⚖️ Lisensi
Proyek ini menggunakan lisensi MIT. Kamu bebas untuk menggunakan, memodifikasi, dan membagikan ulang kode ini.

---

## 📂 Struktur Proyek

```text
.
├── assets/
│   ├── slice.mp3         # Efek suara saat memotong
│   ├── game-start.mp3    # Efek suara hitungan mundur
│   ├── game-over.mp3     # Efek suara kemenangan
│   └── fav.png           # Icon game
├── index.html            # File utama (HTML, CSS, & JS)
└── README.md             # Dokumentasi proyek

