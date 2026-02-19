# titanic-survival-prediction

**Titanic Survival Prediction: A Machine Learning Workflow**
📌 **Overview**

Proyek ini adalah implementasi model klasifikasi untuk memprediksi probabilitas keselamatan penumpang kapal Titanic. Menggunakan dataset legendaris dari Kaggle, proyek ini berfokus pada analisis fitur penumpang seperti usia, jenis kelamin, kelas kabin, dan tarif untuk menentukan faktor-faktor yang mempengaruhi tingkat kelangsungan hidup.

🛠️ **Tech Stack**

- Language: Python
- Libraries: Pandas, NumPy (Data Manipulation), Scikit-Learn (Machine Learning)
- Dataset: Titanic - Machine Learning from Disaster (Kaggle)

🚀 **Key Learning & Features**

- Data Preprocessing:
    - Penanganan nilai kosong (missing values) pada kolom kritis seperti Age dan Embarked.
    - Seleksi fitur untuk menghapus kolom yang tidak relevan secara statistik (seperti PassengerId, Name, Ticket, Cabin).

- Categorical Encoding: Menggunakan get_dummies untuk mengubah data kategorikal menjadi format numerik agar bisa diproses model.
- Modeling: Menggunakan algoritma Random Forest Classifier untuk memprediksi target biner (Survived).
- Submission Ready: Menghasilkan file my_submission.csv yang sudah disesuaikan dengan format standar kompetisi Kaggle.

📊 **Results**

Model mampu memproses data penumpang baru dan memberikan prediksi keselamatan yang kemudian diformat ke dalam file CSV untuk keperluan evaluasi kompetisi.
