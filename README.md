# UAS-DAE

C14220041-Andreas Harry

C14220092-Amos Gihon

Analisis Nilai Terbaik (Value-for-Money) Universitas

I. Tujuan Analisis
Tujuan utama dari pengolahan data ini adalah untuk mengidentifikasi universitas yang menawarkan Nilai Terbaik (Value-for-Money) berdasarkan dua kriteria utama:

Biaya Kuliah (Tuition Fee): Diklasifikasikan sebagai High (di atas $10.000) atau Low (di bawah $10.000).
Tingkat Kelulusan (Graduation Rate): Tingkat kelulusan yang tinggi di setiap kelas biaya menunjukkan kualitas dan keberhasilan institusi.
Analisis ini bertujuan untuk menemukan universitas dengan Graduation Rate tertinggi di rentang biaya termurah dan termahal dari masing-masing kategori (High dan Low).

II. Metodologi Pengolahan Data (KNIME Workflow)
Pengolahan data dilakukan menggunakan platform KNIME Analytics, melalui langkah-langkah sebagai berikut:
1. Pre-processing dan Klasifikasi Biaya
2. Node Utama: Rule Engine
3. Aksi: Kolom biaya kuliah (in-state tuition dan out-of-state tuition) diklasifikasikan ke dalam dua kategori baru:
   
   HIGH: Jika biaya kuliah >= $10.000.
   
   LOW: Jika biaya kuliah <= $10.000.
5. Tujuan: Membuat kriteria kategorisasi biaya yang jelas sesuai definisi "High" dan "Low" untuk memfasilitasi pencarian value-for-money.

<img width="801" height="197" alt="image" src="https://github.com/user-attachments/assets/14d2c40a-58de-49a0-8b7d-99d33e7609a9" />

(harga kiri untuk in-state-tuition)(harga kanan untuk out-of state tuition)

high:   

1.Siena Collage 10.800 10.800 (range harga high termurah dengan graduation rate tertinggi)

2.Amherst College 19.760 19.760 (range harga high termahal dengan graduation rate tertinggi)
<img width="1846" height="343" alt="Screenshot 2025-12-10 204623" src="https://github.com/user-attachments/assets/1dd10e27-1e76-4c42-8e58-95dbae04061f" />
<img width="1847" height="644" alt="Screenshot 2025-12-10 204326" src="https://github.com/user-attachments/assets/8a8d415d-6ff3-4f2a-87cf-57f52c45fbd5" />



low:

1.Missouri Southern State Collage 1920 3840 (range harga low termurah dengan graduation rate tertinggi)

2.Cazenovia Collage 9384 9384 (range harga low termahal dengan graduation rate tertinggi)
<img width="1846" height="340" alt="Screenshot 2025-12-10 204616" src="https://github.com/user-attachments/assets/a1953e16-c570-492c-ba13-a1644d5ecec4" />
<img width="1845" height="632" alt="Screenshot 2025-12-10 204341" src="https://github.com/user-attachments/assets/63f76180-277c-429b-8a04-c56ef1f98d0f" />

ini merupakan bar chart dari tiap state beserta harga rata-rata in-state tuition dan out-of-state tuition
<img width="1845" height="681" alt="Screenshot 2025-12-10 204310" src="https://github.com/user-attachments/assets/75b6d40a-34ad-4e55-9602-8a15444938cb" />

ini merupakan pie chart dari pengelompokan public vs private university
<img width="1845" height="359" alt="image" src="https://github.com/user-attachments/assets/72c2fd82-805c-4974-b2ca-904a7e809b89" />







