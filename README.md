# Computational-Intelligent
Program Aplikasi Genetik Algoritma dan Review Jurnal International
__________________________________________________________________

TOOLS
program aplikasi “Genetic Algorithm – Knapsack Problem”. Pada program terdiri dari 5 tombol utama dan 8 form untuk mengisi data input sebelum melakukan proses dan 3 memo yang digunakan untuk menampilkan hasil dan proses selama program berlangsung secara detail. Adapun masing-masing komponen dan fungsi detailnya:
1.	Tombol ; terdiri dari 5 tombol utama yaitu Reload, Hapus, Refresh, Tambah dan Mulai Proses. 
a.	Reload ; digunakan untuk memasukan data dari file *.txt (DataBarang.txt) ke dalam tabel program untuk dieksekusi
Note : Data pada file DataBarang.txt dapat ditambahkan secara manual. 
b.	Hapus ; digunakan untuk membersihkan data form secara keseluruhan apabila ingin melakukan pembatalan data input atau setelah menyelesaikan program
c.	Refresh ; digunakan untuk merefresh data yang ada menggunakan data default yang ada dalam program
d.	Tambah ; digunakan untuk menambahkan data dalam tabel data secara manual. Tombol ini digunakan ketika user sudah mengisi form Nama Barang, Berat dan Harga. 
e.	Mulai Proses ; digunakan untuk memulai proses Algoritma Genetik untuk menyelesaikan Knapsack Problem sesuai dengan inputan data barang, batasan kapasitas tampung, persentasi mutasi dan crossover, banyaknya populasi dan generasi yang diinginkan. 

2.	Form ; terdiri dari 8 form penting yang harus diisi oleh user sebelum menekan tombol proses. Pada form sendiri dibagi dalam 2 kategori yaitu : 
a.	Penginputan data barang, terdiri dari 3 form utama yang harus di input oleh user jika ingin menambahkan data barang baru pada tabel. Ketiga form dimaksud yaitu : Nama Barang, Berat Barang dan Harga Barang. Apabila salah satu dari ke-3 form tidak dilengkapi maka data barang tersebut tidak dapat disimpan dalam tabel. Untuk menyimpan data inputan dari user, maka selanjutnya user menekan tombol “Tambah”
b.	Penginputan Data Algoritma Genetik, terdiri dari 5 form utama yang wajib diisi oleh user sebelum menjalankan program dengan menekan tombol “Mulai Proses”, yaitu : 
•	Kapasitas Maksimal Tampung. Digunakan oleh user untuk menginput bobot maksimal daya tampung yang dijadikan sebagai batasan dalam memasukan barang dalam kantong 
•	Jumlah Populasi. User menentukan jumlah populasi yang akan dibentuk per generasinya
•	Jumlah Generasi. User menentukan jumlah generasi yang akan digunakan. Jumlah generasi dijadikan sebagai syarat berhenti pada program ini
•	Probabilitas Mutasi. User menentukan berapa persentase (%) mutasi yang dilakukan dalam proses mutasi untuk menghasilkan individu baru
•	Probabilitas Crossover. User menentukan berapa persentase (%) crossover yang akan dilakukan.

3.	Memo ; terbagi dalam 2 bagian utama dengan masing-masing fungsinya. Yaitu : 
a.	Memo Hasil, digunakan untuk manampilkan data barang-barang terpilih yang dapat dimasukan dalam media penampung. Memo ini terletak pada bagian kanan atas pada program. 
b.	Memo Proses, digunakan untuk menampilkan proses algoritma genetik dalam menentukan solusi knapsack problem. Adapun informasi-informasi yang termuat didalamnya yaitu : informasi Kromosom, Bobot masing-masing Kromosom, Nilai Fitness Kromosom, Kromosom Hasil Crossover, Kromosom Hasil Mutasi, Optimasi Kromosom per Generasi dan Optimasi Kromosom Terbaik untuk keseluruhan Generasi. 

CARA PENGGUNAAN 
Langkah pertama yang harus dilakukan oleh user untuk menjalankan program aplikasi “Genetic Algorithm – Knapsack Problem” adalah dengan membuka file “KnapsackProblem.exe”. Setelah muncul tampilan awal program, user dapat menginput data secara manual dengan memasukan data pada form barang dan menekan tombol “Tambah”, atau menginput data barang secara otomatis menggunakan tombol “Reload” atau “Refresh”. Sebelum memulai proses user harus menginput jumlah Maksimum kapasitas daya tampung, jumlah populasi, jumlah generasi, presentasi mutasi dan presentasi crossover yang akan dilakukan. Setelah semuanya sudah lengkap, maka user dapat menjalankan program dengan menekan tombol “Mulai Proses”. User selanjutnya menunggu hingga proses selesai maka pada program akan ditampilkan hasil barang-barang yang terpilih dan proses algoritma genetiknya. Lamanya proses bergantung pada banyaknya data inputan, jumlah populasi dan generasi yang digunakan, semakin banyak populasi, generasi ataupun data yang digunakan, maka untuk memproses hasil akan membutuhkan waktu yang lebih lama. 

OUTPUT
Hasil dari program aplikasi ini tidak bersifat tetap, dikarenakan proses random yang digunakan membuat hasil dari program ini sulit ditebak. Namun tentunya pada program akan memberikan solusi yang diinginkan. Apabila jumlah kapasitas yang diinputkan terlalu kecil dan dengan jumlah generasi yang digunakan juga sedikit maka kemungkinan solusi tidak ditemukan. 

