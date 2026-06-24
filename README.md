# Yatzy Dice Game 🎲

Implementasi game dadu klasik **Yatzy** berbasis Web. Proyek ini dibuat menggunakan kombinasi **Java Servlet** untuk backend (logika permainan) dan **HTML/CSS/JS** untuk antarmuka pengguna (UI) yang interaktif untuk **Tugas Besar** Mata Kuliah **PBO**.

## 🧑 Anggota Kelompok

| No  |           Nama            |          NIM |
| :-- | :-----------------------: | -----------: |
| 1   |   A Muh Imran Ramadhan    | 103012400371 |
| 2   |       Ahmad Kadhim        | 103012400230 |
| 3   |       Hamad Dafala        | 103012400386 |
| 4   |     Rafi Dzaki Azhari     | 103012400336 |
| 5   | Arsha Athalla Putra Satya | 103012400062 |
| 6   |   Fadhil Syahda Andira    | 103012430052 |

## 🌟 Fitur Utama

- **Singleplayer vs AI:** Tantang AI dengan strategi pintar yang akan memilih skor terbaik secara otomatis. Musuh bot juga memiliki nama-nama unik yang diacak!
- **Local Multiplayer:** Main bareng teman secara bergantian (_pass-and-play_).
- **Sistem Perhitungan Skor Otomatis:** Perhitungan kategori Yatzy seperti _Three of a kind_, _Full House_, _Small/Large Straight_, dan _Yatzy_ dilakukan langsung oleh `RuleEngine`.
- **UI Modern & Interaktif:** Desain elegan bernuansa _maroon_ (merah marun) dan emas, dilengkapi dengan animasi kocok dadu, kustomisasi avatar pemain, serta musik latar interaktif (_menu audio_ & _in-game audio_).

## 🛠️ Teknologi yang Digunakan

- **Backend:** Java, Java Servlets.
- **Frontend:** HTML5, CSS3, Vanilla JavaScript.
- **Arsitektur:** Menggunakan pola arsitektur MVC (Model-View-Controller).

## 📂 Struktur Folder Utama

- `src/java/com/yatzy/model/`: Inti logika permainan (Entitas Dadu, Pemain, Kartu Skor, AI, dan Aturan Game).
- `src/java/com/yatzy/controller/`: Servlet API yang menjadi jembatan antara Frontend dan Backend (`GameServlet`).
- `web/`: Semua file frontend, termasuk:
  - `index.html`: Struktur halaman.
  - `css/style.css`: Gaya tampilan visual.
  - `js/app.js`: Logika interaksi antarmuka pengguna.
  - `assets/`: Aset gambar dan musik latar.

## 🚀 Cara Menjalankan Project

1. **Clone Repository:**
   ```bash
   git clone https://github.com/rdzvoltgt3/Pemrograman-Berorientasi-Objek_Tugas-Besar.git
   ```
2. **Buka di IDE:** Buka proyek ini di IDE Java yang mendukung Web Application (seperti **Apache NetBeans**, **Eclipse**, atau **IntelliJ IDEA Ultimate**).
3. **Konfigurasi Server:** Pastikan kamu sudah mensetting _web server_ lokal (misalnya Apache Tomcat atau Glassfish).
4. **Build & Run:** Jalankan proyek (_Run/Deploy_) dari IDE. Server akan otomatis melakukan _build_ dan membuka _browser_ ke halaman utama permainan Yatzy.
