
# UlasKelas

## Deskripsi Proyek
UlasKelas adalah aplikasi berbasis web yang bagi mahasiswa IPB untuk berbagi dan mengakses ulasan mengenai berbagai mata kuliah Supporting Course. Melalui UlasKelas, mahasiswa dapat membaca pengalaman dan penilaian dari rekan-rekan mereka mengenai mata kuliah tertentu, termasuk informasi tentang beban  studi, kualitas pengajar, dan relevansi terhadap bidang studi utama. 



## Metode Pengembangan

[![Static Badge](https://img.shields.io/badge/TRELLO-0052CC?style=for-the-badge&logo=trello&logoColor=FFFFFF)](https://trello.com/)

Pada proses pengembangan aplikasi web UlasKelas, metode yang digunakan adalah metode Agile. Metode Agile merupakan pendekatan lebih lanjut dari SDLC (System Development Life Cycle) untuk memfasilitasi pengembangan aplikasi yang membutuhkan waktu yang singkat, dan memberikan tingkat keberhasilan pengembangan aplikasi lebih baik dari metode desain terstruktur

Jenis metode Agile yang digunakan adalah Kanban. Kanban merupakan cara manajemen dengan memvisualisasikan seluruh alur kerja daripada melihat hasil dari setiap proses
## Anggota

| Nama | NIM     |
| :-------- | :------- | 
[Ahmad Subhan Daryhadi](https://www.github.com/ahmadsubhand) | G6401221023 |
[Ridho Al Fath Nusantara](https://www.github.com/Roufth)| G6401221030 |
[Pandu Persada Tanjung](https://www.github.com/pandutanjung)| G6401221097 |

## Batasan

Terdapat beberapa batasan yang dimiliki oleh aplikasi ini diantaranya

- Daftar mata kuliah tidak dapat ditampilkan semua dikarenakan konsumsi API hanya dapat mengakses data mata kuliah pada semester yang sedang berjalan
- Aplikasi yang dibuat menggunakan OAuth untuk implementasi fitur loginnya dengan membatasi akses email sehingga jika ingin menggunakan aplikasi ini harus menggunakan email IPB (apps.ipb.ac.id)


## Instalasi

Jalankan program dengan menjalankan perintah berikut di terminal

```bash
  python manage.py runserver
```
Program akan ditampilkan di browser ketika mengklik link server yang muncul pada terminal

## UML Diagram

Use Case Diagram
![Use Case Diagram](https://github.com/pandutanjung/UlasKelas/assets/83505767/bec7b4f2-cd49-461d-b7e7-e24fae7fdebe)

Activity Diagram

![Activity Diagram](https://github.com/pandutanjung/UlasKelas/assets/83505767/36587327-3f88-4de0-80e3-7b3712f6d875)

Class Diagram

![Class Diagram](https://github.com/pandutanjung/UlasKelas/assets/83505767/25b9bb5d-64bd-401d-bd53-4b0441173ceb)

Sequence Diagram

![Sequence Diagram](https://github.com/pandutanjung/UlasKelas/assets/83505767/72fc73a1-787a-4684-953a-78824a1ecffa)

## Teknologi

[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django)](https://www.djangoproject.com/)

[![Google Cloud Platform](https://img.shields.io/badge/Google%20Cloud%20Platform-4285F4?style=for-the-badge&logo=google%20cloud&logoColor=FFFFFF)](https://cloud.google.com/?hl=id)




## Fitur

- Sistem autentifikasi pengguna
- Manajemen mata kuliah, terdiri dari kode mata kuliah, bobot SKS, deskripsi mata kuliah, sebaran nilai semester-semester sebelumnya, ulasan mata kuliah, dan rating penilaian ulasan kuantitatif mata kuliah
- Penghitungan rating
- Forum ulasan mata kuliah, terdiri dari ulasan kuantitatif dan kualitatif


## Desain Antarmuka Aplikasi

Daftar Mata Kuliah
![image](https://github.com/pandutanjung/UlasKelas/assets/83505767/28ce8d61-6b3b-40dd-82e6-5eb1b66bac1c)

Detail Mata Kuliah
![image](https://github.com/pandutanjung/UlasKelas/assets/83505767/acabe5eb-786f-4833-aace-2c3e8c7d8d95)

Tambahkan Rating Pada Mata Kuliah
![image](https://github.com/pandutanjung/UlasKelas/assets/83505767/09094487-6874-440b-8161-143577af0bcb)

Tambahkan Review Pada Mata Kuliah
![image](https://github.com/pandutanjung/UlasKelas/assets/83505767/3f35dc8f-45a2-4a83-b83a-3d0313df1392)

Detail Mata Kuliah
![image](https://github.com/pandutanjung/UlasKelas/assets/83505767/94158daa-5ff8-4188-94fa-bf7fdbfe2ff9)

Edit Rating Pada Mata Kuliah
![image](https://github.com/pandutanjung/UlasKelas/assets/83505767/e8779558-4e86-4cee-880a-117cea709e42)

Edit Review Pada Mata Kuliah
![image](https://github.com/pandutanjung/UlasKelas/assets/83505767/6b99fb94-f956-4a7f-9c07-a53885c6cdf9)
