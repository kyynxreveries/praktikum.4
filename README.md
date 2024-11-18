DAFTAR ISI
==========
- [LAPORAN PRAKTIKUM 4](#laporan-praktikum-4)    
    - [CODE PROGRAM NILAI AKHIR](#code-program-nilai-akhir)
    - [FLOWCHART NILAI AKHIR](#flowchart-nilai-akhir)
    - [KESIMPULAN](#kesimpulan)


# LAPORAN PRAKTIKUM 4


## CODE PROGRAM NILAI AKHIR

### Step 1 : Menginisialisasi List Data Mahassiswa
Program dimulai dengan menginisialisasi sebuah list kosong bernama data_mahasiswa untuk menyimpan data setiap mahasiswa. List ini akan diisi dengan data mahasiswa yang diinput selama program berjalan :

![1](https://github.com/user-attachments/assets/bebc7749-63a4-4a70-a62a-cda52ad022db)


### Step 2 : Input Data Mahasiswa dan Perulangan While
Program kemudian masuk ke dalam sebuah perulangan while yang memungkinkan pengguna untuk memasukkan data mahasiswa secara berulang hingga pengguna memilih untuk berhenti :

- Nama Mahasiswa: Program meminta input nama mahasiswa.
- Nim Mahasiswa: Program meminta input nim mahasiswa.
- Nilai Tugas: Program meminta input nilai tugas mahasiswa dalam bentuk integer.
- Nilai UTS: Program meminta input nilai UTS mahasiswa dalam bentuk integer.
- Nilai UAS: Program meminta input nilai UAS mahasiswa dalam bentuk integer.

![11](https://github.com/user-attachments/assets/72a2b159-9ecc-4e25-82b7-a71550aae935)


### Step 3 : Menghitung Nilai Akhir
Setelah menerima input nilai tugas, UTS, dan UAS, program menghitung nilai akhir mahasiswa dengan menggunakan formula berikut :

![3](https://github.com/user-attachments/assets/92838827-946a-4203-9816-b6542afa9616)


> Formula ini berarti:
> - Nilai tugas memiliki bobot 30% dari nilai akhir.
> - Nilai UTS memiliki bobot 35% dari nilai akhir.
> - Nilai UAS memiliki bobot 35% dari nilai akhir.

### Step 4 : Simpan Data Mahasiswa
Setelah nilai akhir dihitung, program membuat dictionary untuk menyimpan semua informasi tentang mahasiswa (nama, nim, nilai tugas, nilai UTS, nilai UAS, dan nilai akhir). Dictionary ini kemudian ditambahkan ke dalam list data_mahasiswa :

![12](https://github.com/user-attachments/assets/8870a1c8-e1ce-4bf6-b132-30fd45c6bdeb)


### Step 5 : Code Seleksi Untuk Tanyakan Tambahan Data Mahasiswa
Setelah menyimpan data, program bertanya kepada pengguna apakah ingin menambah data mahasiswa lagi atau tidak. If pengguna mengetik y, program akan mengulangi proses input. Jika pengguna mengetik t, perulangan akan berhenti, berikan perintah break untuk menghentikan Program :

![5](https://github.com/user-attachments/assets/c3930525-022b-46e9-8b74-2e83d61cb75b)


### Step 6 : Print Data Mahasiswa
Setelah perulangan selesai (pengguna memilih t untuk berhenti menambah data), program akan menampilkan daftar data mahasiswa yang telah dimasukkan. Untuk setiap mahasiswa data yang ditampilkan meliputi nama, nim, nilai tugas, nilai UTS, nilai UAS, dan nilai akhir :

![13](https://github.com/user-attachments/assets/f7dd46e5-d3eb-4949-8eb0-00e98105e195)


### Step 7 : Beri Batas Bawah
Print '=' dikalikan 80 :

![14](https://github.com/user-attachments/assets/8f869167-3a6b-4a5d-bf19-5814b1247b16)

### Step 8 : Test Code Program
Jalankan code program dengan memasukan nama, nilai tugas, nilai uts, nilai uas :

- Nama : Dafa Maulana
- Nim : 312410387
- Nilai Tugas : 90
- Nilai UTS : 55
- Nilai UAS : 80

  ![WhatsApp Image 2024-11-18 at 20 49 51](https://github.com/user-attachments/assets/dbafe06d-353a-4671-acd5-66c9508822ae)


## FLOWCHART NILAI AKHIR

### Step 1 : Start
Titik Mulai :

![16](https://github.com/user-attachments/assets/32066d22-2413-40fd-b979-3890015fd01f)


### Step 2 : Input Data Mahasiswa
Buatkan Input Data Mahasiswa dengan mencangkup Nama, Nim, Nilai Tugas, Nilai UTS, Nilai UAS :

![17](https://github.com/user-attachments/assets/81985e62-4e22-4bfe-9939-d637d2cdea24)


### Step 3 : Lakukan Seleksi
Langkah selanjutnya yaitu buatkan decision atau seleksi berupa pertanyaan Menambahkan Data Mahasiswa (Y/T?), jika Ya maka kemabli ke Input Data mahasiswa, jika Tidak maka lanjut ke langkah selanjutnya :

![22](https://github.com/user-attachments/assets/d81f39d8-ddae-422d-8ac2-d2559276f21d)

### Step 4 : Proses Perhitungan
Langkah ini untuk memproses Nilai Akhir dari Input nilai nilai yang telah dimasukan :

![23](https://github.com/user-attachments/assets/78412618-8da6-4350-aaa1-008fd2d861af)


### Step 5 : Output Nilai Akhir
Masuk kelangkah Akhir yaitu menampilkan Nilai Akhir dari Data Mahasiswa yang telah diinputkan dan sudah dihitung :

![24](https://github.com/user-attachments/assets/62f62d28-56ca-443b-9684-c467c743e5d2)


### Step 6 : End
Titik Berhenti :

![25](https://github.com/user-attachments/assets/fa78d31e-d3fc-4a0d-8a47-886660d46a91)

## Kesimpulan
kesimpulan dari laporan prkatikum di atas adalaj penggunaan append dapat menambahkan element lain,jika kita perhatikan penggunaan perulangan sangat membantu untuk memastikan jika ada tambahan data yang
di inputkan,namun dari semua itu adalah kelas dari sebuah list dari tema praktikum kali ini.penggunaan list berguna untuk mengetahui apa saja yang ada di dalam data,list mampu menampung beberapa
element bebeda.
