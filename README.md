# Strategy of Katla Game Using SMT
Katla adalah jenis permainan berbasis website yang dikembangkan oleh Fatih Khalifa pada awal tahun 2022. Tujuan utama dari permainan ini adalah untuk mengisi kotak kosong yang tersedia sehingga membentuk satu kata baku bahasa Indonesia (KBBI). Pada awal permainan, tersedia 6 x 5 kotak kosong yang harus diisi dengan huruf sesuai ejaan kata baku. Tidak ada aturan spesifik dalam jumlah penggunaan huruf, namun sistem dari permainan ini adalah hanya dapat dimainkan satu kali dalam sehari. Informasi yang didapatkan dari setiap tebakan kata menjadi sebuah tantangan tersendiri untuk menyelesaikan permainan. Terdapat 6 kesempatan tebakan kata baku sehingga pemilihan kata harus benar-benar diperhitungkan. Permainan Katla terbilang cukup baru sehingga masih sedikit ajuan strategi algoritma dalam penyelesaian permainan ini. Salah satu metode yang dapat digunakan dalam penyusunan strategi permainan ini adalah Satisfiability Modulo Theory (SMT). Data kata yang digunakan dalam project ini diperoleh melalui proses scraping pada laman website kbbi.co.id

Terdapat tiga strategi yang dilakukan pada project ini, meliputi:
1. Strategi Solver Murni
2. Strategi Optimalisasi Frekuensi Karakter
3. Strategi Dictinct Character 
