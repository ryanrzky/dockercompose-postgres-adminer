# Install Postgres dan Adminer Menggunakan Docker Compose

#### Cara Menggunakan
1. Buat Direktory `database-data`
2. Ganti Value
    ```
    POSTGRES_PASSWORD:
    POSTGRES_USER:
    POSTGRES_DB: 
    ```
    sesuai dengan kebutuhan

3. Eksekusi Perintah `docker-compose up -d` untuk menjalankan Postgres dan Adminier
4. Eksekusi Perintah `docker-compose down` untuk menghentikan dan menghapus Postgres dan Adminer