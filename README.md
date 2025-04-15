# Laporan Proyek Machine Learning Predictive Analytics - Ibrahim Akbar Arsanata

## Domain Proyek

Akhir-akhir ini, banyak sekali di sosial media atau dari orang-orang sekitar saya yang mengeluhkan betapa susahnya mencari pekerjaan di Indonesia. Pada saat ini, tercatat sebanyak **7,2 juta orang** pada Februari 2024 [^1]. Hal ini disebabkan oleh berbagai macam faktor, salah satunya adalah terdapat ketidaksesuaian antara jumlah pencari kerja dan jumlah lapangan kerja yang tersedia. Ini menciptakan persaingan yang sangat ketat di antara pencari kerja, terutama di kalangan lulusan baru [^2]. 

Oleh karena itu, saat ini kebanyakan dari mereka ingin menjadi freelancer untuk dapat menjangkau klien di seluruh dunia. Ini membuka peluang kerja yang lebih luas tanpa batasan geografis, memungkinkan individu untuk mendapatkan penghasilan dari berbagai sumber [^3]. Hal ini dibuktikan oleh Ulfah Nur Hikmawati dalam Jurnal Penelitiannya yang menunjukkan bahwa jumlah freelancer di Indonesia mengalami peningkatan yang signifikan, dengan Badan Pusat Statistik (BPS) mencatat sekitar **33,34 juta orang** memilih bekerja sebagai freelancer pada Agustus 2020, meningkat **4,32 juta orang** dari tahun sebelumnya. Tren ini terus berlanjut hingga 2025, dengan banyak generasi muda beralih ke pekerjaan freelance karena fleksibilitas dan otonomi yang ditawarkan [^4].  

Namun, meskipun begitu, freelancer sering kali menghadapi persaingan yang ketat dan tekanan untuk menerima tawaran pekerjaan dengan upah yang lebih rendah, sehingga mengurangi daya tawar mereka. Tak hanya itu, mencari dan mempertahankan klien merupakan tantangan terbesar bagi para freelancer [^5]. Tantangan utama lain bagi freelancer pemula termasuk kesulitan dalam menetapkan harga jasa yang kompetitif. Ditekankan bahwa menetapkan harga terlalu rendah dapat mengurangi nilai pekerjaan, sementara harga yang terlalu tinggi dapat membuat klien ragu. Riset pasar menjadi penting untuk menemukan tarif yang sesuai di platform freelance seperti Upwork dan Fiverr [^6]. 

Selain itu, para freelancer juga menghadapi tantangan lain, yaitu keraguan mengenai tingkat keberhasilan pekerjaan mereka. Freelancer sering kali merasa kurang dihargai dan mengalami ketidakpastian dalam hubungan dengan klien, yang dapat mempengaruhi kepercayaan diri mereka dalam menyelesaikan proyek dengan baik [^7].


## Business Understanding

Meskipun menawarkan fleksibilitas dan peluang yang lebih luas, para freelancer di Indonesia menghadapi berbagai tantangan yang telah dijelaskan pada paragraf diatas. Penting untuk memahami bahwa keberhasilan seorang freelancer tidak hanya bergantung pada keterampilan teknis, tetapi juga pada kemampuan mereka untuk menavigasi pasar yang kompetitif. Dengan melakukan riset yang mendalam, freelancer dapat menemukan tarif yang sesuai dan meningkatkan daya tawar mereka. Selain itu, membangun hubungan yang kuat dengan klien dan meningkatkan kepercayaan diri dalam menyelesaikan proyek dapat membantu mengurangi ketidakpastian dan meningkatkan kepuasan kerja. Melalui analisis ini, saya akan mengidentifikasi strategi yang dapat diterapkan untuk mengatasi tantangan-tantangan tersebut dan menciptakan lingkungan kerja yang lebih mendukung bagi para freelancer.

### Problem Statements

1. **Pernyataan Masalah 1: Tantangan dalam mencari dan mempertahankan klien.**
   - Freelancer sering kali menghadapi kesulitan dalam mendapatkan klien baru dan mempertahankan hubungan dengan klien yang ada, yang dapat mempengaruhi pendapatan mereka.

2. **Pernyataan Masalah 2: Kesulitan dalam menetapkan harga jasa yang kompetitif.**
   - Freelancer pemula sering kali bingung dalam menentukan tarif yang sesuai, di mana harga yang terlalu rendah dapat mengurangi nilai pekerjaan, sementara harga yang terlalu tinggi dapat membuat klien ragu.

3. **Pernyataan Masalah 3: Keraguan mengenai tingkat keberhasilan pekerjaan.**
   - Freelancer sering merasa kurang dihargai dan mengalami ketidakpastian dalam hubungan dengan klien, yang dapat mempengaruhi kepercayaan diri mereka dalam menyelesaikan proyek.

### Goals

1. **Jawaban Pernyataan Masalah 1:**
   - Untuk mengatasi tantangan dalam mencari dan mempertahankan klien, akan dilakukan analisis mendalam terhadap beberapa faktor kunci. Pertama, mengidentifikasi posisi yang menunjukkan permintaan tinggi di pasar. Kedua, penting untuk memahami pengalaman dan keterampilan yang paling dipercaya serta diminati oleh klien. Selain itu, mengetahui wilayah geografis dengan permintaan tinggi dapat memberikan keuntungan kompetitif. Terakhir, memahami metode pembayaran yang disukai oleh klien akan membantu freelancer merancang penawaran yang lebih menarik dan sesuai dengan kebutuhan klien. Dengan pendekatan strategis ini, freelancer dapat meningkatkan peluang mereka untuk mendapatkan klien baru dan membangun hubungan jangka panjang yang saling menguntungkan.

2. **Jawaban Pernyataan Masalah 2:**
   - Untuk mengatasi tantangan dari menentukan tarif yang sesuai, akan dilakukan analisis terhadap faktor faktor yang 

3. **Jawaban Pernyataan Masalah 3:**
   - Meningkatkan kepercayaan diri freelancer dengan memberikan alat dan sumber daya untuk menilai dan meningkatkan tingkat keberhasilan proyek mereka.

### Solution Statements

1. **Solution Statement 1:**
   - Menerapkan model prediktif untuk mengidentifikasi peluang klien yang potensial berdasarkan profil dan preferensi freelancer, sehingga meningkatkan peluang mendapatkan proyek.

2. **Solution Statement 2:**
   - Melakukan hyperparameter tuning pada model yang digunakan untuk meningkatkan akurasi prediksi job success rate, sehingga freelancer dapat lebih percaya diri dalam menyelesaikan proyek.

3. **Solution Statement 3:**
   - Mengembangkan dashboard interaktif yang memungkinkan freelancer untuk memantau kinerja mereka, termasuk tingkat keberhasilan proyek dan umpan balik dari klien, untuk meningkatkan hubungan dan kepuasan kerja.

Dengan pendekatan ini, diharapkan dapat membantu freelancer mengatasi tantangan yang mereka hadapi dan menciptakan lingkungan kerja yang lebih mendukung.

Pada bagian ini, kamu perlu menjelaskan proses klarifikasi masalah.

Bagian laporan ini mencakup:

Problem Statements
Menjelaskan pernyataan masalah latar belakang:

Pernyataan Masalah 1
Pernyataan Masalah 2
Pernyataan Masalah n
Goals
Menjelaskan tujuan dari pernyataan masalah:

Jawaban pernyataan masalah 1
Jawaban pernyataan masalah 2
Jawaban pernyataan masalah n
Semua poin di atas harus diuraikan dengan jelas. Anda bebas menuliskan berapa pernyataan masalah dan juga goals yang diinginkan.

Rubrik/Kriteria Tambahan (Opsional):

Menambahkan bagian “Solution Statement” yang menguraikan cara untuk meraih goals. Bagian ini dibuat dengan ketentuan sebagai berikut:

Solution statements
Mengajukan 2 atau lebih solution statement. Misalnya, menggunakan dua atau lebih algoritma untuk mencapai solusi yang diinginkan atau melakukan improvement pada baseline model dengan hyperparameter tuning.
Solusi yang diberikan harus dapat terukur dengan metrik evaluasi.


## Data Understanding
Data yang saya gunakan merupakan data tentang seputar freelancer Dataset ini menyajikan informasi lengkap mengenai berbagai freelancer yang bekerja di platform-platform populer seperti Fiverr, PeoplePerHour, dan Upwork. Fokus utamanya meliputi profil dan karakteristik freelancer berdasarkan kategori pekerjaan, tingkat pengalaman, serta wilayah geografis klien yang mereka layani. Selain itu, dataset ini juga mencakup metode pembayaran yang digunakan, statistik performa seperti jumlah pekerjaan yang telah diselesaikan, penghasilan total dalam USD, dan tarif per jam yang ditetapkan oleh freelancer.  

Indikator kualitas kerja seperti tingkat keberhasilan pekerjaan dan rating dari klien turut disertakan, bersama dengan durasi pengerjaan proyek serta jenis kontrak yang digunakan, baik fixed price maupun hourly rate. Aspek bisnis tambahan seperti rehire rate dan biaya pemasaran juga diintegrasikan untuk memberikan gambaran lebih komprehensif. Tujuan utama dataset ini adalah untuk menganalisis performa freelancer di berbagai platform dengan mempertimbangkan faktor demografis dan ekonomi, sehingga dapat mengungkap pola kesuksesan dalam pasar freelancing global yang semakin kompetitif.

Sumber dataset ini saya ambil dari kaggle dengan link dataset berikut (https://www.kaggle.com/datasets/abderahmanchtebat/freelancer-earnings-bd) dengan rincian variable atau fitur pada datanya sebagai berikut:

Freelancer_ID : ID unik untuk setiap freelancer dalam dataset.
Job_Category : Kategori pekerjaan yang dilakukan freelancer, misalnya Web Development, App Development, Data Entry, Digital Marketing.
Platform : Platform freelance tempat pekerjaan dilakukan, seperti Fiverr, PeoplePerHour, Upwork.
Experience_Level : Tingkat pengalaman freelancer: Beginner (pemula), Intermediate (menengah), Expert (ahli).
Client_Region : Wilayah geografis klien yang mempekerjakan freelancer seperti Asia, Australia, UK, dll.
Payment_Method : Metode pembayaran yang digunakan oleh klien seperti Mobile Banking, Bank Transfer, Crypto.
Job_Completed : Jumlah pekerjaan atau proyek yang telah diselesaikan oleh freelancer.
Earnings_USD : Total penghasilan dalam USD dari semua pekerjaan yang telah diselesaikan.
Hourly_Rate : Tarif per jam kerja dalam USD dari freelancer tersebut.
Job_Success_Rate : Persentase keberhasilan proyek atau tingkat kepuasan terhadap hasil kerja (biasanya berdasarkan feedback/penilaian).
Client_Rating : Rating rata-rata dari klien terhadap kinerja freelancer pada skala tertentu (misal 1-5).
Job_Duration_Days : Durasi rata-rata penyelesaian proyek dalam hari.
Project_Type : Jenis kontrak/proyek: Fixed (harga tetap) atau Hourly (berdasarkan jam kerja).
Rehire_Rate : Persentase seberapa sering klien mengontrak ulang freelancer tersebut.
Marketing_Spend : Pengeluaran untuk pemasaran oleh freelancer untuk mendapatkan job.


![image](https://github.com/user-attachments/assets/02f518b2-0798-4b3d-af55-4b7c7b39189d)


Paragraf awal bagian ini menjelaskan informasi mengenai data yang Anda gunakan dalam proyek. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: UCI Machine Learning Repository.

Selanjutnya uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:

Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
cuisine : merupakan jenis masakan yang disajikan pada restoran.
dst
Rubrik/Kriteria Tambahan (Opsional):

Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.
## Data Preparation
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
