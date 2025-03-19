# Laporan Proyek Machine Learning Predictive Analytics - Ibrahim Akbar Arsanata
## Domain Proyek
  Akhir akhir ini banyak sekali di sosial media atau dari orang-orang sekitar saya yang mengeluhkan betapa susahnya mencari pekerjaan di Indonesia. Pada saat ini,tercatat sebanyak 7,2 juta orang pada Februari 2024 [^1]. Hal ini disebabkan oleh berbagai macam faktor, salah satunya adalah terdapat ketidaksesuaian antara jumlah pencari kerja dan jumlah lapangan kerja yang tersedia. Ini menciptakan persaingan yang sangat ketat di antara pencari kerja, terutama di kalangan lulusan baru [^2]. Oleh karena itu, saat ini kebanyakan dari mereka ingin menjadi freelancer dapat menjangkau klien di seluruh dunia. Ini membuka peluang kerja yang lebih luas tanpa batasan geografis, memungkinkan individu untuk mendapatkan penghasilan dari berbagai sumber[^3]. Hal ini dibuktikan oleh Ulfah Nur Hikmawati dalam Jurnal Penelitiannya yang  menunjukkan bahwa jumlah freelancer di Indonesia mengalami peningkatan yang signifikan, dengan Badan Pusat Statistik (BPS) mencatat sekitar 33,34 juta orang memilih bekerja sebagai freelancer pada Agustus 2020, meningkat 4,32 juta orang dari tahun sebelumnya. Tren ini terus berlanjut hingga 2025, dengan banyak generasi muda beralih ke pekerjaan freelance karena fleksibilitas dan otonomi yang ditawarkan [^4].  
  Namun meskipun begitu, freelancer sering kali menghadapi persaingan yang ketat dan tekanan untuk menerima tawaran pekerjaan dengan upah yang lebih rendah, sehingga mengurangi daya tawar mereka. Tak hanya itu mencari dan mempertahankan client merupakan tantangan terbesar bagi para freelancer[^5]. Tak hanya itu tantangan utama lain bagi freelancer pemula, termasuk kesulitan dalam menetapkan harga jasa yang kompetitif. Ditekankan bahwa menetapkan harga terlalu rendah dapat mengurangi nilai pekerjaan, sementara harga yang terlalu tinggi dapat membuat klien ragu. Riset pasar menjadi penting untuk menemukan tarif yang sesuai di platform freelance seperti Upwork dan Fiverr[^6]. Selain itu para freelancer juga menghadapi tantangan lain yaitu keraguan mengenai tingkat keberhasilan pekerjaan mereka. Freelancer sering kali merasa kurang dihargai dan mengalami ketidakpastian dalam hubungan dengan klien, yang dapat mempengaruhi kepercayaan diri mereka dalam menyelesaikan proyek dengan baik[^7].
  Oleh karena itu, di sini saya akan melakukan analisis untuk menyelesaikan masalah-masalah yang dihadapi oleh freelancer, seperti tantangan untuk mencari client, job succes rate, serta tantangan dalam menetapkan harga jasa yang kompetitif, harus diselesaikan. Penting untuk memahami bahwa keberhasilan seorang freelancer tidak hanya bergantung pada keterampilan teknis, tetapi juga pada kemampuan mereka untuk menavigasi pasar yang kompetitif. Dengan melakukan riset yang mendalam, freelancer dapat menemukan tarif yang sesuai dan meningkatkan daya tawar mereka. Selain itu, membangun hubungan yang kuat dengan klien dan meningkatkan kepercayaan diri dalam menyelesaikan proyek dapat membantu mengurangi ketidakpastian dan meningkatkan kepuasan kerja. Melalui analisis ini, saya akan mengidentifikasi strategi yang dapat diterapkan untuk mengatasi tantangan-tantangan tersebut dan menciptakan lingkungan kerja yang lebih mendukung bagi para freelancer.

Business Understanding
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
Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai data yang Anda gunakan dalam proyek. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: UCI Machine Learning Repository.

Selanjutnya uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:

Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
cuisine : merupakan jenis masakan yang disajikan pada restoran.
dst
Rubrik/Kriteria Tambahan (Opsional):

Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.
Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

Rubrik/Kriteria Tambahan (Opsional):

Menjelaskan proses data preparation yang dilakukan
Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.
Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

Rubrik/Kriteria Tambahan (Opsional):

Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. Jelaskan proses improvement yang dilakukan.
Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. Jelaskan mengapa memilih model tersebut sebagai model terbaik.
Evaluation
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
