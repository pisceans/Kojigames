# Kojigames

# 🍌 Koji Jungle Adventure

[![Web3 Project](https://img.shields.io/badge/Sector-Web3%20Gaming-blueviolet)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Koji Jungle Adventure** adalah sebuah game platformer berbasis web yang dikembangkan menggunakan **HTML5 Canvas** dan **Vanilla JavaScript**. Game ini mengusung estetika *16-bit retro pixel art* dan menampilkan karakter utama bernama Koji dalam misi mengumpulkan pisang di hutan tropis yang berbahaya.

Proyek ini merupakan demonstrasi dari implementasi logika game sederhana, sistem koordinat 2D, deteksi tabrakan (*collision detection*), serta manajemen aset digital dalam lingkungan Web3.

## 🕹️ Demo & Gameplay
Anda dapat memainkan game ini langsung melalui GitHub Pages:
**[KLIK DI SINI UNTUK BERMAIN](https://pisceans.github.io/-ANIMAL/)** (Sesuaikan dengan URL asli Anda)

### Kontrol:
- **Panah Kiri / Kanan**: Berjalan
- **Spasi / Panah Atas**: Melompat
- **Tujuan**: Kumpulkan pisang sebanyak mungkin dan hindari musuh serta rintangan untuk mencapai skor tertinggi.

## 🛠️ Fitur Teknis
- **Dynamic Physics**: Implementasi gravitasi, gaya lompat, dan akselerasi karakter yang halus.
- **Patrol AI**: Musuh memiliki logika patroli otomatis dengan kemampuan berbalik arah (*sprite flipping*) secara dinamis.
- **Animated Collectibles**: Item pisang menggunakan fungsi sinosoidal untuk memberikan efek melayang (*hover effect*) yang hidup.
- **Responsive Canvas**: Dirancang untuk berjalan optimal pada browser modern dengan performa tinggi.
- **Retro Visuals**: Konsistensi gaya pixel art di seluruh aset (Karakter, Musuh, Rintangan, dan Latar Belakang).

## 📁 Struktur Aset
| Aset | Deskripsi |
| :--- | :--- |
| `Koji.png` | Main Character (Fighter dengan atribut 'BEAST') |
| `banana.png` | Collectible Item (Target skor) |
| `enemy.png` | Monster Merah (Bipedal patrol enemy) |
| `stone.png` & `box.png` | Rintangan statis lingkungan |
| `background.png` | Hutan tropis pixel art 16-bit |

## 🚀 Instalasi Lokal
Jika Anda ingin menjalankan atau mengembangkan game ini di komputer lokal:

1. Clone repositori ini:
   ```bash
   git clone [https://github.com/pisceans/koji-adventure.git](https://github.com/username/koji-adventure.git)
