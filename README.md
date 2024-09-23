# MovieList 🎬

MovieList adalah aplikasi web yang memungkinkan pengguna untuk mencari informasi film menggunakan OMDB API. Aplikasi ini menampilkan detail film seperti judul, tahun rilis, rating, poster, dan deskripsi.

## Fitur ✨
- Cari film berdasarkan judul.
- Menampilkan detail film termasuk poster, sinopsis, rating, dan tahun rilis.
- Tampilan antarmuka yang sederhana dan mudah digunakan.

## Teknologi yang Digunakan 🛠
- **Front-end**: HTML, CSS, JavaScript
- **API**: [OMDB API](http://www.omdbapi.com/)
- **Back-end**: (Opsional, tambahkan jika kamu menggunakan back-end framework atau server)

## Instalasi 🚀

Berikut adalah langkah-langkah untuk menjalankan proyek ini secara lokal.

### 1. Clone Repository
```bash
git clone https://github.com/username/movielist.git
cd movielist
### 2. dapatkan API key dari OMDB API
Daftar ke OMDB API untuk mendapatkan API key.
Setelah mendapatkan API key, simpan di dalam file .env atau di dalam script (untuk proyek ini, API key dapat langsung ditambahkan di file JavaScript).

### 3. Konfigurasi API
Edit file JavaScript di proyek untuk menambahkan API key:
const apiKey = ' f2783983';

### 4. Jalankan Aplikasi
Buka file index.html di browser untuk melihat aplikasi. Kamu bisa juga menggunakan server lokal sederhana seperti Live Server pada Visual Studio Code.

### 5. Endpoint Yang Digunakan
Search movies:
http://www.omdbapi.com/?s={movie_title}&apikey={API_KEY}
Get movie details by ID:
http://www.omdbapi.com/?i={imdb_id}&apikey={API_KEY}

