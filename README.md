<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# II. Persiapan
### 1. Instalasi Laravel 11
![1](https://github.com/user-attachments/assets/c1d6b853-4c3e-4999-98d8-8f99fed719d4)
### 2. Konfigurasi Database
![db](https://github.com/user-attachments/assets/26166ed8-2342-4bbf-a5c5-e5b5b3797115)
# III. Membuat API CRUD untuk Sistem Toko Buku
### 1. Membuat Migration dan Model
> Buat migration dan model untuk Kategori dan Buku
![2](https://github.com/user-attachments/assets/37b9355f-7720-43fb-98db-163d2a212aa8)
![3](https://github.com/user-attachments/assets/afa32741-dedf-41ae-a9ab-cc17ae3ad034)
> Edit file migration `create_kategoris_table.php`:
![4](https://github.com/user-attachments/assets/a3804506-84db-4aa2-8a2d-ef098ca7e85a)
> Edit file migration `create_bukus_table.php`:
![5](https://github.com/user-attachments/assets/c9f150a2-43cd-43f5-9fb2-b86b18e9ee46)
### 2. Membuat Controller API untuk Kategori dan Buku
> Buat controller untuk Kategori dan Buku:
![6](https://github.com/user-attachments/assets/eaab5917-a752-4974-b7e1-75996f6b13c7)
> Isi file `KategoriController.php`:
![7](https://github.com/user-attachments/assets/32405f87-cf88-42bb-84f6-5d773d252065)
> Jalankan perintah berikut untuk melakukan migrasi:
![migrate](https://github.com/user-attachments/assets/fc8d48c6-139c-4449-96c1-650913bbb44f)

# IV. Testing API dengan Postman
> 1. Jalankan server Laravel:
![9](https://github.com/user-attachments/assets/c55ba7c4-338a-42e0-a58f-cdaf9ed7fab1)

> 2. Testing endpoint menggunakan Postman:
> A.	GET http://localhost:8000/api/kategoris
![GET K](https://github.com/user-attachments/assets/76dc1b19-dd49-438f-9aa1-0eda3ae467f4)
> B. POST http://localhost:8000/api/kategoris
![POST K](https://github.com/user-attachments/assets/09eaf2cb-2cc3-4204-b2eb-03649e4688f2)
> C. GET http://localhost:8000/api/bukus
![GET B](https://github.com/user-attachments/assets/c0a815d2-927a-48c1-b1af-de6c5b464bd4)
> D. POST http://localhost:8000/api/bukus
![POST B](https://github.com/user-attachments/assets/36c90d50-0d49-44a8-85a8-af2465d078cc)
> E. GET http://localhost:8000/api/bukus/1
![GET B1](https://github.com/user-attachments/assets/71134954-b171-448b-9528-dbf152eb6061)
> F. PUT http://localhost:8000/api/bukus/1
![PUT B](https://github.com/user-attachments/assets/e7766fc0-293e-4336-991a-eea5cac37939)
> G. DELETE http://localhost:8000/api/bukus/1
![DEL](https://github.com/user-attachments/assets/b42c9529-01c2-4779-bf50-6b796485562e)

Tugas Mahasiswa
1.	Tambahkan Validasi:
o	Nama buku tidak boleh kosong.
o	Harga minimal Rp 1.000.
![Validasi 2](https://github.com/user-attachments/assets/4d18f3b2-bdf7-4d49-9ce6-ea73e475fdcf)

2.	Rancang Endpoint Baru:
Buatlah satu endpoint tambahan untuk sistem toko buku, misalnya, endpoint untuk mencari buku berdasarkan kategori atau judul. Tantangan: Apa pertimbangan yang harus Anda buat saat merancang endpoint ini? Pertimbangkan aspek performa, skalabilitas, dan pengalaman pengguna.
![Validasi 1](https://github.com/user-attachments/assets/a4413bae-6c7d-4166-a7d5-82f5a3bde78c)

3.	Uji API Secara Publik:
o	Gunakan ngrok atau sejenisnya untuk membuka API ke internet.
https://sj2qcddp-8000.asse.devtunnels.ms/
![90](https://github.com/user-attachments/assets/f79adf03-4228-45fc-b550-410107e23941)
![55](https://github.com/user-attachments/assets/84e94bc6-726d-48e5-80cd-57d25a1eb979)
















