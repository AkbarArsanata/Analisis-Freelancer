# Laporan Proyek Machine Learning Predictive Analytics - Ibrahim Akbar Arsanata

---

# Domain Proyek

Akhir-akhir ini, banyak sekali di sosial media atau dari orang-orang sekitar saya yang mengeluhkan betapa susahnya mencari pekerjaan di Indonesia. Pada saat ini, tercatat sebanyak **7,2 juta orang** pada Februari 2024 [^1]. Hal ini disebabkan oleh berbagai macam faktor, salah satunya adalah terdapat ketidaksesuaian antara jumlah pencari kerja dan jumlah lapangan kerja yang tersedia. Ini menciptakan persaingan yang sangat ketat di antara pencari kerja, terutama di kalangan lulusan baru [^2]. 

Oleh karena itu, saat ini kebanyakan dari mereka ingin menjadi freelancer untuk dapat menjangkau klien di seluruh dunia. Ini membuka peluang kerja yang lebih luas tanpa batasan geografis, memungkinkan individu untuk mendapatkan penghasilan dari berbagai sumber [^3]. Hal ini dibuktikan oleh Ulfah Nur Hikmawati dalam Jurnal Penelitiannya yang menunjukkan bahwa jumlah freelancer di Indonesi a mengalami peningkatan yang signifikan, dengan Badan Pusat Statistik (BPS) mencatat sekitar **33,34 juta orang** memilih bekerja sebagai freelancer pada Agustus 2020, meningkat **4,32 juta orang** dari tahun sebelumnya. Tren ini terus berlanjut hingga 2025, dengan banyak generasi muda beralih ke pekerjaan freelance karena fleksibilitas dan otonomi yang ditawarkan [^4]. Survei menunjukkan mayoritas freelancer berasal dari generasi milenial dan Z yang mengutamakan fleksibilitas dan kesempatan menyalurkan kreativitas. Sebanyak 95 persen responden survei berencana menekuni pekerjaan freelance dalam jangka panjang, dengan 53 persen berencana melakukannya lebih dari 5 tahun [reza]. Dengan kata lain, saat ini banyak pekerja pemula (entry level) yang ingin berkarir sebagai freelancer. Namun, hal ini tidak mudah karena banyak faktor yang harus dipertimbangkan untuk sukses di dunia freelance. Berikut beberapa tantangan yang perlu diantisipasi:

freelancer  menghadapi  tantangan  ketidakstabilan  pendapatan  dan  minimnya  akses  terhadap jaminan sosial, banyak freelancer mengalami ketidakpastian terkait keberlanjutan karir mereka, terutama  dalam  menghadapi  persaingan  global  di  platform  digital.  Kekhawatiran  terhadap  kurangnya jaminan kesehatan dan pensiun menjadi tantangan yang memerlukan solusi kebijakan yang inovatif.[pengaruh platform freelance]. Untuk menemukan solusi tersebut perlu dilakukan analisis faktor faktor apa saja yang bisa meningkatkan pendapatan. Untuk meningkatkan pendapatan, perlu dianalisis faktor-faktor seperti Job Success Rate (JSR), yang menunjukkan keberhasilan penyelesaian pekerjaan. Jika JSR meningkat, pendapatan kemungkinan juga naik, meski jenis pekerjaan dan pengalaman turut memengaruhi. Selain itu, alokasi anggaran pemasaran yang tepat—melalui digital ads atau program referral—dapat meningkatkan efektivitas investasi promosi dan mendongkrak penghasilan. Durasi kerja panjang berpotensi menurunkan produktivitas akibat kelelahan, sehingga penting menemukan durasi kerja ideal agar efisiensi tetap maksimal tanpa burnout. Terakhir, tarif per jam harus ditetapkan dengan hati-hati karena kenaikan harga tidak selalu menaikkan pendapatan jika mengurangi jumlah klien. Analisis menyeluruh dari faktor-faktor ini dapat membantu freelancer meningkatkan stabilitas dan besaran penghasilan sekaligus mendorong kebijakan perlindungan sosial yang inovatif di sektor gig economy.



Namun, meskipun begitu, freelancer sering kali menghadapi persaingan yang ketat dan tekanan untuk menerima tawaran pekerjaan dengan upah yang lebih rendah, sehingga mengurangi daya tawar mereka. Tak hanya itu, mencari dan mempertahankan klien merupakan tantangan terbesar bagi para freelancer [^5]. Oleh karena itu akan dilakukan analisis juga mengenai pengaruh beriklan terhadap kesempatan mendapatkan client.

Tantangan utama lain bagi freelancer pemula termasuk kesulitan dalam menetapkan harga jasa yang kompetitif. Ditekankan bahwa menetapkan harga terlalu rendah dapat mengurangi nilai pekerjaan, sementara harga yang terlalu tinggi dapat membuat klien ragu. Riset pasar menjadi penting untuk menemukan tarif yang sesuai di platform freelance seperti Upwork dan Fiverr [^6]. 

Selain itu, para freelancer juga menghadapi tantangan lain, yaitu keraguan mengenai tingkat keberhasilan pekerjaan mereka. Freelancer sering kali merasa kurang dihargai dan mengalami ketidakpastian dalam hubungan dengan klien, yang dapat mempengaruhi kepercayaan diri mereka dalam menyelesaikan proyek dengan baik [^7].


# Business Understanding

---

Meskipun menawarkan fleksibilitas dan peluang yang lebih luas, para freelancer di Indonesia menghadapi berbagai tantangan yang telah dijelaskan pada paragraf diatas. Penting untuk memahami bahwa keberhasilan seorang freelancer tidak hanya bergantung pada keterampilan teknis, tetapi juga pada kemampuan mereka untuk menavigasi pasar yang kompetitif. Dengan melakukan riset yang mendalam, freelancer dapat menemukan tarif yang sesuai dan meningkatkan daya tawar mereka. Selain itu, membangun hubungan yang kuat dengan klien dan meningkatkan kepercayaan diri dalam menyelesaikan proyek dapat membantu mengurangi ketidakpastian dan meningkatkan kepuasan kerja. Melalui analisis ini, saya akan mengidentifikasi strategi yang dapat diterapkan untuk mengatasi tantangan-tantangan tersebut dan menciptakan lingkungan kerja yang lebih mendukung bagi para freelancer.

## Problem Statements

1. **Pernyataan Masalah 1: Apakah peningkatan Job Success Rate dapat secara konsisten menaikkan prediksi pendapatan?**
   -Job Success Rate (JSR) adalah metrik yang mengindikasikan seberapa sukses seorang freelancer dalam menyelesaikan pekerjaannya. Problem statement ini bertujuan untuk mengevaluasi apakah kenaikan JSR berbanding lurus dengan peningkatan pendapatan. Jika ditemukan korelasi positif, maka freelancer atau platform dapat fokus pada strategi peningkatan kualitas pekerjaan untuk meningkatkan pendapatan. Namun, perlu juga dikaji apakah faktor lain seperti jenis pekerjaan atau pengalaman turut memengaruhi hubungan ini.

2. **Pernyataan Masalah 2: Apakah alokasi pemasaran/promosi yang optimal dapat membuat investasi pemasaran lebih efektif dalam mendongkrak pendapatan?**
   -Investasi dalam pemasaran dan promosi sering kali memakan biaya besar, tetapi tidak selalu berdampak signifikan pada pendapatan. Problem statement ini mengeksplorasi bagaimana alokasi budget pemasaran yang tepat (misalnya: digital ads, referral program, atau SEO) dapat memaksimalkan ROI (Return on Investment). Analisis ini dapat membantu perusahaan atau freelancer dalam mengambil keputusan strategis untuk mengoptimalkan pengeluaran promosi.

3. **Pernyataan Masalah 3: Apakah durasi kerja panjang berdampak negatif signifikan terhadap produktivitas dan penurunan prediksi pendapatan?**
   -Bekerja dalam durasi panjang (overtime atau jam kerja ekstrem) sering dikaitkan dengan kelelahan (burnout) yang berpotensi menurunkan produktivitas. Problem ini menguji apakah terdapat titik di mana durasi kerja yang terlalu lama justru mengurangi efisiensi dan akhirnya menurunkan pendapatan. Temuan ini dapat menjadi acuan dalam manajemen waktu kerja untuk menjaga produktivitas optimal.

4. **Pernyataan Masalah 4: Apakah ada batasan durasi kerja ideal agar tidak menimbulkan penurunan efisiensi atau kelelahan bagi pekerja?**
   -Berhubungan dengan problem sebelumnya, problem ini mencari durasi kerja "sweet spot" di mana pekerja dapat mempertahankan produktivitas maksimal tanpa mengalami kelelahan berlebih. Analisis dapat melibatkan variabel seperti jam kerja/hari, istirahat, dan jenis pekerjaan. Hasilnya dapat digunakan untuk rekomendasi kebijakan kerja baik bagi freelancer maupun perusahaan.
   
5. **Penyataan Masalah 5: Apakah tarif per jam memiliki pengaruh signifikan terhadap perubahan estimasi pendapatan?**
   -Tarif per jam adalah faktor langsung dalam penghitungan pendapatan freelancer. Namun, problem ini mengevaluasi apakah menaikkan tarif per jam selalu meningkatkan pendapatan, atau justru berpotensi mengurangi jumlah klien karena harga terlalu tinggi. Analisis dapat mencakup elastisitas permintaan, tingkat persaingan, dan kualitas layanan untuk menentukan strategi penetapan harga optimal.

## Goals

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

Terlihat dari gambar diatas tidak terindikasi adanya missing value

## Duplicated Checking 

## Inconsistent Checking

## Outlier Checking
![image](https://github.com/user-attachments/assets/e3f4c3c1-15f2-4942-ba17-a321fb7a3ffd)

Terlihat dari gambar diatas tidak terindikasi adanya Outlier


## Korelasi

![image](https://github.com/user-attachments/assets/48c1083b-1fd1-49b1-8659-eeedc2ef019c)


Matriks korelasi ini menunjukkan hubungan linear antar variabel seperti Freelancer_ID, Job_Completed, Earnings_USD, Hourly_Rate, Job_Success_Rate, Client_Rating, Job_Duration_Days, Rehire_Rate, dan Marketing_Spend. Nilai korelasi berada dalam rentang -1 hingga 1 dengan warna merah menandakan korelasi positif dan biru untuk korelasi negatif.

Dari matriks terlihat bahwa sebagian besar nilai korelasi antar variabel sangat dekat dengan nol (baik positif maupun negatif), misalnya nilai-nilai seperti 0.01, -0.02, 0.03 yang menunjukkan hubungan yang sangat lemah atau hampir tidak ada hubungan linear antara variabel-variabel tersebut. Tidak ada pasangan variabel yang memiliki nilai korelasi tinggi (misalnya di atas 0.7 atau di bawah -0.7) yang biasanya menjadi indikasi adanya multikolinearitas.


Berdasarkan matriks korelasi ini dapat disimpulkan bahwa **tidak terdapat gejala multikolinearitas** signifikan antar variabel dalam dataset freelancer ini karena semua nilai korelasinya rendah dan tidak menunjukkan ketergantungan linier kuat satu sama lain.

Oleh karena itu, **tidak perlu dilakukan teknik reduksi dimensi seperti Principal Component Analysis (PCA)** untuk mengatasi masalah multikolinearitas pada data ini.

---


Paragraf awal bagian ini menjelaskan informasi mengenai data yang Anda gunakan dalam proyek. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: UCI Machine Learning Repository.

Selanjutnya uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:

Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
cuisine : merupakan jenis masakan yang disajikan pada restoran.
dst
Rubrik/Kriteria Tambahan (Opsional):

Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.
## Data Preparation

Data preparation merupakan tahapan penting dalam proses pengembangan model machine learning. Ini adalah tahap di mana kita melakukan proses transformasi pada data sehingga menjadi bentuk yang cocok untuk proses pemodelan. Dikarenakan pada submision kita diberi opsi untuk memilih salah satu dari 3 pilihan (Klasifikasi, Regresi, Time series dan forecasting) maka disini diputuskan untuk menggunakan metode Regresi untuk menyelesaikan semua permasalahan tersebut




Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

Rubrik/Kriteria Tambahan (Opsional):

Menjelaskan proses data preparation yang dilakukan
Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.
## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

Rubrik/Kriteria Tambahan (Opsional):

Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. Jelaskan proses improvement yang dilakukan.
Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. Jelaskan mengapa memilih model tersebut sebagai model terbaik.
## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik akurasi, precision, recall, dan F1 score. Jelaskan mengenai beberapa hal berikut:

Penjelasan mengenai metrik yang digunakan
Menjelaskan hasil proyek berdasarkan metrik evaluasi
Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

Rubrik/Kriteria Tambahan (Opsional):

Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.
---Ini adalah bagian akhir laporan---

Catatan:

Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor Dillinger, Github Guides: Mastering markdown, atau sumber lain di internet. Semangat!
Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.

## Referensi
[^1]: Mabanta, R. (2024). *PRESIDEN: ANGKA PENGANGGURAN TERBUKA DITEKAN HINGGA 4,5% DI 2025*. CGS International Sekuritas Indonesia, Jakarta Selatan.
[^2]: Tysara, L., & Mandasari, R. (2023). 15 Penyebab Pengangguran di Indonesia, Simak Macam-Macamnya. LIPUTAN 6.
[^3]: Albii. (2025). Kabar Gembira bagi Freelance di Tahun 2025. tebuirengonline.
[^4]: Hikmawati, U. N. (2024). DI AMBANG KEGAIRAHAN DAN KERENTANAN (Fleksibilitas Freelance Industri Kreatif Desain di Yogyakarta). Jurnal Studi Pemuda, 12(1), 50.
[^5]: Jurnal Pendidikan Ekonomi Undiksha, Masakazu, K., Sisdianto, E., Suwardika, G., & Nugroho, D. S. (2023). Peran Digital Freelancer Marketplace dan Media Sosial Terhadap Perkembangan Gig Economy Worker. Jurnal Pendidikan Ekonomi Undiksha, 15(1). 
[^6]: Tim Penyusun, Dan Teknis, Aini, N., & Rosmiati, M. (n.d.). Upah Layak untuk Semua: Model Pengupahan Pekerja Lepas Industri Media dan Kreatif.
[^7]: Amanda, A. (2024). KERENTANAN KERJA PADA PEKERJA HARIAN LEPAS DI INDUSTRI KREATIF INDONESIA. Journal Research of Management (JARMA), 5(2), 186-185.
