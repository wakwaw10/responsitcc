# responsitcc

1. Pull repository dengan perintah `git pull https://github.com/fikimaul/responsitcc.git`
2. Masuk ke folde yang telah di pull tadi dengan perintah `cd responsitcc`
3. Untuk membuild image jalankan perintah `docker build -t nama_image .`
4. Untuk menjalankan image yang telah dibuild digunkan perintah `docker run -d -p 8000:80 -p 443:443 --name nama_kontainer nama_image`
5. untuk menjalankan doker-compose gunakan perintah `docker-compose up -d`
