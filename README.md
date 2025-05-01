Student Performance Analysis
🔎 Menganalisis faktor-faktor yang memengaruhi nilai ujian siswa menggunakan Python (Matplotlib, Seaborn, Scikit-Learn)
📌 Deskripsi Singkat
Proyek ini bertujuan untuk memahami faktor-faktor yang memengaruhi performa akademik siswa dengan menggunakan Machine Learning dan Data Visualization. Dataset student_habits_performance.csv berisi informasi tentang kebiasaan belajar siswa, kualitas hidup, dan nilai ujian mereka (Exam Score).
Dalam proyek ini, kita akan: ✔ Menganalisis hubungan antara kebiasaan belajar dan performa ujian
✔ Memvisualisasikan pola dan distribusi nilai siswa
✔ Membangun model Machine Learning untuk memprediksi nilai ujian berdasarkan berbagai faktor

🛠 Teknologi yang Digunakan
- Python
- Pandas → Manipulasi data
- Matplotlib & Seaborn → Visualisasi data
- Scikit-Learn → Machine Learning (Linear Regression)


🎯 Analisis yang Dilakukan
1️⃣ Visualisasi Data
✔ Scatter plot & heatmap untuk melihat korelasi antara study hours, attendance, dan exam score
✔ Boxplot untuk memahami pengaruh diet, exercise, dan internet quality terhadap nilai ujian
✔ Histogram untuk melihat distribusi Exam Score
✔ Bar chart untuk membandingkan nilai ujian berdasarkan Gender
2️⃣ Prediksi Nilai Ujian dengan Machine Learning
✔ Menggunakan Linear Regression untuk memprediksi Exam Score berdasarkan faktor-faktor yang tersedia
✔ Evaluasi model dengan Mean Squared Error (MSE) dan R² Score
✔ Uji model dengan data baru untuk melihat hasil prediksi

🚀 Cara Menggunakan
- Clone repository inigit clone https://github.com/USERNAME/student-performance-analysis.git
cd student-performance-analysis

- Install dependensipip install pandas matplotlib seaborn scikit-learn

- Jalankan Jupyter Notebookjupyter notebook

- Buka file student_performance_analysis.ipynb dan jalankan sel satu per satu- Pastikan dataset student_habits_performance.csv tersedia dalam direktori



📄 File dalam Repository
📁 student_performance_analysis.ipynb → Jupyter Notebook utama untuk eksplorasi dan prediksi
📁 student_habits_performance.csv → Dataset siswa yang digunakan dalam analisis
📁 README.md → Dokumentasi proyek

🤝 Kontribusi
Jika Anda ingin berkontribusi:
- Fork repository ini
- Buat perubahan pada branch baru
- Submit pull request dengan deskripsi perubahan Anda


📌 Catatan
🔹 Pastikan dataset tersedia di direktori sebelum menjalankan notebook
🔹 Jika ingin meningkatkan akurasi model, coba Random Forest Regression atau Gradient Boosting
🔹 Eksplor lebih banyak fitur untuk melihat faktor yang paling berpengaruh terhadap performa siswa
