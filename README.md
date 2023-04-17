# BD-Pratikum2

## Praktikum 1

Data Model Mapping
1. Mahasiswa (nim, nama, jenis_kelamin, tgl_lahir, jalan, kota, kodepos, no_hp, kd_ds)
2. Dosen (kd_ds, nama)
3. Matakuliah (kd_mk, nama, sks)
4. JadwalMengajar (kd_ds, kd_mk, hari, jam, ruang)
5. KRSMahasiswa (nim, kd_mk, kd_ds, semester, nilai)

Buat DDL Script berdasarkan skema ERD tersebut diatas.
Jalankan script DDL tersebut pada DBMS MySQL

1. Script Tabel mahasiswa

![am](https://user-images.githubusercontent.com/115520666/232470961-6c109f44-d69c-41c2-bba5-4be4696dd081.png)



OUTPUT

![Gmbr1](https://user-images.githubusercontent.com/115520666/232471138-2136f003-8874-492d-a7dd-0f048e5f68bd.png)


2. Script Tabel dosen

![Gmbr2](https://user-images.githubusercontent.com/115520666/232471229-f0fdeffe-08d2-4851-adc4-3c7277529b5a.png)

OUTPUT

![Gmbr3](https://user-images.githubusercontent.com/115520666/232471405-e40606c9-2bdd-4cba-a4b7-4633e792d7c6.png)

3. Script Tabel matakuliah

![Gmbr4](https://user-images.githubusercontent.com/115520666/232471445-0c8d476b-a2a1-4796-97d4-c1e143a336c8.png)

OUTPUT

![Gmbr5](https://user-images.githubusercontent.com/115520666/232471555-54c7ccae-38a0-46ce-a079-7f7a774f5c05.png)

4. Script Tabel JadwalMengajar

![Gmbr6](https://user-images.githubusercontent.com/115520666/232471615-0b660958-a3a3-4e03-aa4c-970caa299e9f.png)

OUTPUT

![Gmbr7](https://user-images.githubusercontent.com/115520666/232471701-6307689d-5d99-42bc-a713-c251f7e7044a.png)

6. Script Tabel KRSmahasiswa

![Gmbr8](https://user-images.githubusercontent.com/115520666/232471794-ad9f9f8a-686c-4d1c-8a9f-ee40900ff3af.png)

OUTPUT

![Gmbr9](https://user-images.githubusercontent.com/115520666/232471985-ed6c716d-fdf6-417e-be31-8294a25eab3f.png)

DDL Script
![Gmbr10](https://user-images.githubusercontent.com/115520666/232472128-de205efa-36af-4ea1-ba76-14840f4a3d6d.png)



# Tugas Praktikum 2
```
1. Isi data pada table tersebut sebanyak minimal 5 record data.
2. Tampilkan semua isi/record tabel! 
3. Ubah data tanggal lahir mahasiswa yang bernama Ari menjadi: 1979-08-31! 
4. Tampilkan satu baris / record data yang telah diubah tadi yaitu record dengan nama Ari saja! 
5. Hapus Mahasiswa yang bernama Dina! 
6. Tampilkan record atau data yang tanggal kelahirannya lebih dari atau sama dengan 1996-1-2! 
7. Tampilkan semua Mahasiswa yang berasal dari Bekasi dan berjenis kelamin perempuan! 
8. Tampilkan semua Mahasiswa yang berasal dari Bekasi dengan kelamin laki-laki atau Mahasiswa yang berumur lebih dari 22 tahun dengan kelamin wanita!
9. Tampilkan data nama dan alamat mahasiswa saja dari tabel tersebut
10. Tampilkan data mahasiswa terurut berdasarkan nama
```

1. Isi data pada table tersebut sebanyak minimal 5 record data.
![Gmbr11](https://user-images.githubusercontent.com/115520666/232472257-611c02a1-957f-423f-b40f-0febb5a0f140.png)

2. Tampilkan semua isi/record tabel!
![Gmbr12](https://user-images.githubusercontent.com/115520666/232472319-de967634-e70c-4889-b14d-33dda7406ea6.png)

3. Ubah data tanggal lahir mahasiswa yang bernama Ari menjadi: 1979-08-31!
![Gmbr13](https://user-images.githubusercontent.com/115520666/232472372-fff97470-8e43-4bc6-b236-232bb3d1c64c.png)

4. Tampilkan satu baris / record data yang telah diubah tadi yaitu record dengan nama Ari saja!
![Gmbr14](https://user-images.githubusercontent.com/115520666/232472502-3fe5cc43-368c-4d12-947e-83a65fc0f08b.png)

5. Hapus Mahasiswa yang bernama Dina!
![Gmbr15](https://user-images.githubusercontent.com/115520666/232472720-4df5d650-b3b9-4af4-9677-b2838df752a4.png)

6. Tampilkan record atau data yang tanggal kelahirannya lebih dari atau sama dengan 1996-1-2!
![Gmbr16](https://user-images.githubusercontent.com/115520666/232472769-7bf24d28-31ff-462e-9724-e2aff13ef801.png)

7. Tampilkan semua Mahasiswa yang berasal dari Bekasi dan berjenis kelamin perempuan!
![Gmbr17](https://user-images.githubusercontent.com/115520666/232472804-88e08e55-08b9-4a37-af39-44b31ea5c8f7.png)

8. Tampilkan semua Mahasiswa yang berasal dari Bekasi dengan kelamin laki-laki atau Mahasiswa yang berumur lebih dari 22 tahun dengan kelamin wanita!
![Gmbr18](https://user-images.githubusercontent.com/115520666/232472851-ef084835-7559-4151-be00-8ece0e79d133.png)

9. Tampilkan data nama dan alamat mahasiswa saja dari tabel tersebut
![Gmbr19](https://user-images.githubusercontent.com/115520666/232472879-4bad5280-fbca-44bf-96bd-227da33cee5e.png)

10. Tampilkan data mahasiswa terurut berdasarkan nama
![Gmbr20](https://user-images.githubusercontent.com/115520666/232472922-d61bea05-dc5f-4f1c-a228-4a74cc90f48f.png)


Evaluasi dan Pertanyaan
1. Apa bedanya penggunaan BETWEEN dan penggunaan operator >= dan <= ?
(misal: tgl_lahir BETWEEN '1990-10-10' AND '1992-10-11')
(misal: tgl_lahir >= '1990-10-10' AND tgl_lahir <= '1992-10-11')
```
Operator BETWEEN digunakan untuk memeriksa apakah sebuah nilai berada di antara dua nilai yang diberikan, termasuk kedua nilai tersebut. Contoh penggunaannya adalah tgl_lahir BETWEEN '1990-10-10' AND '1992-10-11', yang artinya mengambil data dengan tanggal lahir di antara 10 Oktober 1990 dan 11 Oktober 1992, termasuk kedua tanggal tersebut.
Sedangkan operator >= dan <= digunakan untuk membandingkan nilai dan mengambil data dengan nilai yang lebih besar atau lebih kecil dari suatu nilai tertentu. Contoh penggunaannya adalah tgl_lahir >= '1990-10-10' AND tgl_lahir <= '1992-10-11', yang artinya mengambil data dengan tanggal lahir yang lebih besar atau sama dengan 10 Oktober 1990 dan lebih kecil atau sama dengan 11 Oktober 1992.
```
2. Berikan kesimpulan anda!
```
Data Manipulation Language (DML) adalah bahasa pemrograman yang digunakan untuk mengakses, memanipulasi dan mengelola data dalam database. DML memungkinkan pengguna untuk melakukan operasi seperti menambahkan data baru, memperbarui data yang ada, menghapus data, dan mengambil data untuk mendapatkan data yang dibutuhkan.

Di DML, pengguna dapat mengakses data menggunakan perintah SQL (Structured Query Language). SQL adalah bahasa standar untuk mengakses dan mengelola data dalam basis data relasional. Perintah SQL yang digunakan dalam DML adalah untuk menyisipkan, memodifikasi, menghapus, dan menampilkan data seperti dijelaskan di atas. 
```


