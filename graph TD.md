graph TD
A[Mulai] --> B[Pengumpulan Data]
B --> C[Preprocessing Data]
C --> D[Implementasi LOF]
D --> E[Pengembangan RBS]
E --> F[Integrasi LOF & RBS]
F --> G[Evaluasi & Analisis]
G --> H[Selesai]

subgraph Pengumpulan Data
B[Pengumpulan Data] --> B1[Dataset Kaggle Anushonkar]
B[Pengumpulan Data] --> B2[Dataset Kaggle Aman Verma]
end

subgraph Preprocessing Data
C[Preprocessing Data] --> C1[Ubah Format ke CSV]
C[Preprocessing Data] --> C2[Data Cleaning]
C[Preprocessing Data] --> C3[Normalisasi Data]
end

subgraph Implementasi LOF
D[Implementasi LOF] --> D1[Buat Environment]
D[Implementasi LOF] --> D2[Latih Model LOF]
D[Implementasi LOF] --> D3[Uji Model LOF]
end

subgraph Pengembangan RBS
E[Pengembangan RBS] --> E1[Identifikasi Aturan]
E[Pengembangan RBS] --> E2[Implementasi Aturan]
end

subgraph Integrasi LOF & RBS
F[Integrasi LOF & RBS] --> F1[Prediksi Outlier dengan LOF]
F[Integrasi LOF & RBS] --> F2[Validasi Outlier dengan RBS]
end

subgraph Evaluasi & Analisis
G[Evaluasi & Analisis] --> G1[Analisis Hasil]
G[Evaluasi & Analisis] --> G2[Evaluasi Keakuratan]
G[Evaluasi & Analisis] --> G3[Kesimpulan & Rekomendasi]
end
