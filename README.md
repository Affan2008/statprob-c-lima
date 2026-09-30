# Air Quality & Noise Map of Major Cities (2019–2026)
## Statistika dan Probabilitas (C) - Project EDA

Kelompok 5:
- Aillen Rihhadatu Nasywa (5027261030)
- Affan Haidar Maulana (5027261054)
- Muhammad Nadhif Fernanda (5027261139)

Sumber Data: [Air Quality & Noise Map of Major Cities(2019–2026)](https://www.kaggle.com/datasets/asifxzaman/air-quality-and-noise-map-of-major-cities20192026)
Lisensi Data: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Topik Project: Smart City


### Temuan Utama
- New York Punya Data Paling Banyak: Dari sekian banyak kota yang dicatat, kota New York muncul paling sering di dalam tabel.
- Tingkat Kebisingan Selalu di Atas 50 dB: Di semua kota, tidak ada area yang benar-benar tenang karena tingkat kebisingannya selalu di atas batas normal (50 dB).
- Gas CO dan NO2 Selalu Muncul Bersamaan: Saat kadar Nitrogen Dioksida (NO2) tinggi, kadar Karbon Monoksida (CO) di tabel juga hampir selalu ikut tinggi.

### Cara Menjalankan Notebook
Kami mengikuti langkah-langkah pada halaman project di Classroom untuk menyiapkan environment untuk menjalankan notebook:

- Clone repositori ini atau download sebagai ZIP dan extract ke folder yang mudah dicapai dengan terminal/CMD
- Install Miniconda atau Anaconnda
- Buka terminal/CMD dan buat environment baru untuk notebook ini
```
conda create -n airQualityC5 python=3.11 -y
conda activate airQualityC5
```
- Install paket-paket yang dibutuhkan
```
conda install -c conda-forge jupyter pandas matplotlib seaborn -y
```
- Masuk ke dalam folder yang berisi notebook ini dan jalankan Jupyter Notebook
```
cd lokasi/folder/notebook
jupyter notebook
```
