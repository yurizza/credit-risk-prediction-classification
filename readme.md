# Credit Risk Prediction Classification ("GOOD" or "BAD")

"""
Problem Statement : 

Lending company di Indonesia ingin mengevaluasi risiko kredit yang terkait dengan para calon peminjam menggunakan dataset yang disediakan oleh perusahaan, yang terdiri dari data pinjaman yang disetujui dan ditolak. 

Dengan adanya prediksi risiko kredit maka perusahaan peminjaman dapat mengoptimalkan keputusan pemberian pinjaman, mengurangi risiko kerugian, meningkatkan efisiensi operasional, dan memperkuat posisi mereka di pasar, sehingga menciptakan dampak positif secara finansial dan operasional."""

'''
Objective :

1. Membangun model prediktif menggunakan dataset yang diberikan yang dapat mengklasifikasikan calon peminjam menjadi dua kategori: disetujui (risiko rendah) dan ditolak (risiko tinggi).

2. Mengidentifikasi faktor-faktor atau fitur-fitur utama dalam dataset yang secara signifikan mempengaruhi penilaian risiko kredit.

3. Mengevaluasi kinerja model penilaian risiko kredit berdasarkan metrik evaluasi yang sesuai, seperti akurasi, presisi, recall, dan skor F1.
'''

## Steps :

1. Business Analysis
2. Analytic Approach
3. Data Requirements & Collection
4. Data Preparation
    - Handling Missing Value
    - Statistics Descriptive & Inferential Statistics
5. Model Machine Learning
    - Scalling (Standard Scaller) & Encoding (One Hot Encoder)
    - Undersampling (Random) & Oversampling (SMOTE)
    - Finding Best Algorithm (Linear Regression, Decision Tree, Random Forest, Ada Boost and Gradient Boosting)
    - Select n Best Feature for Best Algorithm.
    - Metrics Evaluation
    - Feature Importances
6. Conclusion
    - 1. Algoritma terbaik untuk prediksi risiko kredit adalah Random Forest, dengan akurasi 0.85.
    - 2. Feature yang digunakan untuk membangun model adalah 40 dari 54.
    - 3. Dari nilai presisi, recall dan f1-score bahwa model mampu dengan baik memprediksi "good" credit risk dari pada "bad" credit risk.
