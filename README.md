# Pertemuan 07 Fungsi Python
Nama: Zakiyatus Salsabila
NIM: 2225250225
Kelas: 3F

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan
python3 praktik/utilitas_matematika.py

## Struktur Fungsi
Program ini berisi beberapa fungsi matematika sederhana, yaitu:

1. **luas_persegi_panjang(p, l)**  
   Menghitung luas persegi panjang dengan mengalikan panjang dan lebar, kemudian mengembalikan hasil menggunakan `return`.

2. **luas_segitiga(a, t)**  
   Menghitung luas segitiga dengan rumus setengah dikali alas dikali tinggi.

3. **jumlah_n(n)**  
   Menghitung jumlah bilangan dari 1 sampai n menggunakan perulangan.

4. **faktorial(n)**  
   Menghitung nilai faktorial suatu bilangan menggunakan perulangan. Faktorial 0 menghasilkan nilai 1.

5. **menu()**  
   Menampilkan pilihan operasi matematika dan memanggil fungsi sesuai pilihan pengguna.

Setiap fungsi menggunakan parameter sesuai data yang diperlukan. Hasil perhitungan dikembalikan menggunakan `return`, sehingga hasilnya bisa digunakan kembali oleh bagian program lain.

## Hasil Pengujian
Pengujian dilakukan dengan membandingkan hasil yang diharapkan dengan hasil aktual dari program.

| Operasi | Input | Hasil yang Diharapkan |
|---|---|---|
| Luas persegi panjang | p = 8, l = 5 | 40 |
| Luas segitiga | a = 10, t = 6 | 30.0 |
| Jumlah 1 sampai n | n = 10 | 55 |
| Faktorial | n = 5 | 120 |
| Faktorial | n = 0 | 1 |

Seluruh pengujian dinyatakan berhasil apabila hasil aktual sesuai dengan hasil yang diharapkan. Hasil aktual perlu diperiksa langsung dengan menjalankan program di terminal.

## Kriteria Keberhasilan

- Setiap fungsi memiliki satu tujuan yang jelas.
- Parameter digunakan untuk menerima data yang dibutuhkan fungsi.
- Fungsi perhitungan menggunakan `return` untuk mengembalikan hasil.
- Variabel lokal digunakan sesuai dengan ruang lingkupnya.
- Hasil pengujian sesuai dengan perhitungan yang diharapkan.
- Program utama mudah dibaca dan tidak mengulang rumus yang sama.
- Program dapat dijalankan dan setiap fungsi dapat dijelaskan.

## Refleksi
etelah mengerjakan praktik ini, saya memahami bahwa fungsi dapat membantu membuat program menjadi lebih teratur dan mudah dibaca. Setiap fungsi memiliki tugas masing-masing, sehingga kode tidak perlu ditulis berulang kali ketika melakukan perhitungan yang sama.

Saya juga belajar menggunakan parameter untuk memasukkan data ke dalam fungsi dan `return` untuk mengembalikan hasil perhitungan. Dengan cara ini, hasil fungsi dapat disimpan dalam variabel atau digunakan kembali untuk proses lain.

Selain itu, saya memahami perbedaan variabel lokal dan variabel yang berada di luar fungsi. Variabel lokal digunakan di dalam fungsi tempat variabel tersebut dibuat, sedangkan variabel di luar fungsi memiliki ruang lingkup yang berbeda.

Melalui pengujian beberapa operasi matematika, saya belajar bahwa hasil program perlu diperiksa menggunakan test case agar kesalahan dapat diketahui. Contohnya, faktorial 0 harus menghasilkan 1, sedangkan jumlah bilangan dari 1 sampai 10 harus menghasilkan 55.

Kesulitan yang saya pelajari dari praktik ini adalah memahami cara kerja parameter, `return`, dan scope. Dengan mencoba menjalankan program dan memeriksa hasilnya, saya menjadi lebih memahami alur kerja fungsi dalam Python.
