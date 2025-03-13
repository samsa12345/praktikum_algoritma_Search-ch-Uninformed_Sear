# praktikum_algoritma_Search-ch-Uninformed_Sear
2306143
Berikut adalah template README yang dapat Anda gunakan untuk repository GitHub Anda, berdasarkan deskripsi yang Anda berikan:

```markdown
# Implementasi Algoritma Pencarian dalam Python

Repository ini berisi berbagai implementasi algoritma pencarian dalam bahasa Python, mencakup berbagai teknik pencarian yang digunakan untuk menyelesaikan masalah pencarian dalam graf.

## 🔍 Pencarian Tanpa Informasi (Uninformed Search)

### 1. **DFS (Depth First Search)**
   - Menelusuri graf dengan mendalami satu cabang terlebih dahulu sebelum kembali ke node sebelumnya.

### 2. **BFS (Breadth First Search)**
   - Menelusuri graf secara melebar dengan mengunjungi semua node pada satu tingkat sebelum berpindah ke tingkat berikutnya.

### 3. **UCS (Uniform Cost Search)**
   - Mencari jalur dengan biaya paling rendah berdasarkan bobot antar node.

Algoritma ini digunakan untuk menemukan jalur optimal dalam suatu graf menggunakan pendekatan pencarian tanpa informasi tambahan (uninformed). Selain itu, algoritma ini juga dapat dikembangkan lebih lanjut untuk pencarian dengan heuristik (informed search).

## 📁 Struktur Repository

- `dfs.py` → Implementasi Depth First Search
- `bfs.py` → Implementasi Breadth First Search
- `ucs.py` → Implementasi Uniform Cost Search

Setiap file berisi kode algoritma serta contoh penggunaannya yang dapat diuji langsung.

## 🚀 Menjalankan di Google Colab

Untuk menjalankan algoritma-algoritma ini di Google Colab atau komputer lokal Anda, ikuti langkah-langkah berikut:

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/username/repository-name.git
   ```

2. **Masuk ke direktori repository:**
   ```bash
   cd repository-name
   ```

3. **Jalankan skrip Python yang diinginkan:**
   - Untuk menjalankan DFS:
     ```bash
     python dfs.py
     ```
   - Untuk menjalankan BFS:
     ```bash
     python bfs.py
     ```
   - Untuk menjalankan UCS:
     ```bash
     python ucs.py
     ```

