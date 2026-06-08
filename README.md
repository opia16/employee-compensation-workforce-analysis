# Employee Compensation & Workforce Analysis

Analisis distribusi tenaga kerja dan struktur kompensasi karyawan menggunakan Google Sheets, Data Cleaning, Data Wrangling, dan Pivot Table Analysis.

---

## Latar Belakang

Data karyawan menyimpan berbagai informasi penting terkait departemen, wilayah kerja, gaji, serta status kompensasi. Namun data mentah sering kali memiliki inkonsistensi format, missing value, dan struktur yang belum siap digunakan untuk analisis.

Pada proyek ini dilakukan proses data preparation, data cleaning, data integration, serta analisis menggunakan Pivot Table untuk menghasilkan insight terkait distribusi tenaga kerja dan kompensasi perusahaan.

---

## Tujuan Analisis

- Menganalisis distribusi kompensasi karyawan berdasarkan departemen
- Menganalisis distribusi kompensasi berdasarkan wilayah kerja
- Membandingkan rata-rata gaji antar departemen
- Membandingkan rata-rata gaji antar region
- Menganalisis tren perekrutan karyawan
- Mengetahui distribusi tenaga kerja perusahaan

---

## Tools

- Google Sheets
- Pivot Table
- Spreadsheet Functions
- Data Cleaning

---

## Data Preparation

Tahapan pengolahan data meliputi:

### 1. Data Cleaning

- Standardisasi format tanggal
- Perbaikan format Join Date
- Penanganan missing value
- Validasi tipe data

### 2. Missing Value Handling

**Age** (Menggunakan median imputation)

**Salary** (Menggunakan mean imputation)

### 3. Data Wrangling

memisahkan kolom menggunakan fungsi SPLIT().

| Department-Region                    | Department                | Region     |
| -------------------------- | ----------------------- | ------------------------- |
| DevOps-California | DevOps | California |
| Finance-Texas | Finance | Texas |
|Admin-Nevada	| Admin |	Nevada |

### 4. Data Integration

Menggabungkan dataset utama dengan tabel referensi salary menggunakan: VLOOKUP()

---

## Analisis yang Dilakukan
### Compensation Distribution by Department

Analisis distribusi:
- Underpaid
- Standard
- Overpaid

berdasarkan departemen.

### Compensation Distribution by Region

Analisis distribusi kompensasi berdasarkan wilayah kerja.

### Average Salary by Department

Perbandingan rata-rata gaji antar departemen.

### Average Salary by Region

Perbandingan rata-rata gaji antar wilayah.

### Employee Distribution by Join Year

Analisis tren perekrutan karyawan dari tahun ke tahun.

### Employee Distribution by Region

Analisis persebaran tenaga kerja perusahaan.

---

## Key Insights
### 1. DevOps Memiliki Jumlah Underpaid Tertinggi

Departemen DevOps menunjukkan jumlah karyawan underpaid tertinggi dibanding departemen lain sehingga perlu dilakukan evaluasi struktur kompensasi.

### 2. Sales Memiliki Rata-rata Gaji Tertinggi

Departemen Sales memiliki rata-rata salary tertinggi yang kemungkinan dipengaruhi oleh insentif dan komisi.

### 3. California Memiliki Salary Tertinggi

Region California menunjukkan rata-rata salary tertinggi dibanding region lainnya.

### 4. Perekrutan Meningkat pada Tahun 2023

Jumlah karyawan yang bergabung meningkat signifikan pada tahun 2023 yang mengindikasikan adanya ekspansi bisnis.

### 5. Distribusi Karyawan Relatif Merata

Jumlah tenaga kerja tersebar cukup merata di seluruh region sehingga menunjukkan operasional perusahaan yang seimbang.

---

## Rekomendasi Bisnis
* Evaluasi struktur kompensasi pada departemen dengan jumlah underpaid tinggi.
* Lakukan benchmarking salary antar region.
* Pertahankan keseimbangan distribusi tenaga kerja.
* Analisis faktor yang mendorong peningkatan perekrutan tahun 2023.
* Gunakan dashboard monitoring kompensasi secara berkala.

---

## Author
Shofia Nabila

Studi Independen Data Analyst | Vinix7

Sistem Infromasi Kelautan | Univeristas Pendidikan Indonesia
