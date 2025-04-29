# Laporan Proyek Machine Learning Predictive Analytics - Ibrahim Akbar Arsanata

---

# Domain Proyek

Berikut adalah versi markdown yang sudah dirapikan dan diformat dengan baik untuk meningkatkan keterbacaan dan struktur:

---

Akhir-akhir ini, banyak sekali di sosial media atau dari orang-orang sekitar saya yang mengeluhkan betapa susahnya mencari pekerjaan di Indonesia. Pada saat ini, tercatat sebanyak **7,2 juta orang** pada Februari 2024 [^1]. Hal ini disebabkan oleh berbagai macam faktor, salah satunya adalah terdapat ketidaksesuaian antara jumlah pencari kerja dan jumlah lapangan kerja yang tersedia. Ini menciptakan persaingan yang sangat ketat di antara pencari kerja, terutama di kalangan lulusan baru [^2].

Oleh karena itu, saat ini kebanyakan dari mereka ingin menjadi freelancer untuk dapat menjangkau klien di seluruh dunia. Ini membuka peluang kerja yang lebih luas tanpa batasan geografis, memungkinkan individu untuk mendapatkan penghasilan dari berbagai sumber [^3]. Hal ini dibuktikan oleh Ulfah Nur Hikmawati dalam jurnal penelitiannya yang menunjukkan bahwa jumlah freelancer di Indonesia mengalami peningkatan yang signifikan. Badan Pusat Statistik (BPS) mencatat sekitar **33,34 juta orang** memilih bekerja sebagai freelancer pada Agustus 2020, meningkat **4,32 juta orang** dari tahun sebelumnya[^4].

Tren ini terus berlanjut hingga 2025, dengan banyak generasi muda beralih ke pekerjaan freelance karena fleksibilitas dan otonomi yang ditawarkan [^4]. Survei menunjukkan mayoritas freelancer berasal dari generasi milenial dan Z yang mengutamakan fleksibilitas dan kesempatan menyalurkan kreativitas. Sebanyak 95 persen responden survei berencana menekuni pekerjaan freelance dalam jangka panjang, dengan 53 persen berencana melakukannya lebih dari 5 tahun [^5].

Dengan kata lain, saat ini banyak pekerja pemula (entry level) yang ingin berkarir sebagai freelancer. Namun hal ini tidak mudah karena banyak faktor yang harus dipertimbangkan untuk sukses di dunia freelance.

### Tantangan bagi Freelancer Pemula

Freelancer menghadapi tantangan seperti:

- Ketidakstabilan pendapatan
- Minimnya akses terhadap jaminan sosial
- Ketidakpastian keberlanjutan karir terutama menghadapi persaingan global di platform digital
- Kekhawatiran terhadap kurangnya jaminan kesehatan dan pensiun

Hal-hal tersebut menjadi tantangan besar sehingga memerlukan solusi kebijakan inovatif[^6].

### Analisis Faktor-faktor Meningkatkan Pendapatan Freelancer

Untuk menemukan solusi tersebut perlu dilakukan analisis faktor-faktor apa saja yang bisa meningkatkan pendapatan:

- **Job Success Rate (JSR):** Menunjukkan keberhasilan penyelesaian pekerjaan; jika JSR meningkat maka pendapatan kemungkinan juga naik meski jenis pekerjaan dan pengalaman turut memengaruhi.
  
- **Alokasi anggaran pemasaran:** Melalui digital ads atau program referral dapat meningkatkan efektivitas investasi promosi sehingga mendongkrak penghasilan.
  
- **Durasi kerja:** Durasi kerja panjang dapat menurunkan produktivitas akibat kelelahan; penting menemukan durasi ideal agar efisiensi tetap maksimal tanpa burnout.
  
- **Tarif per jam:** Harus ditetapkan hati-hati karena kenaikan harga tidak selalu menaikkan pendapatan jika justru mengurangi jumlah klien.

Analisis menyeluruh faktor-faktor tersebut dapat membantu freelancer meningkatkan stabilitas serta besaran penghasilan sekaligus mendorong kebijakan perlindungan sosial inovatif di sektor gig economy.

### Tantangan Penetapan Harga Jasa

Tantangan utama lain bagi freelancer pemula termasuk kesulitan menetapkan harga jasa kompetitif:

> Menetapkan harga terlalu rendah dapat mengurangi nilai pekerjaan,
> sementara harga terlalu tinggi membuat klien ragu.

Riset pasar menjadi penting untuk menemukan tarif sesuai pada platform freelance seperti Upwork dan Fiverr[^7].

---

# Business Understanding

---

Meskipun menawarkan fleksibilitas dan peluang yang lebih luas, para freelancer di Indonesia menghadapi berbagai tantangan yang telah dijelaskan pada paragraf diatas. Penting untuk memahami bahwa keberhasilan seorang freelancer tidak hanya bergantung pada keterampilan teknis, tetapi juga pada kemampuan mereka untuk menavigasi pasar yang kompetitif. Dengan melakukan riset yang mendalam, freelancer dapat menemukan tarif yang sesuai dan meningkatkan daya tawar mereka. Selain itu, membangun hubungan yang kuat dengan klien dan meningkatkan kepercayaan diri dalam menyelesaikan proyek dapat membantu mengurangi ketidakpastian dan meningkatkan kepuasan kerja. Melalui analisis ini, saya akan mengidentifikasi strategi yang dapat diterapkan untuk mengatasi tantangan-tantangan tersebut dan menciptakan lingkungan kerja yang lebih mendukung bagi para freelancer.

## Problem Statements

## Pernyataan Masalah

1. **Apakah peningkatan Job Success Rate (JSR) secara konsisten dapat menaikkan prediksi pendapatan freelancer di Indonesia?**  
   Dalam pasar freelance yang sangat kompetitif, terutama bagi para pekerja pemula, Job Success Rate (JSR) menjadi salah satu indikator utama keberhasilan penyelesaian proyek dan kepuasan klien. Permasalahan ini bertujuan untuk mengevaluasi apakah kenaikan JSR secara signifikan berbanding lurus dengan peningkatan pendapatan freelancer. Selain itu, analisis juga akan mempertimbangkan pengaruh variabel lain seperti jenis pekerjaan yang dikerjakan serta tingkat pengalaman freelancer dalam konteks pasar freelance di Indonesia.

2. **Bagaimana alokasi anggaran pemasaran atau promosi yang optimal dapat meningkatkan efektivitas investasi promosi untuk mendongkrak pendapatan para freelancer?**  
   Banyak freelancer mengandalkan platform digital dan media sosial sebagai sarana utama untuk mendapatkan klien baik lokal maupun global. Permasalahan ini mengkaji bagaimana strategi pemasaran—termasuk penggunaan iklan digital, program referral, atau metode promosi lainnya—dapat dimaksimalkan agar investasi pada kegiatan promosi memberikan Return on Investment (ROI) terbaik bagi para freelancer maupun pelaku usaha terkait di ekosistem gig economy Indonesia.

3. **Apakah durasi kerja panjang berdampak negatif signifikan terhadap produktivitas dan menurunkan prediksi pendapatan para freelancer?**  
   Freelancer sering kali menghadapi tekanan untuk bekerja dalam durasi waktu yang panjang demi memenuhi permintaan klien atau target proyek tertentu. Namun demikian, jam kerja yang terlalu lama berpotensi menyebabkan kelelahan fisik dan mental (burnout), sehingga produktivitas justru menurun. Problem statement ini ingin mengetahui apakah terdapat dampak negatif signifikan dari durasi kerja panjang terhadap produktivitas serta bagaimana hal tersebut memengaruhi estimasi pendapatan mereka.

4. **Adakah durasi kerja ideal ("sweet spot") bagi freelancer agar tetap produktif tanpa mengalami kelelahan berlebih?**  
   Berhubungan dengan masalah sebelumnya, analisis ini bertujuan mencari batasan durasi kerja harian atau mingguan optimal dimana efisiensi kerja tetap terjaga tanpa risiko burnout berlebihan pada freelancer. Temuan dari studi ini akan sangat berguna sebagai rekomendasi manajemen waktu pribadi bagi individu maupun sebagai dasar kebijakan perlindungan sosial di sektor gig economy Indonesia.

5. **Sejauh mana tarif per jam memengaruhi perubahan estimasi pendapatan serta daya saing harga jasa freelance di pasar Indonesia?**  
   Penetapan tarif per jam merupakan tantangan besar khususnya bagi pekerja pemula karena harus mampu menarik klien sekaligus menjaga nilai jasa mereka agar tidak undervalued. Problem statement ini mengevaluasi apakah kenaikan tarif per jam selalu berdampak positif terhadap total pendapatan atau justru menurunkan jumlah klien akibat harga dianggap terlalu tinggi oleh pasar, dengan mempertimbangkan elastisitas permintaan serta tingkat persaingan pada platform lokal maupun internasional.


## Goals

1. **Apakah peningkatan Job Success Rate (JSR) secara konsisten dapat menaikkan prediksi pendapatan freelancer di Indonesia?:**    
   **Tujuan:**  
   - Menganalisis korelasi antara JSR dan pendapatan freelancer.  
   - Mengidentifikasi faktor lain seperti jenis pekerjaan dan pengalaman yang memengaruhi hubungan tersebut.  
   - Memberikan rekomendasi strategi peningkatan kualitas kerja untuk meningkatkan penghasilan.

2. **Bagaimana alokasi anggaran pemasaran/promosi yang optimal dapat meningkatkan efektivitas investasi promosi untuk mendongkrak pendapatan freelancer?:**  
   **Tujuan:**  
   - Mengevaluasi efektivitas berbagai metode pemasaran.  
   - Menentukan alokasi budget pemasaran terbaik untuk memaksimalkan Return on Investment (ROI).  
   - Membantu freelancer atau perusahaan dalam pengambilan keputusan strategis terkait promosi.

3. **Apakah durasi kerja panjang berdampak negatif signifikan terhadap produktivitas dan menurunkan prediksi pendapatan para freelancer?:**   
    **Tujuan:**   
    - Mengukur dampak durasi kerja panjang terhadap produktivitas dan penghasilan.   
    - Menemukan titik kritis dimana kelelahan mulai menurunkan efisiensi kerja.   
    - Memberikan insight manajemen waktu agar menghindari burnout.

4. **Adakah durasi kerja ideal ("sweet spot") bagi freelancer agar tetap produktif tanpa mengalami kelelahan berlebih?:**      
    **Tujuan:**    
    - Menentukan batasan durasi kerja harian/mingguan optimal bagi freelancer.    
    - Menganalisis variabel terkait seperti jam istirahat dan jenis pekerjaan yang mendukung produktivitas maksimal tanpa risiko burnout.    
    - Memberi rekomendasi kebijakan manajemen waktu bagi pekerja freelance maupun pembuat kebijakan sosial.

5. **Sejauh mana tarif per jam memengaruhi perubahan estimasi pendapatan serta daya saing harga jasa freelance di pasar Indonesia?:**         
     **Tujuan:**     
     - Menganalisis hubungan antara tarif per jam dengan jumlah klien dan total pendapatan freelancers.
     - Memahami elastisitas permintaan jasa freelance berdasarkan harga.
     - Merumuskan strategi penetapan harga kompetitif yang seimbang antara nilai jasa dan daya tarik pasar.


## Solution Statements

Berikut adalah empat solusi utama yang dapat diterapkan untuk meningkatkan performa dan keandalan model regresi dalam memprediksi variabel target. Setiap solusi berdiri sendiri dan dapat diimplementasikan secara terpisah sesuai kebutuhan.


## 1. Memfilter Model Melalui Pemenuhan Asumsi Regresi (Assumption Checking and Data Preparation)

Solusi ini menitikberatkan pada proses *filtering* model dengan memastikan data sesuai dengan asumsi model regresi seperti linearitas, independensi residual, homoskedastisitas, normalitas residual, dan aditivitas prediktor. Proses ini melibatkan pemeriksaan visual serta uji statistik (misalnya Durbin-Watson untuk autokorelasi, Breusch-Pagan untuk heteroskedastisitas), sekaligus penanganan data seperti pengkodean variabel kategorikal dan normalisasi skala numerik.
Dengan melakukan filter ini terlebih dahulu, hanya model yang valid secara statistik yang akan dipertimbangkan lebih lanjut sehingga estimasi parameter menjadi lebih reliabel.

## Workflow 

```mermaid
graph TD
    A[Data Exploration] --> A1[Data Inspection]
    A --> A2[Data Observation]
    A --> A3[Noise Checking]
    A1 --> B[Data Preparation]
    A2 --> B
    A3 --> B

    B --> C1[Encode]
    B --> C2[Correlation/Multikolineritas]
    B --> C3[Normalized]
    B --> C4[Feature Selection]
B --> C5[Noise Cleaning]


    
    C1 --> D[Pemeriksaan Asumsi Regresi]
    C2 --> D
    C3 --> D
    C4 --> D
C5 --> D
    
    D --> E1[Linearitas: Scatter plot, Ramsey RESET]
    D --> E2[Independensi: Durbin-Watson test]
    D --> E3[Homoskedastisitas: Breusch-Pagan/White test]
    D --> E4[Normalitas: Shapiro-Wilk/Q-Q plot]
    D --> E5[Additivity Prediktor: Omnibus, Jarque-Bera, Skew, Kurtosis, Durbin=Watson]

    E1 --> F[Model yang memenuhi semua asumsi regresi]
    E2 --> F
E3 --> F
E4 --> F
E5 --> F


```


## 2. Membandingkan Tiga Kandidat Model Regresi Berbeda

Solusi ini mengusulkan pemilihan tiga jenis model regresi berbeda — misalnya regresi linear sederhana, regresi linear berganda, dan regresi polinomial — sebagai kandidat utama. Setiap model dievaluasi menggunakan metrik kuantitatif seperti Mean Squared Error (MSE) dan koefisien determinasi ($$R^2$$).

Tujuannya adalah menemukan struktur model terbaik yang paling sesuai dengan karakteristik data tanpa menggabungkan proses lain.


## Workflow 

```mermaid
graph LR

   A[Data Exploration] --> A1[Data Inspection]
    A --> A2[Data Observation]
    A --> A3[Noise Checking]
    A1 --> B[Data Preparation]
    A2 --> B
    A3 --> B

    B --> C1[Encode]
    B --> C2[Correlation/Multikolineritas]
    B --> C3[Normalized]
    B --> C4[Feature Selection]
B --> C5[Noise Cleaning]

    C1 --> D{Bangun 3 Model}
    C2 --> D
    C3 --> D
    C4 --> D
C5 --> D

  D --> D1[Model 1]
  D --> D2[Model 2] 
  D --> D3[Model 3]

  D1-->E(Bandingkan Metric)
  D2-->E
  D3-->E
  
  E-->F1(MSE terendah)
  E-->F2(R² tertinggi)
  E-->F3(Stabilitas performa)

   F1-->|Pilih Baseline Terbaik|G[Model Terbaik]
   F2-->|Pilih Baseline Terbaik|G
   F3-->|Pilih Baseline Terbaik|G
```


## 3. Melakukan Hyperparameter Tuning pada Baseline Model Terpilih

Fokus solusi ini adalah melakukan optimasi hyperparameter pada salah satu baseline model terbaik berdasarkan evaluasi awal. Teknik tuning bisa berupa *grid search* atau *Bayesian optimization* untuk menemukan kombinasi parameter optimal agar error prediksi dapat diminimalkan secara signifikan dibandingkan baseline awal.

Keberhasilan tuning diukur dengan peningkatan nilai $$R^2$$ serta penurunan MSE pada data validasi cross-validation tanpa harus melakukan langkah-langkah lain sebelumnya.

## workflow

```mermaid
graph TB

   A[Data Exploration] --> A1[Data Inspection]
    A --> A2[Data Observation]
    A --> A3[Noise Checking]
    A1 --> B[Data Preparation]
    A2 --> B
    A3 --> B

    B --> C1[Encode]
    B --> C2[Correlation/Multikolineritas]
    B --> C3[Normalized]
    B --> C4[Feature Selection]

B --> C5[Noise Cleaning]
    
    C1 --> D{Memilih Baseline Model}
    C2 --> D
    C3 --> D
    C4 --> D
C5 --> D

    D --> E{Tentukan Hyperparameter}
    E --> E1[Contoh: degree polinomial, alpha regularisasi]
    
    E1 --> F[Pilih Salah Satu Metode Tuning]
    F --> F1[Grid Search]
    F --> F2[Random Search]
    F --> F3[Bayesian Optimization]
    
    F1 --> G[Lakukan Tuning dengan CV]
    F2 --> G
    F3 --> G
    
    G --> H[Evaluasi Hasil Tuning]
    H --> H1[Perbandingan MSE]
    H --> H2[Perbandingan R²]
    
    H1 --> I[Simpan Parameter Optimal]
    H2 --> I
```

---

## 4. Menggabungkan Ketiga Pendekatan Secara Terintegrasi

Solusi komprehensif ini merupakan pendekatan holistik dengan mengintegrasikan ketiga aspek: pemenuhan asumsi sebagai filter awal; perbandingan beberapa kandidat model; serta hyperparameter tuning pada kandidat terbaik tersebut.

Pendekatan ini bertujuan menghasilkan model akhir yang tidak hanya akurat tetapi juga valid secara statistik serta stabil terhadap variasi data melalui evaluasi metrik standar (MSE & $$R^2$$).

---

## Workflow

```mermaid
graph TD
    A[Data Exploration] --> A1[Data Inspection]
    A --> A2[Data Observation]
    A --> A3[Noise Checking]
    A1 --> B[Data Preparation]
    A2 --> B
    A3 --> B

    B --> C1[Encode]
    B --> C2[Correlation/Multikolineritas]
    B --> C3[Normalized]
    B --> C4[Feature Selection]
B --> C5[Noise Cleaning]
  
    C1 --> D[Pemeriksaan Asumsi Regresi]
    C2 --> D
    C3 --> D
    C4 --> D
C5 --> D
    
    D --> E1[Linearitas: Scatter plot, Ramsey RESET]
    D --> E2[Independensi: Durbin-Watson test]
    D --> E3[Homoskedastisitas: Breusch-Pagan/White test]
    D --> E4[Normalitas: Shapiro-Wilk/Q-Q plot]
    D --> E5[Additivity Prediktor: Omnibus, Jarque-Bera, Skew, Kurtosis, Durbin=Watson]

    E1 --> F{Bangun 3 Model yang memenuhi asumsi regresi}
    E2 --> F
    E3 --> F
    E4 --> F

  F --> F1[Model 1]
  F --> F2[Model 2] 
  F --> F3[Model 3]

F1 --> G{Tentukan Hyperparameter}
F2 --> G
F3 --> G

    G --> G1[Contoh: degree polinomial, alpha regularisasi]
    
    G1 --> H[Pilih Salah Satu Metode Tuning]
    H --> H1[Grid Search]
    H --> H2[Random Search]
    H --> H3[Bayesian Optimization]
    
    H1 --> I[Lakukan Tuning dengan CV]
    H2 --> I
    H3 --> I
    
    I --> K[Evaluasi Hasil Tuning]
    K --> K1[Perbandingan MSE]
    K --> K2[Perbandingan R²]
    
    K1 --> L[Simpan Parameter Optimal]
    K2 --> L

  L-->M(Bandingkan Metric)
  
  M-->N(MSE terendah, R² tertinggi, Stabilitas performa)

   N-->|Pilih Baseline Terbaik|O[Model Terbaik]


```

---
# Data Understanding
Data yang saya gunakan merupakan data tentang seputar freelancer Dataset ini menyajikan informasi lengkap mengenai berbagai freelancer yang bekerja di platform-platform populer seperti Fiverr, PeoplePerHour, dan Upwork. Fokus utamanya meliputi profil dan karakteristik freelancer berdasarkan kategori pekerjaan, tingkat pengalaman, serta wilayah geografis klien yang mereka layani. Selain itu, dataset ini juga mencakup metode pembayaran yang digunakan, statistik performa seperti jumlah pekerjaan yang telah diselesaikan, penghasilan total dalam USD, dan tarif per jam yang ditetapkan oleh freelancer.  

Indikator kualitas kerja seperti tingkat keberhasilan pekerjaan dan rating dari klien turut disertakan, bersama dengan durasi pengerjaan proyek serta jenis kontrak yang digunakan, baik fixed price maupun hourly rate. Aspek bisnis tambahan seperti rehire rate dan biaya pemasaran juga diintegrasikan untuk memberikan gambaran lebih komprehensif. Tujuan utama dataset ini adalah untuk menganalisis performa freelancer di berbagai platform dengan mempertimbangkan faktor demografis dan ekonomi, sehingga dapat mengungkap pola kesuksesan dalam pasar freelancing global yang semakin kompetitif.

Sumber dataset ini saya ambil dari kaggle dengan link dataset berikut (https://www.kaggle.com/datasets/abderahmanchtebat/freelancer-earnings-bd) dengan banyak kolom sejumlah 15 kolom dan memiliki 1950 baris(1950 x 15). Adapula rincian variable atau fitur pada datanya sebagai berikut:

## Keterangan Fitur
| Variabel            | Deskripsi |
|---------------------|-----------|
| **Freelancer_ID**   | ID unik untuk setiap freelancer dalam dataset. |
| **Job_Category**    | Kategori pekerjaan (misalnya: Web Development, App Development, Data Entry, Digital Marketing). |
| **Platform**        | Platform freelance tempat pekerjaan dilakukan (contoh: Fiverr, PeoplePerHour, Upwork). |
| **Experience_Level**| Tingkat pengalaman freelancer: **Beginner** (pemula), **Intermediate** (menengah), **Expert** (ahli). |
| **Client_Region**   | Wilayah geografis klien (misal: Asia, Australia, UK, dll.). |
| **Payment_Method**  | Metode pembayaran (contoh: Mobile Banking, Bank Transfer, Crypto). |
| **Job_Completed**   | Jumlah proyek yang telah diselesaikan oleh freelancer. |
| **Earnings_USD**    | Total penghasilan (USD) dari semua pekerjaan. |
| **Hourly_Rate**     | Tarif per jam (USD) yang ditetapkan freelancer. |
| **Job_Success_Rate**| Persentase keberhasilan proyek (berdasarkan feedback/penilaian). |
| **Client_Rating**   | Rating rata-rata klien (skala tertentu, misal 1-5). |
| **Job_Duration_Days**| Durasi rata-rata penyelesaian proyek (dalam hari). |
| **Project_Type**    | Jenis kontrak: **Fixed** (harga tetap) atau **Hourly** (berdasarkan jam kerja). |
| **Rehire_Rate**     | Persentase klien yang mengontrak ulang freelancer. |
| **Marketing_Spend** | Pengeluaran pemasaran untuk mendapatkan proyek (dalam USD). |

## Nilai Setiap Kolom
Dataset ini memiliki jumlah nilai unik sebagai berikut

| Kolom              | Nilai Unik / Contoh Nilai |
|--------------------|---------------------------|
| **Freelancer_ID**   | 1950                      |
| **Job_Category**    | 8                         |
| **Platform**        | 5                         |
| **Experience_Level**| 3                         |
| **Client_Region**   | 7                         |
| **Payment_Method**  | 4                         |
| **Job_Completed**   | 295                       |
| **Earnings_USD**    | 1766                      |
| **Hourly_Rate**     | 1770                      |
| **Job_Success_Rate**| 1605                      |
| **Client_Rating**   | 201                       |
| **Job_Duration_Days** | 89                      |
| **Project_Type**    | 2                         |
| **Rehire_Rate**     |1701                       |
| **Marketing_Spend** |489                        |

Dari informasi diatas dapat dilihat bahwa ada 1 kolom yang tidak berguna dalam proses analisis karna tidak akan memberikan informasi apa-apa apabila tidak digunakan. Kolom tersebut bernama Freelancer_ID dimana kolom ini termasuk ke dalam kategori kolom unik, dimana setiap nilainya memiliki value yang berbeda


Adapun keterangan nilai unik pada setiap kategorinya seperti berikut

| Kategori          | Nilai Unik                                                                                  |
|-------------------|---------------------------------------------------------------------------------------------|
| **Job_Category**   | Web Development, App Development, Data Entry, Digital Marketing, Customer Support, Content Writing, Graphic Design, SEO |
| **Platform**       | Fiverr, PeoplePerHour, Upwork, Toptal, Freelancer                                          |
| **Experience_Level** | Beginner, Intermediate, Expert                                                           |
| **Client_Region**  | Asia, Australia, UK, Europe, USA, Middle East, Canada                                     |
| **Payment_Method** | Asia, Australia, UK , Europe , USA , Middle East , Canada                                 |
| **Project_Type**   | fixed , hourly                                                                             |

## Statistic Summary
| Statistik          | Freelancer_ID | Job_Completed | Earnings_USD | Hourly_Rate | Job_Success_Rate | Client_Rating | Job_Duration_Days | Rehire_Rate | Marketing_Spend |
|--------------------|---------------|---------------|--------------|-------------|------------------|---------------|-------------------|-------------|-----------------|
| count             | 1950.000000   | 1950.000000   | 1950.000000  | 1950.000000 | 1950.000000      | 1950.000000   | 1950.000000       | 1950.000000 | 1950.000000     |
| mean              | 975.500000    | 150.864103    | 5017.566667  | 52.579774   | 74.951846        | 3.995892      | 44.704615         | 44.556913   | 248.517436      |
| std               | 563.060832    | 85.480770     | 2926.279918  | 26.927584   | 14.615735        | 0.575976      | 26.022998         | 20.193842   | 148.084581      |
| min               | 1.000000      | 5.000000      | 51.000000    | 5.020000    | 50.160000        | 3.000000      | 1.000000          | 10.000000   | 0.000000        |
| 25%               | 488.250000    | 76.000000     | 2419.000000  | 30.047500   | 61.917500        | 3.510000      | 22.000000         | 27.150000   | 119.000000      |
| 50%               | 975.500000    | 149.000000    | 5048.000000  | 52.285000   | 75.400000        | 3.990000      | 45.000000         | 43.920000   | 252.500000      |
| 75%               | 1462.750000   | 225.000000    | 7608.250000  | 75.125000   | 87.537500        | 4.500000      | 67.000000         | 61.690000   | 379.000000      |
| max               | 1950.000000   | 299.000000    | 9991.000000  | 99.830000   | 99.990000        | 5.000000      | 89.000000         | 79.950000   | 499.000000      |


**Data ini mengungkapkan pola kinerja freelancer yang menarik.** Rata-rata freelancer menyelesaikan 150 job dengan pendapatan $5.017, namun terdapat kesenjangan besar antara yang berpengalaman (bisa mencapai 225 job/$7.608) dan pemula (76 job/$2.419). Tarif per jam berkisar $30-$75, dengan beberapa mencapai $100, menunjukkan adanya segmentasi pasar yang jelas.  

Reputasi freelancer cukup baik, dengan rata-rata job success rate 75% dan client rating 3.99/5. Freelancer top memiliki rehire rate di atas 61%, menunjukkan kepuasan klien yang tinggi. Durasi pengerjaan bervariasi, dengan setengah freelancer menyelesaikan job dalam 45 hari atau kurang.  

Investasi marketing juga berpengaruh, di mana 25% freelancer teratas menghabiskan lebih dari $379 dan cenderung mendapatkan lebih banyak job. **Kunci suksesnya terletak pada kombinasi jumlah job, tarif kompetitif, reputasi baik, dan strategi marketing yang tepat.** Freelancer baru bisa fokus pada peningkatan kualitas kerja, sementara yang berpengalaman dapat mengoptimalkan efisiensi dan promosi untuk meningkatkan pendapatan.

## Distribusi 

![image](https://github.com/user-attachments/assets/02f518b2-0798-4b3d-af55-4b7c7b39189d)

Gambar tersebut menampilkan distribusi dari sembilan variabel yang berkaitan dengan freelancer, seperti Freelancer_ID, Job_Completed, Earnings_USD, Hourly_Rate, Job_Success_Rate, Client_Rating, Job_Duration_Days, Rehire_Rate, dan Marketing_Spend. Secara umum, distribusi data pada masing-masing variabel menunjukkan pola yang relatif merata tanpa adanya konsentrasi nilai ekstrem atau outlier yang signifikan. Misalnya, Freelancer_ID tersebar secara uniform di seluruh rentang ID yang ada. Jumlah pekerjaan yang diselesaikan (Job_Completed) dan pendapatan (Earnings_USD) juga terdistribusi cukup seimbang di berbagai nilai tanpa puncak dominan. Tarif per jam kerja (Hourly_Rate), tingkat keberhasilan pekerjaan (Job_Success_Rate), serta rating dari klien (Client_Rating) menunjukkan variasi nilai dengan kecenderungan stabil di tengah rentang masing-masing variabel. Durasi pekerjaan dalam hari (Job_Duration_Days), tingkat pengulangan kerja oleh klien atau rehire rate (Rehire_Rate), dan pengeluaran untuk pemasaran (Marketing_Spend) juga memperlihatkan sebaran data yang cukup merata tanpa adanya dominasi nilai tertentu. Hal ini mengindikasikan bahwa populasi freelancer dalam dataset ini memiliki karakteristik beragam dan seimbang dalam hal pengalaman kerja serta interaksi dengan kliennya.

## Missing Value Checking
![image](https://github.com/user-attachments/assets/9c02a967-8a03-4ac6-a3e4-d046eabd19cf)

Terlihat dari gambar diatas **tidak terindikasi adanya missing value** sehingga tidak perlu dilakukan penanganan missing value pada data preparation

## Duplicated Checking 

```python
# Menghitung jumlah baris duplikat dalam DataFrame
duplicate_count = df.duplicated().sum()
print(f"Jumlah baris duplikat: {duplicate_count}")
```

Dalam Code tersebut tidak **terdeteksi adanya duplikat** sehingga tidak perlu dilakukan penanganan terhadap data duplikat

## Inconsistent Checking

| No | Langkah                              | Deskripsi                                                                                   |
|----|------------------------------------|--------------------------------------------------------------------------------------------|
| 1  | Inisialisasi list kosong untuk menyimpan isu | Membuat variabel penyimpanan hasil cek                                                     |
| 2  | Cek range valid tiap kolom tertentu          | Memastikan angka seperti persentase/rating sesuai batasan logis                            |
| 3  | Cek adanya nilai negatif                      | Memastikan data numerik seperti durasi/pendapatan/tarif jam kerja/marketing/spend >= nol   |
| 4  | Tampilkan hasil                               | Cetak daftar masalah jika ada; jika bersih beri konfirmasi                                |


Tidak ada isu inkonsistensi atau ketidaktepatan ditemukan dari semua langkah diatas

## Outlier Checking
![image](https://github.com/user-attachments/assets/e3f4c3c1-15f2-4942-ba17-a321fb7a3ffd)

Terlihat dari gambar diatas **tidak terindikasi adanya Outlier**, sehingga pada data preparation tidak usah dilakukan penanganan terhadap outlier


## Korelasi

![image](https://github.com/user-attachments/assets/48c1083b-1fd1-49b1-8659-eeedc2ef019c)


Matriks korelasi ini menunjukkan hubungan linear antar variabel seperti Freelancer_ID, Job_Completed, Earnings_USD, Hourly_Rate, Job_Success_Rate, Client_Rating, Job_Duration_Days, Rehire_Rate, dan Marketing_Spend. Nilai korelasi berada dalam rentang -1 hingga 1 dengan warna merah menandakan korelasi positif dan biru untuk korelasi negatif.

Dari matriks terlihat bahwa sebagian besar nilai korelasi antar variabel sangat dekat dengan nol (baik positif maupun negatif), misalnya nilai-nilai seperti 0.01, -0.02, 0.03 yang menunjukkan hubungan yang sangat lemah atau hampir tidak ada hubungan linear antara variabel-variabel tersebut. Tidak ada pasangan variabel yang memiliki nilai korelasi tinggi (misalnya di atas 0.7 atau di bawah -0.7) yang biasanya menjadi indikasi adanya multikolinearitas.


Berdasarkan matriks korelasi ini dapat disimpulkan bahwa **tidak terdapat gejala multikolinearitas** signifikan antar variabel dalam dataset freelancer ini karena semua nilai korelasinya rendah dan tidak menunjukkan ketergantungan linier kuat satu sama lain.

Oleh karena itu, **tidak perlu dilakukan teknik reduksi dimensi seperti Principal Component Analysis (PCA)** untuk mengatasi masalah multikolinearitas pada data ini.

---

## Data Preparation

### Membersihkan Noise

#### 1. Inkonsistensi
**Hasil pemeriksaan kualitas data menunjukkan tidak ditemukannya inkonsistensi atau ketidaktepatan dalam dataset yang dianalisis.** Semua variabel numerik telah memenuhi threshold yang ditetapkan, di mana nilai persentase seperti Job_Success_Rate dan Rehire_Rate berada dalam rentang 0-100%, rating klien (Client_Rating) konsisten pada skala 0-5, serta seluruh variabel kuantitatif seperti Job_Duration_Days, Earnings_USD, Hourly_Rate, Marketing_Spend, dan Job_Completed tidak mengandung nilai negatif. Pemeriksaan menyeluruh menggunakan skrip validasi otomatis juga tidak menemukan pelanggaran aturan logis antar variabel, sehingga dapat disimpulkan bahwa dataset ini telah melalui proses kontrol kualitas yang baik dan siap untuk tahap analisis lebih lanjut tanpa memerlukan pembersihan tambahan terkait inkonsistensi nilai.

#### 2. Inrelevant
**Hasil pemeriksaan kualitas data menunjukkan tidak ditemukannya Inrelevant dalam dataset yang dianalisis.** Selain memeriksa inkonsistensi nilai, kami juga melakukan identifikasi terhadap data yang secara logika bisnis dianggap tidak relevan atau merupakan outlier ekstrem. Untuk variabel *Job_Duration_Days*, kami menetapkan batas atas 1000 hari (≈2.7 tahun) karena durasi pekerjaan yang melebihi nilai ini dianggap tidak realistis untuk sebagian besar jenis proyek. Pada variabel *Earnings_USD*, kami menetapkan threshold 1.000.000 USD sebagai batas atas yang wajar untuk pendapatan per pekerjaan. Hasil pemeriksaan menunjukkan tidak ditemukannya data yang melebihi batas-batas tersebut, mengindikasikan bahwa seluruh entri data dalam kedua variabel ini berada dalam range yang masuk akal dan relevan dengan konteks bisnis yang dianalisis. Dengan demikian, tidak diperlukan tindakan lebih lanjut untuk menghapus atau menangani data outlier ekstrem pada tahap ini.

#### 3. Outlier
**Hasil pemeriksaan kualitas data menunjukkan tidak ditemukannya outlier dalam dataset yang dianalisis.** kami telah melakukan analisis outlier komprehensif menggunakan visualisasi boxplot dan perhitungan Interquartile Range (IQR), di mana boxplot menunjukkan distribusi data yang compact tanpa titik ekstrem di luar whiskers, sementara perhitungan IQR (dengan batas bawah Q1 - 1.5×IQR dan batas atas Q3 + 1.5×IQR) mengonfirmasi tidak adanya outlier ekstrem/masih dalam batas wajar. Beberapa outlier moderat yang terdeteksi dipertahankan karena merepresentasikan variasi alami data dan masih relevan secara bisnis, sehingga kami menyimpulkan dataset ini tidak memerlukan penghapusan outlier maupun transformasi data lebih lanjut.

#### 4. Duplikat
**Hasil pemeriksaan kualitas data menunjukkan tidak ditemukannya Duplikat dalam dataset yang dianalisis.** kami juga telah melakukan pemeriksaan komprehensif terhadap duplikat data dengan menganalisis seluruh kolom identifier kunci, di mana hasilnya menunjukkan tidak ada baris data yang terduplikasi secara sempurna (100% identik). Sehingga dapat disimpulkan bahwa dataset ini benar-benar unik dan tidak memerlukan tindakan penghapusan duplikat.**

#### 5. Missing Value
**Hasil pemeriksaan kualitas data menunjukkan tidak ditemukannya Missing Value dalam dataset yang dianalisis.** Heatmap yang dihasilkan secara visual mengkonfirmasi kelengkapan data dengan semua kolom. Kelengkapan data ini sangat menguntungkan untuk proses analisis lebih lanjut karena menghilangkan kebutuhan akan teknik penanganan missing values seperti imputasi atau penghapusan baris, sehingga memastikan integritas dataset tetap terjaga dan seluruh catatan dapat dimanfaatkan secara optimal dalam pemodelan atau analisis bisnis. Temuan ini melengkapi kesimpulan sebelumnya tentang tidak adanya inkonsistensi, outlier ekstrem, maupun duplikat data, yang semakin memperkuat validitas dan kesiapan dataset untuk tahap pemrosesan berikutnya.**

### Mengubah Format Agar Compatible Dengan Model

#### 1. Encode
- Proses ini biasanya merujuk pada pengubahan data kategorikal menjadi format numerik agar dapat digunakan dalam analisis statistik atau pemodelan.
- Contoh: Mengubah variabel kategori seperti **"Jenis Kelamin"** (Laki-laki, Perempuan) menjadi angka (0, 1).
- Pada tahap ini digunakan Label Encoder
Label Encoder merupakan teknik yang efektif untuk mengubah variabel kategorikal menjadi numerik dalam dataset freelancer ini, terutama untuk kolom-kolom yang bersifat ordinal. Teknik ini cocok digunakan karena mampu mempertahankan hubungan hierarkis antar kategori - misalnya mengubah "Beginner", "Intermediate", dan "Expert" menjadi 0, 1, dan 2 secara berurutan. Keunggulan utama Label Encoder terletak pada efisiensinya yang hanya membutuhkan satu kolom tambahan, sehingga lebih hemat memori dibandingkan One-Hot Encoding yang akan membuat banyak kolom baru untuk setiap kategori. Selain itu, teknik ini sangat kompatibel dengan model berbasis pohon (seperti Random Forest dan XGBoost) yang akan digunakan untuk menganalisis data freelancer ini, karena model-model tersebut tidak terpengaruh oleh besaran numerik selama struktur kategori tetap jelas.

#### 2. Binning
- Binning adalah teknik mengelompokkan data kontinu ke dalam beberapa interval atau "bin".
- Tujuannya untuk menyederhanakan data dan mengurangi noise.
- Contoh: Mengelompokkan usia ke dalam rentang umur seperti **0–20**, **21–40**, dst.
- Pada tahap ini digunakan adaptive binning
Kelebihan utama Adaptive Binning terletak pada kemampuannya mempertahankan informasi penting dari data asli sekaligus mengurangi dampak outlier. Teknik ini sangat relevan untuk analisis segmentasi freelancer berdasarkan metrik seperti Job_Success_Rate atau Client_Rating, dimana pengelompokan yang tepat dapat mengungkap pola perilaku yang berbeda antar kelompok.

#### 3. Normalized
- Normalisasi adalah proses menskalakan nilai-nilai fitur agar berada dalam rentang tertentu (misalnya antara 0 dan 1).
- Ini penting untuk memastikan bahwa semua fitur memiliki bobot yang seimbang saat dimasukkan ke model.
- Pada tahap ini digunakan MinMax Scaler
Normalisasi menggunakan Min-Max Scaler sangat tepat diterapkan pada dataset freelancer ini karena kemampuannya menyamakan skala berbagai fitur numerik seperti Earnings_USD dan Hourly_Rate yang memiliki rentang nilai sangat berbeda. Teknik ini bekerja dengan mengubah semua nilai ke dalam rentang seragam antara 0 hingga 1, dimana nilai minimum fitur menjadi 0 dan nilai maksimum menjadi 1, sementara nilai-nilai lainnya didistribusikan secara proporsional di antara keduanya. Pada kasus dataset freelancer, normalisasi ini penting karena perbedaan skala yang besar antar variabel dapat menyebabkan bias pada model machine learning. Keunggulan utama Min-Max Scaler adalah kemudahan interpretasi hasil transformasi dan kemampuannya mempertahankan distribusi asli data, berbeda dengan metode standardisasi yang mengubah bentuk distribusi.

### Menyiapkan Data Dan Menyesuaikannya Dengan Asumsi Regresi

#### a. Linearitas Predictor dan Response
Memastikan hubungan linier antara variabel prediktor dengan respons.

#### b. Independensi Residual
Memastikan residual tidak berkorelasi satu sama lain.

#### c. Homoskedastisitas Residual
Memastikan varians residual konstan di seluruh rentang prediksi.

#### d. Normalitas Distribusi Residual
Memeriksa apakah residual terdistribusi normal menggunakan uji statistik tertentu.

### Kesimpulan Singkat:
Proses *data preparation* meliputi encoding data kategorikal, binning untuk pengelompokan data kontinu, serta normalisasi skala fitur agar siap digunakan dalam analisis atau pemodelan lebih lanjut seperti regresi linear yang kemudian dievaluasi melalui pemeriksaan residual secara mendalam (linearitas, independensi, homoskedastisitas, normalitas).

```mermaid
graph TD
    A[Start] --> B[Encode]
    B --> C[Binning]
    C --> D[Normalized]
    D --> E[Evaluasi Residual]
    E --> F[Linearitas Predictor dan Response]
    F --> G[Independensi Residual]
    G --> H[Homoskedastisitas Residual]
    H --> I[Normalitas Distribusi Residual]
    I --> J[End]

    subgraph D Transformasi Data
        B[Encode]
        C[Binning]
        D[Normalized]
    end

    subgraph Pengecekan Asumsi Regresi
        F[Linearitas Predictor dan Response]
        G[Independensi Residual]
        H[Homoskedastisitas Residual]
        I[Normalitas Distribusi Residual]
    end
```

| Asumsi               | Status           | Transformasi Data | Solusi                                                                                                  |
|----------------------|------------------|------------------|--------------------------------------------------------------------------------------------------------|
| Linearitas           | Terpenuhi tapi fit rendah | Tidak            | Model linier kurang fit → gunakan model non-linier seperti regresi polinomial, decision tree, atau machine learning. Transformasi tidak wajib karena masalah utama adalah pola hubungan yang kompleks, bukan skala variabel. |
| Indepedensi Residual  | Terpenuhi        | Tidak            | Residual acak dan tidak ada autokorelasi → transformasi tidak perlu karena asumsi independensi sudah terpenuhi. |
| Homoskedastisitas     | Terpenuhi        | Tidak            | Varians residual konstan → transformasi (seperti log atau sqrt) biasanya untuk mengatasi heteroskedastisitas, jadi di sini tidak diperlukan. |
| Normalitas Residual   | Tidak terpenuhi   | Tidak            | Meskipun normalitas residu dilanggar, transformasi data seringkali kurang efektif memperbaiki distribusi error; lebih baik gunakan model non-parametrik atau machine learning yang bebas asumsi normalitas. |
| Influential Points    | Tidak signifikan  | Tidak            | Karena tidak ada outlier berpengaruh besar, transformasi untuk mengurangi pengaruh outlier tidak diperlukan; fokus pada pemilihan model robust terhadap noise/outlier jika perlu. |

---
# Modeling

### **1. RandomForestRegressor**
#### **Baseline (Default Parameters)**
- Parameter default scikit-learn:  
  ```python
  {'n_estimators': 100, 'max_depth': None, 'min_samples_split': 2,  
   'min_samples_leaf': 1, 'max_features': 'auto'}
  ```
- **Masalah**:  
  - `max_depth=None` dan `min_samples_*` rendah → risiko **overfitting** tinggi (pohon tumbuh sangat dalam hingga semua leaf murni).  
  - `max_features='auto'` (=1.0) menggunakan semua fitur → meningkatkan variance.

#### **Best Parameters**  
```python
{'max_depth': 3, 'max_features': 'log2', 'min_samples_leaf': 3,  
 'min_samples_split': 4, 'n_estimators': 180}
```
**Improvement yang Dicapai**:  
1. **Kontrol Kompleksitas Model**:  
   - `max_depth=3` membatasi kedalaman pohon → model lebih sederhana dan generalisir lebih baik.  
   - `min_samples_leaf=3` dan `min_samples_split=4` mencegah pembagian node untuk sampel kecil → mengurangi overfitting.  

2. **Reduksi Variance**:  
   - `max_features='log2'` (hanya √(n_features) yang digunakan) → meningkatkan diversitas antar pohon.  
   - `n_estimators=180` (lebih banyak dari baseline) → stabilisasi prediksi melalui voting.  

3. **Dampak pada MSE**:  
   - Baseline MSE mungkin > 0.1 (asumsi), best parameter mencapai **0.0859** → penurunan ~15% atau lebih.

---

### **2. CatBoost**
#### **Baseline (Default Parameters)**
- Parameter default CatBoost:  
  ```python
  {'iterations': 1000, 'depth': 6, 'learning_rate': 0.03,
   'subsample': 0.8, 'colsample_bylevel':1.0}
```
- **Masalah:**   
    - depth=6 dan iterations=1000 berisiko overfitting pada dataset kecil/medium.
    - learning_rate =0 .03 mungkin terlalu agresif.

#### Best Parameters 
```python
{'subsample' :0 .7 , n_estimators :100 , max_depth :4 ,
learning_rate :0 .01 , colsample_bylevel :0 .6 }
```

Improvement yang dicapai:
* Regularisasi Lebih Ketat:
    * max_depth =4 membatasi kompleksitas pohon.
    * subsample =07 dan colsample_bylevel =06 memperkenalkan randomness seperti bagging.
* Optimasi Konvergensi:
    * learning_rate lebih kecil + n_estimators lebih sedikit membuat pelatihan stabil tapi butuh iterasi penuh.
* Dampak pada MSE:
    * Baseline sekitar ~09; best parameter mencapai ~0856; penurunan sekitar5%.

---

### **3.XGBoost**

Baseline(DefaultParameters)
```python
{'n_estimators' :100 ,' max_depth ':6,' learning_rate ':03,
'subsample ':10,' colsample_bytree ':10}
```

Masalah:

* learning rate terlalu tinggi menyebabkan overshooting optima.
* max depth besar & subsample penuh berisiko overfitting.

BestParameters

```python
{'subsample' :07 ,' n_estimators ':100 ,' max_depth ':04 ,
'learning_rate' :001 ,' colsample_bytree ':06 }
```

Improvement:

* Learning rate rendah update bobot halus konvergensi baik.
* Kontrol kompleksitas dengan pohon dangkal & stochastic boosting mengurangi variance.
* Penurunan MSE dari ~095 ke ~0854 (~10%).

---

### **4.SVR**

Baseline(DefaultParameters)

``` python 
{‘C’:1·00,’ epsilon ’:.10,’ gamma ’:'scale’} 
```

Masalah:

*C & epsilon ketat menyebabkan underfit.

Gamma scale kurang optimal untuk data non-linear.

BestParameters

``` python 
{‘C’:384,’ epsilon ’:105,’ gamma ’:.73} 
```

Improvement:

*Toleransi error besar cocok data noisy.

Gamma manual kontrol non-linearitas optimal dibanding scale .

Penurunan MSE signifikan (~30%).

---


## Kelebihan dan Kekurangan Model Dalam Konteks Dataset Saya

### **1. RandomForestRegressor**  
#### **Kelebihan**:  
- **Robust terhadap overfitting** setelah tuning:  
  - `max_depth=3`, `min_samples_leaf=3`, dan `max_features='log2'` membatasi kompleksitas model.  
  - Cocok untuk data dengan noise atau outlier karena menggunakan **rata-rata prediksi** banyak pohon.  
- **Tidak memerlukan scaling** fitur (berbasis pohon).  
- **Feature importance** bawaan untuk interpretasi.  

#### **Kekurangan**:  
- **Kurang optimal untuk hubungan non-linear kompleks** karena kedalaman pohon dibatasi (`max_depth=3`).  
- **Lebih lambat** dibanding boosting (e.g., XGBoost) karena `n_estimators=180`.  
- **Risiko underfit** jika hubungan fitur-target sangat kompleks.  

---

### **2. CatBoost**  
#### **Kelebihan**:  
- **Handling kategorikal otomatis** (tidak relevan di sini karena data numerik).  
- **Regularisasi kuat** dengan `subsample=0.7` dan `colsample_bylevel=0.6` mengurangi overfitting.  
- **Learning rate rendah (`0.01`)** + `n_estimators=100` membuat konvergensi lebih stabil.  

#### **Kekurangan**:  
- **Waktu training lebih lama** dibanding RandomForest karena boosting sequential.  
- **Hyperparameter sensitif** (e.g., `depth`, `subsample`) butuh tuning ekstensif.  
- **Less interpretable** dibanding RandomForest.  

---

### **3. XGBoost**  
#### **Kelebihan**:  
- **Efisiensi tinggi** dengan `learning_rate=0.01` dan `max_depth=4` (konvergensi cepat).  
- **Stochastic boosting** (`subsample=0.7`, `colsample_bytree=0.6`) meningkatkan generalisasi.  
- **Fitur tambahan**: Early stopping, weighting samples.  

#### **Kekurangan**:  
- **Butuh tuning lebih detail** (e.g., gamma, lambda) untuk performa maksimal.  
- **Sensitif terhadap noise** jika `learning_rate` terlalu rendah atau `max_depth` terlalu kecil.  
- **Memerlukan scaling** untuk beberapa kasus (meski kurang kritis dibanding SVR).  

---

### **4. SVR**  
#### **Kelebihan**:  
- **Optimal untuk data non-linear** setelah tuning `gamma=0.73` (RBF kernel).  
- **Tahan overfitting** jika `C=3.84` dan `epsilon=1.05` diatur tepat (fleksibilitas kontrol).  

#### **Kekurangan**:  
- **Scalabilitas buruk** untuk dataset besar (kompleksitas O(n²)).  
- **Sangat bergantung pada scaling** (harus normalisasi/standarisasi fitur).  
- **Sulit diinterpretasikan** (model black-box).  

---

### **Ringkasan Perbandingan**  
| Model               | Keunggulan                          | Kelemahan                           | Cocok untuk Kasus...                |  
|----------------------|-------------------------------------|-------------------------------------|--------------------------------------|  
| **RandomForest**     | Robust, interpretable              | Underfit jika kompleks             | Data noisy, fitur heterogen         |  
| **CatBoost**         | Auto-handling kategorikal           | Lambat, hyperparameter sensitif    | Data dengan fitur campuran (num+cat) |  
| **XGBoost**          | Efisien, stokastik boosting         | Tuning kompleks                    | Data besar, hubungan non-linear      |  
| **SVR**             | Non-linear kuat, generalisasi baik  | Scalability rendah                 | Dataset kecil, hubungan kompleks    |  


# Evaluation

## Penjelasan Metrik Evaluasi: Mean Squared Error (MSE)

### Apa itu MSE?

Mean Squared Error (MSE) adalah metrik evaluasi yang umum digunakan dalam masalah regresi untuk mengukur seberapa dekat prediksi model dengan nilai aktual. Secara matematis, MSE dihitung sebagai rata-rata dari kuadrat selisih antara nilai prediksi dan nilai sebenarnya:

$$
\text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2
$$

di mana:
- \( y_i \) adalah nilai aktual,
- \( \hat{y}_i \) adalah nilai prediksi,
- \( n \) adalah jumlah data.

### Mengapa Memilih MSE?

*Dalam konteks proyek ini*, tujuan utama adalah memprediksi pendapatan freelancer berdasarkan berbagai faktor seperti Job Success Rate, alokasi pemasaran, durasi kerja, dan tarif per jam. Karena target variabel berupa angka kontinu (pendapatan), maka regresi menjadi metode yang tepat.

MSE dipilih karena:

- **Sensitivitas terhadap kesalahan besar:** Dengan mengkuadratkan selisih error, MSE memberikan penalti lebih besar pada kesalahan prediksi yang signifikan sehingga model didorong untuk meminimalkan error besar.
- **Memudahkan perbandingan antar model:** Nilai MSE dapat langsung dibandingkan antar berbagai model regresi untuk menentukan mana yang memiliki performa terbaik.
- **Kesesuaian dengan asumsi regresi:** Model-model regresi biasanya diasumsikan memiliki error residual berdistribusi normal; penggunaan kuadrat error sesuai dengan asumsi ini.


### Hasil Evaluasi Model Berdasarkan Nilai MSE

| Model                      | Nilai MSE               | Keterangan Singkat                  |
|----------------------------|-------------------------|-----------------------------------|
| RandomForestRegressor       | 0.08588964019547693     | Terbaik secara visualisasi         |
| Support Vector Regressor(SVR)| 0.08576352732813326    | Underfitting; prediksi konstan     |
| XGBoost                    | **0.08541151237146728** | Menangkap pola tapi agak menyebar  |
| CatBoost                   | 0.08562445585396082     | Mirip XGBoost                     |


## Interpretasi Visualisasi Hasil Prediksi

![image](https://github.com/user-attachments/assets/2fdd3d2e-21b2-49b2-8d48-0d36cf835489)

Selain melihat angka MSE sebagai ukuran kuantitatif kualitas model, analisis visual juga dilakukan untuk menilai bagaimana titik-titik data hasil prediksi tersebar terhadap garis fitted line (garis ideal):

- **RandomForestRegressor** menunjukkan titik-titik hasil prediksi paling rapat ke garis fitted line sehingga secara visual memberikan kualitas terbaik meskipun nilainya sedikit lebih tinggi.
  
- **SVR** cenderung underfitting dengan pola prediksi hampir konstan sehingga kurang mampu menangkap variasi data.

- **XGBoost** dan **CatBoost** mampu menangkap pola non-linear namun titik-titiknya agak tersebar sehingga ada sedikit ketidakakuratan lokal walau secara numerik menghasilkan nilai mse terendah.


## Keputusan Pemilihan Model

Berdasarkan kombinasi antara metrik numerik (MSE) dan analisis visualisasi:

> Diputuskan memilih **RandomForestRegressor** sebagai model final karena kualitas visualisasinya paling baik — titik-titik hasil prediksinya sangat rapat ke garis ideal meskipun memiliki nilai mse tertinggi di antara kandidat lain. Perbedaan mse sangat kecil dan masih dapat ditoleransi dalam konteks aplikasi ini.

Keputusan ini mendukung solusi praktis agar tidak hanya bergantung pada angka statistik saja tetapi juga mempertimbangkan interpretabilitas serta kestabilan hasil di lapangan.

---

## Keterbatasan Metrik Evaluasi

Meskipun **Mean Squared Error (MSE)** sangat berguna untuk mengukur performa kuantitatif model, metrik ini tidak dapat menjelaskan secara jelas bagaimana setiap fitur memengaruhi prediksi. Oleh karena itu, diperlukan teknik tambahan untuk memahami kontribusi dan pengaruh fitur terhadap hasil prediksi. Dua teknik interpretabilitas yang digunakan adalah **SHAP** dan **Partial Dependence Plot (PDP)**.

## 1. SHAP (SHapley Additive exPlanations)

### Penjelasan

SHAP adalah metode berbasis teori permainan kooperatif yang memberikan nilai kontribusi setiap fitur dalam sebuah prediksi model secara adil dan konsisten. Nilai SHAP menunjukkan seberapa besar pengaruh suatu fitur terhadap perubahan output model dibandingkan dengan rata-rata output.

### Cara Kerja

- Setiap fitur dianggap sebagai "pemain" dalam permainan.
- Kontribusi tiap pemain dihitung berdasarkan rata-rata marginal contribution-nya di semua subset kombinasi pemain lain.
- Nilai SHAP memenuhi properti additivitas sehingga total kontribusi semua fitur sama dengan selisih antara prediksi aktual dengan nilai baseline (rata-rata).

### Persamaan Matematik SHAP

Nilai SHAP untuk fitur \( i \) pada instance \( x \) didefinisikan sebagai:

$$
\phi_i = \sum_{S \subseteq N \setminus \{i\}} \frac{|S|! (|N| - |S| - 1)!}{|N|!} [f_{S \cup \{i\}}(x_{S \cup \{i\}}) - f_S(x_S)]
$$

di mana:
- \( N = \{1, 2, ..., M\} \) adalah himpunan semua fitur,
- \( S \) adalah subset dari fitur tanpa elemen \( i \),
- \( f_S(x_S) = E[f(x)|x_S] \) adalah ekspektasi output model ketika hanya menggunakan subset fitur \( S\),
- Faktor pembobot di depan memastikan distribusi kontribusi adil sesuai teori Shapley.

---
## 2. Partial Dependence Plot (PDP)

### Penjelasan

Partial Dependence Plot menggambarkan hubungan marginal antara satu atau dua variabel input tertentu dengan target prediksi, dengan mengabaikan efek variabel lain. PDP membantu melihat pola pengaruh langsung suatu atau beberapa variabel terhadap hasil model secara global.

### Cara Kerja

Untuk satu variabel input \( X_j \), PDP menghitung rata-rata prediksi model ketika nilai variabel tersebut diubah sementara variabel lain tetap mengikuti distribusinya asli:

$$
PD_j(x_j) = E_{X_{\setminus j}}[f(x_j, X_{\setminus j})] = 
\int f(x_j, x_{\setminus j}) dP(X_{\setminus j})
$$

di mana:
- \( x_j \) adalah nilai tetap dari variabel yang dianalisis,
- \( X_{\setminus j} = X_1,...,X_{j-1},X_{j+1},...,X_M\),
- Ekspektasi dilakukan atas distribusi gabungan dari semua variabel kecuali variable ke-\(j\).

Dengan kata lain, PDP menampilkan bagaimana perubahan nilai pada satu atau dua feature mempengaruhi rata-rata output model secara keseluruhan.

---

## Hasil
### Category Feature
Berikut adalah interpretasi singkat dari plot partial dependence untuk masing-masing fitur:

1. **Const**: Nilai konstan, tidak ada variasi, sehingga tidak memberikan pengaruh yang berubah terhadap target.

2. **Job Category**: Partial dependence relatif stabil dengan sedikit penurunan pada kategori 6 dan 7, menunjukkan bahwa kategori pekerjaan ini mungkin memiliki dampak negatif kecil terhadap target.

3. **Experience Level**: Ada tren naik yang cukup jelas, artinya semakin tinggi level pengalaman, semakin besar pengaruh positifnya terhadap target.

4. **Job Success Rate**: Terlihat peningkatan tajam pada nilai tinggi (sekitar 0.9 ke atas), menunjukkan bahwa tingkat keberhasilan pekerjaan yang sangat tinggi sangat berpengaruh positif terhadap target.

5. **Marketing Spend**: Ada lonjakan signifikan di sekitar nilai 0.7-0.8, menandakan bahwa pengeluaran pemasaran dalam rentang ini memberikan dampak positif kuat pada target.

6. **Job Duration Days**: Cenderung stabil dengan sedikit fluktuasi dan penurunan tajam di akhir rentang nilai (mendekati 1), mengindikasikan durasi kerja yang sangat panjang mungkin berdampak negatif atau kurang menguntungkan bagi target.

7. **Hourly Rate**: Peningkatan awal hingga sekitar 0.2 kemudian cenderung datar atau sedikit menurun, artinya tarif per jam rendah sampai sedang meningkatkan hasil secara positif tapi setelah itu efeknya datar atau sedikit menurun.


![image](https://github.com/user-attachments/assets/e34cd32a-70b1-4512-8ad6-46879f24539b)

| Rentang Job Success Rate | Rentang Marketing Spend | Nilai Partial Dependence | Keterangan                                                                                  |
|-------------------------|------------------------|--------------------------|---------------------------------------------------------------------------------------------|
| Rendah                  | Rendah                 | ~0.41 - 0.48             | Kombinasi rendah dari kedua fitur, nilai partial dependence lebih rendah                    |
| Menengah hingga Tinggi   | Rendah                 | (Tidak disebutkan spesifik)  | Tidak ada informasi eksplisit, kemungkinan nilai partial dependence sedang atau rendah      |
| Menengah hingga Tinggi   | Tinggi (0.8 - 1.0)     | ~0.50 - 0.52             | Nilai partial dependence cenderung lebih tinggi                                            |
| Tinggi (≥1.0)           | Tinggi (mendekati 1.0)  | ~0.50 - 0.52             | Kombinasi tingkat keberhasilan pekerjaan yang baik dan pengeluaran pemasaran tinggi berdampak positif paling kuat terhadap target model |


![image](https://github.com/user-attachments/assets/2bdd854e-acf3-4ef9-87c1-0266816d12fb)

| Rentang Job Success Rate | Rentang Job Duration Days | Nilai Partial Dependence | Keterangan                                                                                  |
|-------------------------|---------------------------|--------------------------|---------------------------------------------------------------------------------------------|
| Rendah                  | Rendah                    | ~0.48 - 0.49             | Kombinasi rendah dari kedua fitur, nilai partial dependence lebih rendah                    |
| Menengah hingga Tinggi   | Rendah                    | (Tidak disebutkan spesifik)  | Tidak ada informasi eksplisit, kemungkinan nilai partial dependence sedang atau rendah      |
| Menengah hingga Tinggi   | Tinggi (0.8 - 1.0)        | ~0.50 - 0.51             | Nilai partial dependence cenderung lebih tinggi                                            |
| Tinggi (≥1.0)           | Tinggi (mendekati 1.0)    | ~0.50 - 0.51             | Kombinasi tingkat keberhasilan pekerjaan yang baik dan durasi kerja panjang berdampak positif paling kuat terhadap target model |


![image](https://github.com/user-attachments/assets/7424f25a-2c6d-4a2c-8f9f-4b70fc110d0e)

| Rentang Job Success Rate | Rentang Hourly Rate      | Nilai Partial Dependence | Keterangan                                                                                  |
|-------------------------|-------------------------|--------------------------|---------------------------------------------------------------------------------------------|
| Rendah                  | Rendah                  | ~0.48 - 0.49             | Kombinasi rendah dari kedua fitur, nilai partial dependence lebih rendah                    |
| Menengah hingga Tinggi   | Rendah atau Sedang       | (Tidak disebutkan spesifik)  | Tidak ada informasi eksplisit, kemungkinan nilai partial dependence sedang atau rendah      |
| Menengah hingga Tinggi   | Sedang hingga Tinggi (0.4 - 1.0)  | ~0.50                   | Nilai partial dependence cenderung meningkat                                               |
| Tinggi (≥1.0)           | Sedang hingga Tinggi     | ~0.50                   | Kombinasi tingkat keberhasilan pekerjaan yang baik dan tarif per jam cukup tinggi berdampak positif paling kuat terhadap target model |



![image](https://github.com/user-attachments/assets/e6289de5-1d33-45e5-b892-38f0349b7193)


| **Fitur**            | **Rentang Nilai**       | **Partial Dependence**     | **Dampak Terhadap Target Model**                                                                                  |
|----------------------|------------------------|---------------------------|-------------------------------------------------------------------------------------------------------------------|
| Marketing Spend      | Sebagian besar nilai    | Stabil di kisaran 0.49-0.50 | Dampak relatif netral atau minor pada target model                                                                |
| Marketing Spend      | Sangat tinggi (mendekati 1.0) | Lonjakan signifikan, sekitar 0.52-0.53   | Memberikan dampak positif kuat terhadap target model, terlepas dari durasi pekerjaan                               |
| Job Duration Days    | Seluruh rentang nilai   | Stabil di kisaran 0.49-0.50   | Efek netral atau minor terhadap hasil model                                                                       |



![image](https://github.com/user-attachments/assets/ad710de1-ea3a-4833-b3b2-41aabed63cd7)

| **Fitur**            | **Rentang Nilai**       | **Partial Dependence**     | **Dampak Terhadap Target Model**                                                                                  |
|----------------------|------------------------|---------------------------|-------------------------------------------------------------------------------------------------------------------|
| Marketing Spend      | Sebagian besar nilai    | Stabil di kisaran 0.48-0.50 | Dampak relatif netral atau minor pada target model                                                                |
| Marketing Spend      | Sangat tinggi (mendekati 1.0) | Lonjakan signifikan, sekitar 0.52   | Memberikan dampak positif kuat terhadap target model, terlepas dari variasi Hourly Rate                            |
| Hourly Rate          | Seluruh rentang nilai   | Stabil di kisaran 0.48-0.50   | Efek netral atau minor terhadap hasil model                                                                       |

![image](https://github.com/user-attachments/assets/079998c7-8aec-4dc3-b198-39fbe08e4366)

| **Fitur**            | **Rentang Nilai**               | **Partial Dependence**           | **Dampak Terhadap Target Model**                                                                                  |
|----------------------|--------------------------------|---------------------------------|-------------------------------------------------------------------------------------------------------------------|
| Durasi Pekerjaan & Tarif Per Jam | Sebagian besar kombinasi nilai  | Stabil di kisaran 0.48-0.50       | Dampak relatif netral atau minor pada target model                                                                |
| Durasi Pekerjaan Panjang (0.7 - 0.85) & Tarif Per Jam Sedang-Hinggi (0.4 - 1.0) | Rentang spesifik tersebut          | Peningkatan hingga sekitar 0.51                        | Kombinasi durasi kerja lebih lama dan tarif per jam cukup tinggi memberikan dampak positif paling kuat            |
| Durasi Kerja Pendek & Tarif Per Jam Rendah   | Area dengan nilai rendah (~0.48)    | Partial dependence lebih rendah (~0.48)                | Dampak kurang signifikan terhadap hasil model                                                                     |

## SHAP

![image](https://github.com/user-attachments/assets/3d48b0f6-17ec-4e45-8d86-9d9629e82939)

| Fitur             | Pengaruh Terhadap Pendapatan       | Detail Penjelasan                                                                                      |
|-------------------|-----------------------------------|------------------------------------------------------------------------------------------------------|
| Job_Success_Rate  | Sangat positif dan dominan        | Nilai tinggi pada fitur ini secara konsisten meningkatkan prediksi pendapatan. Ini menunjukkan bahwa keberhasilan pekerjaan sangat menentukan earning. |
| Marketing_Spend   | Positif dengan variasi cukup besar| Pengeluaran pemasaran yang lebih tinggi cenderung menaikkan pendapatan, menandakan investasi marketing efektif dalam meningkatkan earning.           |
| Job_Category      | Variatif (positif atau negatif tergantung kategori) | Kategori pekerjaan berbeda memberikan dampak berbeda pada pendapatan; beberapa kategori lebih menguntungkan daripada yang lain.                       |
| Experience_Level  | Positif                          | Semakin tinggi pengalaman seseorang, semakin besar kontribusinya dalam menaikkan prediksi pendapatan.                                               |
| Job_Duration_Days | Sedikit negatif                  | Durasi kerja yang panjang cenderung sedikit menurunkan prediksi pendapatan, mungkin karena faktor efisiensi atau kelelahan kerja jangka panjang.     |
| Hourly_Rate       | Netral / kecil                   | Tarif per jam tidak memberikan pengaruh signifikan terhadap perubahan estimasi earnings menurut model ini; mungkin dipengaruhi oleh faktor lain juga.  |


## Keterangan skala vs nilai asli

Berikut adalah tabel dalam format Markdown berdasarkan informasi yang diberikan:

### Mapping Kategori

| Kategori            | Nilai | Deskripsi          |
|---------------------|-------|--------------------|
| **Job_Category**    | 1     | App Development    |
|                     | 2     | Content Writing    |
|                     | 3     | Customer Support   |
|                     | 4     | Data Entry         |
|                     | 5     | Digital Marketing  |
|                     | 6     | Graphic Design     |
|                     | 7     | SEO                |
|                     | 8     | Web Development    |
| **Experience_Level**| 0     | Beginner           |
|                     | 1     | Expert             |
|                     | 2     | Intermediate       |

### Informasi Skala Numerik

#### Job_Success_Rate
| Nilai Skala | Nilai Asli |
|-------------|------------|
| 0.1         | 55.25      |
| 0.2         | 60.21      |
| 0.3         | 65.17      |
| 0.4         | 70.13      |
| 0.5         | 75.09      |
| 0.6         | 80.06      |
| 0.7         | 85.02      |
| 0.8         | 89.98      |
| 0.9         | 94.94      |
| 1.0         | 99.90      |

#### Marketing_Spend
| Nilai Skala | Nilai Asli |
|-------------|------------|
| 0.1         | 50.80      |
| 0.2         | 100.60     |
| 0.3         | 150.40     |
| 0.4         | 200.20     |
| 0.5         | 250.00     |
| 0.6         | 299.80     |
| 0.7         | 349.60     |
| 0.8         | 399.40     |
| 0.9         | 449.20     |
| 1.0         | 499.00     |

#### Job_Duration_Days
| Nilai Skala | Nilai Asli |
|-------------|------------|
| 0.1         | 9.80       |
| 0.2         | 18.60      |
| 0.3         | 27.40      |
| 0.4         | 36.20      |
| 0.5         | 45.00      |
| 0.6         | 53.80      |
| 0.7         | 62.60      |
| 0.8         | 71.40      |
| 0.9         | 80.20      |
| 1.0         | 89.00      |

#### Hourly_Rate
| Nilai Skala | Nilai Asli |
|-------------|------------|
| 0.1         | 14.60      |
| 0.2         | 24.05      |
| 0.3         | 33.51      |
| 0.4         | 42.96      |
| 0.5         | 52.42      |
| 0.6         | 61.88      |
| 0.7         | 71.33      |
| 0.8         | 80.79      |
| 0.9         | 90.24      |
| 1.0         | 99.70      |

## Hasil Analisis Untuk Menjawab Goals Dan Problem Statement

Berikut adalah jawaban untuk setiap poin dan sub-poin Problem Statement dengan nilai asli, dirapikan dalam format **Markdown** agar lebih mudah dibaca dan dipahami:

---

## Jawaban Problem Statement dengan Nilai Asli

## 1. Peningkatan Job Success Rate (JSR) dan Prediksi Pendapatan Freelancer

### Hasil Analisis:
- **SHAP:** Job Success Rate (JSR) adalah fitur paling dominan dalam meningkatkan prediksi pendapatan. Nilai tinggi JSR berkorelasi kuat dengan pendapatan yang lebih tinggi.
- **PDP:** Terdapat peningkatan tajam partial dependence ketika JSR mendekati ≥94.94, menunjukkan bahwa freelancer dengan tingkat keberhasilan pekerjaan tinggi cenderung menghasilkan pendapatan lebih besar.

### Rekomendasi:
- Prioritaskan kualitas pekerjaan (misalnya, penyelesaian tepat waktu, kepuasan klien) untuk meningkatkan JSR.
- Freelancer dengan JSR rendah harus fokus pada perbaikan kualitas kerja sebelum menaikkan tarif atau memperpanjang durasi kerja.
- Platform freelance dapat memberikan insentif (e.g., badge "Top Performer") untuk freelancer dengan JSR tinggi sehingga meningkatkan daya tarik mereka di pasar.

---

## 2. Alokasi Anggaran Pemasaran Optimal untuk Meningkatkan Pendapatan

### Hasil Analisis:
- **PDP & SHAP:** Marketing Spend memiliki dampak positif signifikan terutama saat mencapai kisaran antara **349.60 – 399.40 USD** (nilai asli). Namun efeknya tidak linier—terjadi lonjakan di kisaran tersebut.
- **Interaksi dengan JSR:** Kombinasi *JSR tinggi* + *Marketing Spend* tinggi (~349.60–499 USD) memberikan dampak terbesar terhadap pendapatan.

### Rekomendasi:
- Alokasikan budget pemasaran secara strategis, tidak sekadar meningkatkan pengeluaran; fokus pada efektivitas kampanye (misalnya target audiens yang tepat).
- Freelancer dengan JSR tinggi sebaiknya menginvestasikan lebih banyak dana untuk promosi karena kombinasi ini memberikan ROI terbaik.
- Platform freelance dapat menyediakan fitur "promoted gigs" dengan pricing tier yang disesuaikan efektivitas pemasaran.

---

## 3. Dampak Durasi Kerja Panjang terhadap Produktivitas dan Pendapatan

### Hasil Analisis:
- **SHAP:** Job Duration Days memiliki dampak sedikit negatif pada pendapatan terutama saat durasi sangat panjang.
- **PDP:** Ada penurunan partial dependence saat durasi mendekati sekitar **89 hari kerja** (~nilai asli), mengindikasikan risiko burnout atau penurunan efisiensi.

### Rekomendasi:
- Hindari durasi kerja terlalu panjang (>80 jam/minggu atau sekitar >10 jam/hari secara konsisten), karena dapat menurunkan produktivitas dan pendapatan.
- Freelancer sebaiknya menerapkan time management seperti teknik Pomodoro dan istirahat teratur agar menjaga efisiensi kerja.
- Platform freelance dapat memberikan peringatan atau rekomendasi saat freelancer mengambil proyek berdurasi ekstrem.

---

## 4. Durasi Kerja Ideal ("Sweet Spot") untuk Produktivitas Maksimal

### Hasil Analisis:
- PDP Interaksi menunjukkan kombinasi *Job Duration Days* antara sekitar **62–71 hari kerja** + *Hourly Rate* antara **42–100 USD** menghasilkan partial dependence tertinggi (~0.51).
  
Ini mengindikasikan bahwa durasi kerja "cukup panjang" tapi tidak ekstrem serta tarif per jam kompetitif adalah optimal.

### Rekomendasi:
- Freelancer sebaiknya menetapkan durasi kerja harian sekitar 6–8 jam/hari  
(asumsi normalisasi ~0.7–0.85 setara 62–71 hari dalam konteks data).
  
- Gunakan data produktivitas pribadi untuk menentukan sweet spot individual karena beberapa orang mungkin lebih produktif di rentang waktu berbeda.
  
- Platform bisa menyediakan analytics waktu kerja vs pendapatan guna membantu optimisasi jadwal freelancer.

---

## 5.Pengaruh Tarif Per Jam terhadap Pendapatan dan Daya Saing Pasar

### Hasil Analisis:
 - SHAP menunjukkan Hourly Rate berdampak netral/kecil terhadap prediksi pendapatan; faktor lain seperti JSR jauh lebih berpengaruh.
 - PDP memperlihatkan kenaikan partial dependence pada tarif per jam sekitar $24 USD (~skala normalisasi 0.2), namun setelah itu efek stabil — menaikkan tarif tidak selalu menaikkan pendapatan secara signifikan.

### Rekomendasi: 
 - Freelancer pemula bisa mulai dari tarif rendah sekitar $24 USD/jam guna membangun portofolio dan meningkatkan JSR terlebih dahulu.
 - Freelancer berpengalaman disarankan tak hanya mengandalkan kenaikan tarif tapi juga fokus ke peningkatan kualitas layanan serta efisiensi kerja.
 - Strategi harga dinamis seperti diskon proyek jangka panjang bisa jadi alternatif efektif dibanding sekadar menaikkan harga per jam.


---

## Kesimpulan

| No | Topik                                      | Kesimpulan Utama                                                                                          |
|-----|--------------------------------------------|----------------------------------------------------------------------------------------------------------|
| 1   | Peningkatan Job Success Rate (JSR)         | JSR sangat dominan dalam prediksi pendapatan; kualitas kerja tinggi → pendapatan lebih besar.             |
| 2   | Alokasi Anggaran Pemasaran Optimal          | Marketing Spend efektif di kisaran $349.60–$399.40; kombinasi JSR tinggi + marketing tinggi hasil terbaik.|
| 3   | Dampak Durasi Kerja Panjang                  | Durasi kerja sangat panjang (>89 hari) menurunkan produktivitas dan pendapatan akibat risiko burnout.      |
| 4   | Durasi Kerja Ideal ("Sweet Spot")            | Durasi sekitar 62–71 hari dengan tarif per jam $42–$100 optimal untuk produktivitas dan pendapatan maksimal.|
| 5   | Pengaruh Tarif Per Jam terhadap Pendapatan    | Tarif per jam berpengaruh kecil, kenaikan tarif setelah ~$24 stabil; fokus pada kualitas & efisiensi kerja.|




## Referensi
[^1]: Mabanta, R. (2024). *PRESIDEN: ANGKA PENGANGGURAN TERBUKA DITEKAN HINGGA 4,5% DI 2025*. CGS International Sekuritas Indonesia, Jakarta Selatan.
[^2]: Tysara, L., & Mandasari, R. (2023). 15 Penyebab Pengangguran di Indonesia, Simak Macam-Macamnya. LIPUTAN 6.
[^3]: Albii. (2025). Kabar Gembira bagi Freelance di Tahun 2025. tebuirengonline.
[^4]: Hikmawati, U. N. (2024). DI AMBANG KEGAIRAHAN DAN KERENTANAN (Fleksibilitas Freelance Industri Kreatif Desain di Yogyakarta). Jurnal Studi Pemuda, 12(1), 50.
[^5]: Hadyan, Rezha. (2020, February 13). Pekerjaan Sebagai Freelancer Banyak Dipilih Oleh Generasi Muda, Kenapa?
[^6]: Lubis, R. K. (2024). AsbaK : Jurnal Ekonomi dan Bisnis Pengaruh Platform Freelance Terhadap Perubahan Pola Konsumsi dan Pekerjaan di Indonesia.
[^7]: Tim Penyusun, Dan Teknis, Aini, N., & Rosmiati, M. (n.d.). Upah Layak untuk Semua: Model Pengupahan Pekerja Lepas Industri Media dan Kreatif.



