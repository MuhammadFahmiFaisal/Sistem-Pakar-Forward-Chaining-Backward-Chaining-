# Sistem Pakar: Forward Chaining & Backward Chaining

## 📌 Deskripsi
Repository ini berisi implementasi sistem pakar dengan menggunakan algoritma **Forward Chaining** dan **Backward Chaining** dalam **Python**. Sistem pakar ini dapat digunakan untuk memberikan solusi atau rekomendasi berdasarkan pengetahuan yang diberikan dalam bentuk aturan-aturan tertentu. Forward Chaining dan Backward Chaining adalah dua metode populer yang digunakan dalam sistem pakar untuk menarik kesimpulan.

## 📖 Penjelasan Algoritma

### 1️⃣ Forward Chaining
Forward Chaining adalah metode inferensi yang dimulai dari fakta-fakta yang ada (data awal) dan menggunakan aturan-aturan (production rules) untuk mengarah ke kesimpulan. Proses dimulai dengan fakta yang diketahui dan terus berkembang dengan menerapkan aturan-aturan yang relevan untuk memperoleh informasi baru hingga mencapai tujuan atau kesimpulan. Metode ini disebut juga sebagai **data-driven reasoning** karena dimulai dari fakta dan mencari solusi.

#### Langkah-langkah Forward Chaining:
1. Mulai dengan fakta yang diketahui.
2. Terapkan aturan yang relevan untuk menambah informasi baru.
3. Ulangi langkah 2 hingga tujuan tercapai atau tidak ada aturan yang dapat diterapkan lagi.

### 2️⃣ Backward Chaining
Backward Chaining adalah metode inferensi yang dimulai dengan tujuan atau hipotesis dan bekerja mundur untuk mencari bukti atau fakta yang mendukung hipotesis tersebut. Dalam metode ini, sistem pakar memulai dengan pertanyaan atau kesimpulan yang ingin dicapai, lalu mencari aturan yang dapat membuktikan atau membenarkan tujuan tersebut. Metode ini disebut juga sebagai **goal-driven reasoning** karena dimulai dari tujuan dan mencari fakta yang relevan.

#### Langkah-langkah Backward Chaining:
1. Tentukan tujuan atau hipotesis yang ingin diuji.
2. Cek apakah tujuan dapat dibuktikan dengan aturan yang ada.
3. Jika tujuan tidak langsung terbukti, cek apakah sub-tujuan dapat membuktikan tujuan utama.
4. Ulangi langkah 3 sampai fakta yang relevan ditemukan atau tidak ada lebih banyak aturan yang dapat diterapkan.
