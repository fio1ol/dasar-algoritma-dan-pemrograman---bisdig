# dasar-algoritma-dan-pemrograman---bisdig
nama: fio lola karmila, kelas: 2a, nim: 24110310027, prodi: bisnis digital, matkul: dasar algoritma dan pemrograman, dosen: Ahmad Roihan s. kom., mti. 
1. Fungsi rekursif
Fungsi factorial(n) adalah fungsi rekursif yang digunakan untuk menghitung faktorial dari sebuah bilangan bulat n. Cara Kerja Rekursi dalam Program:
Fungsi akan terus memanggil dirinya sendiri dengan nilai n - 1.
Proses ini akan berhenti saat mencapai kondisi dasar yaitu n == 0.
Saat n == 0, fungsi mengembalikan nilai 1, lalu hasil perkalian mundur dihitung kembali sampai ke nilai awal.
Manfaat Penggunaan Fungsi:
- Mempermudah pemahaman kode karena logika terpisah dalam fungsi.
- Kode lebih ringkas dan efisien, tinggal panggil factorial(n) kapan pun dibutuhkan.
- mendukung pemrograman modular dan DRY (Don’t Repeat Yourself).
- Mudah di-debug dan diuji, karena fungsi bisa diuji sendiri tanpa perlu program lengkap.
Sebagai catatan:
- try-except digunakan biar program nggak error kalau user salah input.
- Ada pengecekan supaya angka negatif nggak diproses (karena faktorial cuma buat angka >= 0).
- Output-nya akan langsung muncul setelah input dimasukkan.

2. berikut langkah langkah algoritmanya dari sistem sederhana:
- Memulai program
- Meminta pengguna untuk memasukkan harga dari tiga barang
- Menyimpan ketiga harga tersebut ke dalam variabel
- Menjumlahkan ketiga harga tersebut untuk mendapatkan total pembayaran
- Menampilkan hasil total pembayaran ke layar.

3. peran tipe data dan operatornya:
> Tipe Data float
Digunakan untuk menyimpan nilai-nilai mata pelajaran yang bisa berupa angka desimal (misalnya 75.5). Ini penting supaya perhitungan rata-rata lebih akurat.
> Operator Aritmatika (+ dan /)
Operator + digunakan untuk menjumlahkan nilai ketiga mata pelajaran. Operator / digunakan untuk membagi jumlah nilai dengan 3 untuk mendapatkan rata-rata.
> Operator Perbandingan (>)
Digunakan untuk membandingkan rata-rata dengan nilai batas kelulusan (75). Jika rata-rata lebih besar dari 75, maka siswa dinyatakan lulus.

4. penggunaan array dan pengulangannya
>Perulangan (for loop):
Digunakan untuk meminta input nilai dari masing-masing siswa secara berulang sebanyak 5 kali. Ini menghindari penulisan input manual satu per satu.
>Array (List di Python):
Digunakan untuk menyimpan nilai-nilai siswa yang dimasukkan secara dinamis. List memungkinkan kita menyimpan beberapa data dalam satu variabel dan mengaksesnya berdasarkan indeks.
>Fungsi max() dan index():
max() digunakan untuk mencari nilai tertinggi dalam list. index() untuk mengetahui posisi siswa yang mendapat nilai tertinggi.

5. berikut penjelasan struktur kontrol percabangan:
Percabangan if-else digunakan untuk memeriksa kondisi apakah total belanja pelanggan melebihi Rp 500.000. Jika kondisi if terpenuhi (total belanja > 500.000), maka pelanggan mendapatkan diskon 10% dari total belanja. Jika kondisi if tidak terpenuhi, maka diskon yang diberikan adalah 0. Percabangan ini penting agar program bisa mengambil keputusan berbeda sesuai dengan kondisi yang ada.
