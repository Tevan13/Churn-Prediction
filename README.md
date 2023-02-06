# Churn-Prediction (Team Slovakia)
Churn prediction dibuat sebagai final project program MSIB Batch 3 dari Yayasan Ahmad Zaky Foundation - Startup Campus yang berlangsung selama 3 bulan.
Data yang digunakan adalah [Mockup Dataset](https://bit.ly/datasetFPDS)

### Problem Statement
Customer Churn adalah proses untuk mengukur tingkat pelanggan untuk melihat customer berhenti membeli produk ataupun customer yang masih beli produk

### Objective
Memprediksi customerChurn dalam 1 bulankedepan denganperiode 6 bulan sebelumnya

### Data Period
*Calibration Period :
- Desember 2021 - Mei 2022 = Juni

*Holdout Period :
- Januari 2022 - Juni 2022 = Juli

### Exploratory Data Analysis (singkat)
#### Presentase device yang digunakan oleh customer dalam melakukan transaksi 
![image](https://user-images.githubusercontent.com/82057016/216912732-329c244f-6d94-4b97-a6f9-59617841d2d0.png)
#### Presentase Customer Churn & Non-Churn 
![image](https://user-images.githubusercontent.com/82057016/216912528-fc6f7fc6-4653-4b80-bcbf-ee95490c7db7.png)
#### Metode pembayaran sukses dan berhasil 
![image](https://user-images.githubusercontent.com/82057016/216913117-b50e1520-e891-40bf-a706-ef7ac14ed8e6.png)

### Baseline Model
Pada pembuatan model disini kami menggunakan 3 Algoritma yaitu **Logistic Regression** dengan akurasi sebesar 76% , **Decision Tree** dengan akurasi sebesar 94% , dan **Random Forest** dengan akurasi sebesar 88%
#### Berikut hasil modelling dengan digambarkan ROC dan Confusion Matrix
![image](https://user-images.githubusercontent.com/82057016/216913986-786f704e-3ee0-4167-94f5-558cce201f1c.png)


### Visualisasi Data
#### Berikut visualisasi data churn prediction menggunakan [Google Data Studio](https://lookerstudio.google.com/u/0/reporting/bc87dea6-0f03-429d-9408-1e1ee40099ee/page/KdO8C)

![image](https://user-images.githubusercontent.com/82057016/216866989-3deea2a8-25a9-4d1d-83ba-5263f922cdf3.png)
