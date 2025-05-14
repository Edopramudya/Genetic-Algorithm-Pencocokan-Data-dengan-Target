## 🧬 Genetic Algorithm: Pencocokan Data dengan Target

Proyek ini adalah implementasi sederhana dari **Genetic Algorithm (GA)** menggunakan Python, yang bertujuan untuk menemukan solusi (kromosom) yang **semakin mendekati target data** melalui proses seleksi, crossover, dan mutasi.

### 📌 Tujuan

Mencari individu (kromosom) yang paling mirip dengan data target `[1, 2, 1]` menggunakan pendekatan algoritma genetika.

### 📊 Dataset

Terdiri dari 4 data awal:

| Data | F1 | F2 | F3 |          |
| ---- | -- | -- | -- | -------- |
| D1   | 1  | 2  | 1  | ← Target |
| D2   | 2  | 1  | 2  |          |
| D3   | 8  | 9  | 8  |          |
| D4   | 9  | 8  | 9  |          |

### ⚙️ Parameter GA

* **Population Size**: 4 individu per generasi
* **Crossover Rate**: 0.8
* **Mutation Rate**: 0.1
* **Elitism**: 1 individu terbaik disimpan tiap generasi
* **Stop Condition**: Algoritma berhenti jika solusi dengan fitness sempurna (1.0) ditemukan

### 🔄 Proses GA

1. Inisialisasi populasi
2. Evaluasi fitness
3. Seleksi orang tua
4. Crossover & mutasi
5. Elitism & pembentukan populasi baru
6. Ulangi hingga solusi terbaik ditemukan

### 🧠 Hasil

Output per generasi akan menampilkan:

* Nomor generasi
* Daftar individu dan fitness-nya
* Solusi terbaik jika ditemukan

### 📁 Struktur File

* `genetic_algorithm.py` – kode utama algoritma genetika


