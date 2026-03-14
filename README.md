# PENJELASAN ARRAY
<img width="230" height="25" alt="image" src="https://github.com/user-attachments/assets/4c16ac15-d73b-493b-a4fc-0d8a6a326e20" />


baris kode ini digunakkan untuk medefinisikan sebuah array,list kosong([]) untuk menyimpan data nilai mahasiswa


<img width="684" height="137" alt="Screenshot 2026-03-10 142746" src="https://github.com/user-attachments/assets/2241bd4c-1b9d-4c69-b086-facbae561e64" />

1)barisan pertama (for) untuk melakukan perulangan (for i in range(10): ) melakukan perulangan berjalan selama 10 kali perulangan

2)barisan kedua digunakkan untuk menerima input nilai dari pengguna. Program meminta pengguna memasukkan nilai, kemudian program mengeluarkan pesan "masukkan nilai mahasiswa ke-{i+1}", dimana i+1 digunakan agar penomoran mahasiswa dimulai dari 1, nilai yang dimasukkan kemudian berubah nilainya dari bentuk teks menjadi bilangan bulat menggunakan fungsi int().

3)barisan ketiga digunakan untuk menambahkan nilai yang telah dimasukkan oleh pengguna ke dalam list nilai_mahasiswa. Fungsi append() digunakan untuk menambahkan nilai kedalam array.

<img width="1262" height="200" alt="image" src="https://github.com/user-attachments/assets/d2671737-1168-4117-927a-c7d902ee8151" />

1)pada baris pertama dan kedua bertujuan untuk membuat variabel penghitung jumlah mahasiswa yang lulus dan tidak_lulus. Variabel ini diinisialisasi dengan nilai nol sebagai nilai awal sebelum proses pengecekan program.

2)barisan ketiga berfungsi untuk membuat perulangan yang digunakan untuk membaca setiap nilai_mahasiswa yang telah disimpan ke dalam list.

3)barisan keempat digunakan sebagai proses perbandingan untuk menentukan nilai mahasiswa yang lulus dan tidak_lulus

4)barisan kelima dan keenam digunakaan untuk menentukan nilai lebih besar/kecil dari 60.

<img width="672" height="151" alt="image" src="https://github.com/user-attachments/assets/5f74d477-848c-4726-a6f3-f4a42e990ba4" />

1)barisan pertama digunakkan untuk menampilkan seluruh nilai mahasiswa yang sudah tersimpan di dalam list.

2)barisan kedua digunakkan untuk mencari nilai terbesar dari seluruh mahasiswa.

3)barisan ketiga digunakkan untuk mencari nilai terkecil dari seluruh mahasiswa.

4)barian keempat digunakkan untuk menghitung rata-rata seluruh nilai mahasiswa.fungsi sum() digunakkan untuk menjumlahkan seluruh nilai yang ada di dalam array dan len() digunakkan untuk mengambil informasi panjang array yang sudah disimpan.

5)baris kelima dan keenam digunakan untuk menampilkan variabel jumlah lulus dan tidak_lulus

<img width="1259" height="236" alt="Screenshot 2026-03-12 174807" src="https://github.com/user-attachments/assets/291d5083-fd3a-4123-8e60-43aae4febf42" />

1)pada baris import matplotlib.pyplot as plt digunakan untuk mengimpor library matplotlib.pyplot yang berfungsi untuk membuat grafik atau visualisasi data.

2)pada baris plt.figure() digunakkan untuk embuat sebuah area gambar baru yang akan digunakan untuk menampilkan grafik.

3)pada baris kategori = ["Lulus", "Tidak Lulus"] digunakan sebagai kategori nama pada grafik tersebut.

4)pada baris data = [lulus, tidak_lulus] digunakkan untuk membuat list yang berisi jumlah mahasiswa lulus dan tidak_lulus.

5)pada baris plt.bar(kategori, data) digunakkan untuk membuat batang grafik.

6)pada baris plt.title("Grafik Data Kelulusan Mahasiswa") digunakkan untuk membuat judul grafik.

7)pada baris plt.show() digunakkan untuk menampilkan garfik yang telah dibuat secara keseluruhan.

<img width="1282" height="281" alt="image" src="https://github.com/user-attachments/assets/55286a37-a7f5-4469-8eda-2d769983b0e0" />

1)pada baris import matplotlib.pyplot as plt digunakan untuk mengimpor library matplotlib.pyplot yang berfungsi untuk membuat grafik atau visualisasi data.

2)pada baris plt.figure() digunakkan untuk embuat sebuah area gambar baru yang akan digunakan untuk menampilkan grafik.

3)pada baris kategori = ["Tertinggi", "Terendah" digunakan sebagai kategori nama pada grafik tersebut.

4)pada Baris nilai_tertinggi = max(nilai_mahasiswa) digunakkan untuk mencari nilai tertinggi dari seluruh mahasiswa.

5)pada Baris nilai_terendah = min(nilai_mahasiswa) digunakkan untuk mencari nilai terendah dari seluruh mahasiswa.

6)pada baris data = [nilai_tertinggi, nilai_terendah digunakkan untuk membuat list yang berisi nilai_tertinggi dan nilai_terendah.

7)pada baris plt.bar(kategori, data) digunakkan untuk membuat batang grafik yang berisi perbandingan antara nilai tertinggi dan terendah.

8)pada baris plt.ylabel("Nilai") digunakkan untuk membuat judul grafik.

9)pada baris plt.show() digunakkan untuk menampilkan garfik yang telah dibuat secara keseluruhan.

# HASIL SCREENSHOT 
<img width="1307" height="360" alt="image" src="https://github.com/user-attachments/assets/6d7f6117-749f-4c6c-b66a-eb91b3eb9f96" />
<img width="1262" height="200" alt="image" src="https://github.com/user-attachments/assets/d2671737-1168-4117-927a-c7d902ee8151" />
<img width="672" height="151" alt="image" src="https://github.com/user-attachments/assets/5f74d477-848c-4726-a6f3-f4a42e990ba4" />
<img width="1246" height="774" alt="Screenshot 2026-03-12 195057" src="https://github.com/user-attachments/assets/69d3b1f2-3467-466c-b09d-4e7934b0f740" />
<img width="1272" height="782" alt="Screenshot 2026-03-12 195125" src="https://github.com/user-attachments/assets/08352668-6e2f-4ad5-9903-fedbadf459ce" />

# ANALISIS KOMPLEKSITAS

pada bagian input mahasiswa, waktu kompleksitasnya adalah O(n). dikarenakan program ini menggunakan perulangan for dimana proses ini dilakukan sebanyak n kali sesuai banyak nya data mahasiswa.

pada bagian proses menghitung jumlah mahasiswa lulu dan tidak lulus, waktu kompleksitasnya adalah O(n). dikarenakan  program menggunakan perulangan untuk memeriksa setiap nilai apakah lebih besar atau sama dengan 60 untuk menentukan status kelulusan mahasiswa.

pada bagian mencari nilai tertinggi(max) dan nilai terendah(min),waktu kompleksitasnya adalah O(n). dikarenakan kedua fungsi ini bekerja dengan memeriksa semua nilai dalam array

pada bagian menghitung rata-rata, waktu kompleksitasnya adalah O(n).dikarenakan program menggunakkan sum() menghitung seluruh dalam array, dan sedangkan len() memiliki waktu kompeksitas yaitu O(1) yang dimana program ini hanya membaca panjang array saja.

pada bagian membuat grafik, waktu kompleksitasnya adalah O(1). dikarenakan data yang ditampilkan bersifat tetap dan tidak bergantung pada jumlah elemen array.

# REFLEKSI PEMBELAJARAN 

saya dapat memahami bagaimana cara menggunakkan struktur data array(list) yang dimana untuk mengelola data seperti data diatas.

saya dapat mengetahui cara mencari nilai tinggi(max) dan rendah(min),dan menghitung rata-rata(sum) di program python.

saya dapat memahami cara membuat grafik di python yaitu menggunakkan  matplotlib.pyplot as plt.

