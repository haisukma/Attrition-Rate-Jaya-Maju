# JayaJayaMaju-Submission
 
# Submission Pertama: Menyelesaikan Permasalahan Human Resources

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

### Permasalahan Bisnis

1. **Tingginya Attrition Rate:**
- Identifikasi faktor-faktor yang mempengaruhi tingginya attrition rate.
- Analisis data untuk menemukan pola dan tren yang berkaitan dengan karyawan yang keluar.

2. **Keterbatasan dalam Monitoring:**
- Manajer departemen HR memerlukan alat untuk memantau berbagai faktor yang mempengaruhi attrition rate.
- Pembuatan dashboard bisnis untuk membantu dalam pengambilan keputusan.

### Solusi
Pembuatan dashboard untuk mengidentifikasi faktor-faktor yang memengaruhi attrition rate dan memudahkan HR dalam memonitoring pegawai

### Cakupan Proyek

1. Data Understanding hingga Preparation Data karyawan.
2. Mengidentifikasi variabel-variabel yang berhubungan dengan attrition.
3. Membangun model machine learning untuk memprediksi kemungkinan karyawan akan keluar menggunakan model Random Forest Classifier.
4. Membuat dashboard bisnis yang memberikan wawasan visual mengenai faktor-faktor yang mempengaruhi attrition dan membantu manajemen dalam mengambil keputusan.
5. Merekomendasikan Action Items berdasarkan hasil analisis.

### Persiapan

Sumber data: [Employee Data](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee)

Setup environment:
Apabila menginstal Python melalui Anaconda ataupun Miniconda, Anda dapat menggunakan conda sebagai package manager dan environment management system

1. Buka Terminal ataupun PowerShell

2. Jalankan perintah berikut untuk membuat virtual environment baru dengan Python 3.9:

```
conda create --name main-jjm python=3.9
conda activate main-jjm
pip install -r requirements.txt
```
3. Untuk Melakukan prediksi, buka file python 'predictionjjm.py'

4. Ganti variable 'path' menjadi data yang ingin anda prediksi

5. Tekan tombol run dan hasil prediksi akan keluar

## Business Dashboard

Business dashboard yang dibuat menggunakan [Looker Studio](https://lookerstudio.google.com/reporting/24d01c8b-265c-45a1-be19-af7f579c4ce6) akan mencakup visualisasi berikut:

1. **Overview Dashboard:** Menampilkan metrik-metrik utama seperti jumlah total karyawan, tingkat attrition, distribusi karyawan berdasarkan departemen, dan lainnya.

2. **Attrition Analysis Dashboard:** Menampilkan analisis mendalam mengenai faktor-faktor yang mempengaruhi attrition seperti OverTime Work, Job Level, Jumlah tahun training, dan lainnya.

## Conclusion

Dari proyek ini, kita mendapatkan beberapa wawasan penting mengenai faktor-faktor yang mempengaruhi tingkat attrition di Jaya Jaya Maju.
Model machine learning Random Forest Classifier yang telah dibangun dapat memprediksi dengan baik kemungkinan karyawan akan keluar berdasarkan data historis.
Berdsarkan business dashboard yang telah dibuat, didapatkan kesimpulan bahwa Attrition rate paling banyak berada pada Departemen HR dengan job role Laboratory Technician & Research Scientist dan pada Departemen Sales dengan job role Sales Excecutive & Sales Representative. Demografis pegawai yang melakukan attrition mayoritas merupakan pegawai berjenis kelamin laki-laki, berstatus single, berumur 22-37, dan memiliki tingkat pendidikan bachelor atau S1.
Business dashboard ini dapat membantu manajemen dalam memonitor dan mengambil tindakan yang diperlukan untuk mengurangi tingkat attrition.

### Rekomendasi Action Items 

1. **Meningkatkan kepuasan kerja karyawan:** Mengidentifikasi dan memperbaiki faktor-faktor yang menyebabkan ketidakpuasan kerja.

2. **Pelatihan dan pengembangan:** Menyediakan lebih banyak kesempatan pelatihan dan pengembangan bagi karyawan.
3. **Evaluasi kompensasi dan manfaat:** Melakukan evaluasi terhadap struktur kompensasi dan manfaat yang diberikan kepada karyawan untuk memastikan mereka merasa dihargai dan termotivasi.

Dengan melaksanakan rekomendasi ini, diharapkan Jaya Jaya Maju dapat mengurangi tingkat attrition dan meningkatkan kepuasan serta produktivitas karyawan.
