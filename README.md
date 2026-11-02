# 📊 Dashboard Analytics Penjualan & Pasar Herbisida (Power BI)

Dashboard interaktif menggunakan **Microsoft Power BI** untuk menganalisis penjualan dan memetakan pasar produk herbisida di marketplace. Dashboard ini menyajikan informasi mengenai produk dengan omzet tertinggi, persebaran lokasi toko, performa penjualan setiap toko, serta indikator utama seperti omzet, unit terjual, rating, dan wishlist.

## 📸 Preview Dashboard

<img width="1908" height="1068" alt="Screenshot 2026-11-02 122957" src="https://github.com/user-attachments/assets/9531989c-f801-4a5a-9257-d8168683c1cd" />


## 📌 Latar Belakang

Data penjualan produk herbisida di marketplace tersebar di berbagai toko, produk, dan lokasi. Kondisi ini menyulitkan proses identifikasi produk unggulan, wilayah potensial, serta toko dengan performa penjualan terbaik.

Untuk mengatasi hal tersebut, proyek ini mengembangkan dashboard interaktif yang mengintegrasikan berbagai informasi penjualan ke dalam satu tampilan. Dashboard dilengkapi fitur filter sehingga pengguna dapat mengeksplorasi data berdasarkan periode listing, lokasi toko, jenis toko, dan rentang harga.

## 🎯 Tujuan Analisis

1. Mengidentifikasi produk herbisida dengan estimasi omzet tertinggi.
2. Memetakan persebaran toko dan mengidentifikasi lokasi dengan omzet terbesar.
3. Membandingkan performa antar toko berdasarkan omzet, unit terjual, rating, dan stok.
4. Menyajikan ringkasan Key Performance Indicators (KPI) untuk mendukung analisis dan pengambilan keputusan bisnis.

## 📂 Dataset

Dataset yang digunakan merupakan data listing produk herbisida dari marketplace.

| Informasi | Keterangan |
|---|---|
| Nama File | `project_herbisida.xls` |
| Lokasi File | `data/project_herbisida.xls` |
| Jumlah Listing Produk | 60 listing |
| Jumlah Toko | 40 toko |
| Jumlah Lokasi | 32 lokasi |
| Periode Listing | 7 Mei 2017 – 18 Januari 2024 |

**Distribusi Jenis Toko:**

| Jenis Toko | Jumlah Listing |
|---|---:|
| Star+ | 33 |
| Star | 14 |
| Reguler | 13 |
| **Total** | **60** |

### 📖 Kamus Data

| Kolom | Keterangan |
|---|---|
| Produk | Nama listing produk |
| Nama Toko | Nama toko penjual |
| Lokasi Toko | Kota/kabupaten lokasi toko |
| Jenis Toko | Kategori toko (Star+, Star, Reguler) |
| Ditambahkan | Tanggal produk pertama kali di-listing |
| Harga | Harga produk (Rp) |
| Stok | Jumlah stok tersedia |
| Est. Omset/bln | Estimasi omzet per bulan |
| Est. Omset 30 hari | Estimasi omzet 30 hari terakhir |
| Terjual/bln | Estimasi unit terjual per bulan |
| Terjual 30 hari | Unit terjual dalam 30 hari terakhir |
| Trend 30 hari | Persentase tren penjualan 30 hari |
| Market Share | Pangsa pasar produk |
| Rating | Rata-rata rating produk |
| Ulasan | Jumlah ulasan produk |
| Wishlist | Jumlah wishlist |
| Nilai Jual Stok | Stok × harga (nilai jual seluruh stok) |
| Total Terjual | Total unit terjual sejak listing |
| Est. Total Omset | Estimasi total omzet sejak listing |

## 📈 Fitur dan Visualisasi Dashboard

### 1. Filter Interaktif (Slicer)

Dashboard menyediakan beberapa filter untuk mempermudah eksplorasi data:

- **Tanggal:** Memfilter berdasarkan tanggal listing produk.
- **Lokasi Toko:** Memilih kota/kabupaten lokasi toko.
- **Jenis Toko:** Memfilter kategori toko (Star+, Star, Reguler).
- **Harga:** Menentukan rentang harga produk.

### 2. Key Performance Indicators (KPI)

Dashboard menyajikan lima indikator utama untuk memberikan gambaran umum kondisi pasar herbisida.

| KPI | Nilai |
|---|---:|
| Total Omzet (30 Hari) | Rp300,8 juta |
| Nilai Jual Stok | Rp289 miliar |
| Total Unit Terjual (30 Hari) | 9.072 unit |
| Rata-rata Rating | 4,77 |
| Total Wishlist | 7.355 |

### 3. Visualisasi Data

| Visualisasi | Deskripsi |
|---|---|
| Top 10 Produk berdasarkan Omzet (30 Hari) | Menampilkan sepuluh produk dengan estimasi omzet tertinggi. |
| Peta Lokasi Toko | Memvisualisasikan persebaran toko berdasarkan lokasi geografis. |
| Top 10 Lokasi Toko berdasarkan Omzet per Bulan | Mengidentifikasi lokasi dengan estimasi omzet bulanan tertinggi. |
| Omzet berdasarkan Bulan Listing Produk | Menampilkan grafik garis estimasi omzet berdasarkan bulan produk ditambahkan. |
| Matriks Performa Toko | Membandingkan omzet, unit terjual, rating, dan stok setiap toko. |

## 💡 Insight Utama

Berdasarkan hasil eksplorasi dan visualisasi data, diperoleh beberapa temuan berikut:

1. **Gambaran Penjualan:** Total estimasi omzet selama 30 hari mencapai Rp300,8 juta dengan total 9.072 unit terjual dan rata-rata rating produk sebesar 4,77.

2. **Konsentrasi Omzet Produk:** Sepuluh produk teratas menyumbang sekitar 73% dari total omzet. Produk dengan kontribusi terbesar antara lain Obat Rumput Winsa 1 Liter dan Roundup 486 SL 1 Liter.

3. **Dominasi Jenis Toko:** Toko berjenis Star+ memiliki kontribusi sekitar 54% dari total omzet, yaitu sebesar Rp162 juta dari total Rp300,8 juta.

4. **Lokasi dengan Omzet Tertinggi:** Kabupaten Jember, Kota Jakarta Barat, dan Kota Surabaya merupakan tiga lokasi dengan estimasi omzet bulanan tertinggi.

5. **Performa Toko:** Elang Mandiri Tani menjadi toko dengan estimasi omzet 30 hari terbesar, yaitu sekitar Rp53,6 juta.

## ⚠️ Catatan dan Keterbatasan Analisis

Beberapa hal perlu diperhatikan dalam menginterpretasikan hasil analisis:

- Angka omzet dan unit terjual merupakan estimasi berdasarkan data marketplace, bukan data transaksi internal toko.
- Dataset tidak memiliki informasi tanggal transaksi penjualan. Oleh karena itu, grafik omzet per bulan dikelompokkan berdasarkan bulan produk pertama kali di-listing (`Ditambahkan`), bukan berdasarkan tren penjualan musiman.
- Beberapa produk memiliki lebih dari satu listing dengan nama yang sama, misalnya Obat Rumput Winsa. Visualisasi Top 10 Produk menggabungkan listing dengan nama produk yang sama sehingga nilainya dapat lebih besar dibandingkan nilai pada satu baris data.
- Jumlah sampel relatif terbatas, yaitu 60 listing produk. Oleh karena itu, hasil analisis merupakan gambaran awal dan belum tentu merepresentasikan keseluruhan pasar herbisida.

## 🛠️ Tools dan Teknologi

- **Microsoft Power BI:** Pengembangan dashboard interaktif dan visualisasi data.
- **Microsoft Excel:** Pengelolaan dan pemeriksaan dataset.
- **Data Cleansing:** Persiapan dan pembersihan data sebelum visualisasi.
- **Data Visualization:** Penyajian informasi melalui grafik, peta, matriks, dan KPI.
- **Dashboard Design:** Perancangan tampilan dashboard untuk mendukung eksplorasi data.

## 📁 Struktur Repository

```text
Dashboard-Analytics-Herbisida/
│
├── data/
│   └── project_herbisida.xls
│
├── powerbi/
│   └── dashboard_herbisida.pbix
│
└── README.md
```
