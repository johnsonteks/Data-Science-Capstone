# SpaceX Falcon 9 First Stage Landing Prediction 🚀

## Deskripsi Singkat
Proyek *Capstone Data Science* ini bertujuan untuk membangun model klasifikasi *machine learning* guna memprediksi keberhasilan pendaratan roket Falcon 9 tahap pertama (*first stage*) dari SpaceX[cite: 2]. Prediksi keberhasilan pendaratan roket ini sangat penting untuk membantu memperkirakan biaya misi peluncuran ruang angkasa[cite: 2]. 

## Alur Kerja Data Science
Proyek ini mencakup siklus *data science* secara menyeluruh (*end-to-end*):
1. **Data Collection:** Mengumpulkan data historis penerbangan SpaceX melalui ekstraksi REST API dan *web scraping* tabel Wikipedia menggunakan BeautifulSoup[cite: 2].
2. **Data Wrangling:** Membersihkan dan menyiapkan data menggunakan Pandas DataFrame[cite: 2].
3. **Exploratory Data Analysis (EDA):** Menganalisis tren dan pola keberhasilan pendaratan menggunakan kueri SQL dan visualisasi data[cite: 2].
4. **Interactive Visual Analytics:** Membangun peta geospasial interaktif lokasi peluncuran dengan Folium serta dasbor interaktif menggunakan Plotly Dash[cite: 2].
5. **Predictive Analysis:** Melatih model klasifikasi (Logistic Regression, SVM, Decision Tree, KNN) di mana model terbaik berhasil mencapai tingkat akurasi prediksi sebesar 83,3%[cite: 2].

## Struktur Repositori
Proyek ini dikerjakan secara berurutan melalui serangkaian *Jupyter Notebook*:
* `1_Data_Collection_API.ipynb` & `2_Data_Collection_Scraping.ipynb` - Proses akuisisi data.
* `3_Data_Wrangling.ipynb` - Pembersihan data.
* `4_EDA_Visual_SQL.ipynb` & `5_EDA_Visual_Lab.ipynb` - Eksplorasi data dengan SQL dan plot visual.
* `6_Folium.ipynb` & `7_Plotly_Dash.ipynb` - Pembuatan analitik visual interaktif.
* `8_Machine_Learning.ipynb` - Pelatihan dan evaluasi model *machine learning*.

## Tools & Technologies
**Bahasa & Database:** Python, SQLite/SQL[cite: 2]
**Libraries Utama:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium, Plotly Dash, BeautifulSoup[cite: 2]
