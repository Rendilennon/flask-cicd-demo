Polling App

Polling App adalah aplikasi sederhana berbasis **Flask** dan **PostgreSQL** untuk membuat polling, melakukan voting, serta melihat hasilnya secara real-time. Proyek ini dikemas menggunakan **Docker Compose** sehingga mudah dijalankan di berbagai lingkungan.

Fitur
- Menampilkan daftar pertanyaan polling.
- Voting pilihan yang tersedia.
- Melihat hasil polling dengan jumlah suara dan persentase.
- Database PostgreSQL dengan data persisten.
- Antarmuka web untuk mengelola database menggunakan **pgAdmin**.

Teknologi
- [Flask](https://flask.palletsprojects.com/) sebagai web framework.
- [PostgreSQL](https://www.postgresql.org/) sebagai database.
- [pgAdmin4](https://www.pgadmin.org/) untuk manajemen database via web.
- [Docker Compose](https://docs.docker.com/compose/) untuk orkestrasi container.


Cara Menjalankan
1. Pastikan Docker dan Docker Compose sudah terinstall.
2. Jalankan perintah berikut:
   ```bash
   docker-compose up -d --build