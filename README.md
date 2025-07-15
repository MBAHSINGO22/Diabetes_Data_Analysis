# 📝 Diabetes_Data_Analysis

**Analisis Data Prediksi Diabetes dengan Python**  
Eksplorasi dataset kesehatan menggunakan Pandas untuk analisis data awal

---

## 📖 Deskripsi Proyek

**Diabetes_Data_Analysis** adalah proyek pembelajaran Python yang dilakukan untuk melakukan analisis data awal (exploratory data analysis) pada *Diabetes Prediction Dataset*. Proyek ini berfokus pada:

- 📊 Pemuatan dan penampilan data menggunakan Pandas  
- 🔍 Inspeksi informasi dataset (tipe data, jumlah entri, nilai kosong)  
- 🧹 missing values

Proyek ini terdiri dari sebuah Jupyter Notebook (`coba.ipynb`) untuk analisis interaktif dan sebuah skrip Python (`Latihan1.py`) untuk menampilkan dataset secara langsung. Cocok untuk pemula yang ingin mempelajari analisis data menggunakan Python. 🟢

---

## 🧠 Teknologi

- Python 3.x  
- Pandas  
- Jupyter Notebook

---

## 📂 Struktur File

```
Diabetes_Data_Analysis/
├── coba.ipynb                    # 📊 Notebook untuk analisis data diabetes
├── Latihan1.py                  # 📝 Skrip untuk menampilkan seluruh dataset
├── diabetes_prediction_dataset.csv  # 📈 Dataset prediksi diabetes
```

---

## ▶️ Menjalankan Program

### 1. Kloning Repositori:

```bash
git clone https://github.com/MBAHSINGO22/Diabetes_Data_Analysis.git
cd Diabetes_Data_Analysis
```

### 2. Pastikan Python Terinstal:

Periksa versi Python:

```bash
python --version
```

Jika belum terinstal, unduh dari [python.org](https://www.python.org/).

### 3. Instal Dependensi:

Instal pustaka yang diperlukan dari `requirements.txt`:

```bash
pip install -r requirements.txt
```

**Isi requirements.txt:**
```
pandas
jupyter
```

### 4. Jalankan Jupyter Notebook:

```bash
jupyter notebook
```

Buka `coba.ipynb` di browser dan jalankan sel-sel untuk melakukan analisis.

### 5. Jalankan Skrip Python:

Pastikan file `diabetes_prediction_dataset.csv` berada di direktori yang sama dengan `Latihan1.py`, lalu jalankan:

```bash
python Latihan1.py
```

📌 *Catatan:* Perbarui jalur file di `Latihan1.py` jika dataset berada di lokasi lain (misalnya, ganti `C:\Users\hp\PEM.ANALISA\PERTEMUAN 6\diabetes_prediction_dataset.csv` dengan jalur yang sesuai).

---

## 🟢 Catatan

- Tidak ada dependensi eksternal selain Pandas dan Jupyter.  
- Pastikan file `diabetes_prediction_dataset.csv` tersedia untuk kedua skrip.  
- `coba.ipynb` menampilkan 10 data pertama dan terakhir, informasi dataset, dan pemeriksaan missing values.  
- `Latihan1.py` menampilkan seluruh dataset dalam format teks.

---

## 📈 Contoh Output

**coba.ipynb**
```
10 Data Pertama:
  gender   age  hypertension  heart_disease smoking_history    bmi  HbA1c_level  blood_glucose_level  diabetes
0  Female  80.0             0              1           never  25.19          6.6                  140         0
1  Female  54.0             0              0         No Info  27.32          6.6                   80         0
...

10 Data Terakhir:
      gender   age  hypertension  heart_disease smoking_history    bmi  HbA1c_level  blood_glucose_level  diabetes
99990   Male  39.0             0              0         No Info  27.32          6.1                  100         0
99991   Male  22.0             0              0         current  29.65          6.0                   80         0
...

Data Informasi:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 100000 entries, 0 to 99999
Data columns (total 9 columns):
 #   Column               Non-Null Count   Dtype  
---  ------               --------------   -----  
 0   gender               100000 non-null  object 
 1   age                  100000 non-null  float64
...

Kesalahan Data:
gender                 0
age                    0
...
```

**Latihan1.py**
```
gender,age,hypertension,heart_disease,smoking_history,bmi,HbA1c_level,blood_glucose_level,diabetes
Female,80.0,0,1,never,25.19,6.6,140,0
Female,54.0,0,0,No Info,27.32,6.6,80,0
...
```

---

## 👨‍💻 Pengembang

**MBAHSINGO22**  
🔗 [GitHub](https://github.com/MBAHSINGO22)
