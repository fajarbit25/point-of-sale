- Install git
- Install composer
- Buat direktori baru di local
- Jalankan terminal, pastikan anda berada di directory yang baru dibuat
- Jalankan perintah berikut untuk cloning repository
<code> git clone https://github.com/fajarbit25/point-of-sale.git </code>
- copy file .env.example (replace namanya file menjadi .env)
- Jalankan perintah berikut untuk mendownload package vendor dari laravel.
<code> composer update </code>

- Selanjutnya buat app key
<code> php artisan key:generate </code>

- Buat database dengan nama dbpos
- Lalu jalankan migrasi database nya, dengan perintah berikut.
<code> php artisan migrate </code>
- Jalankan seeder database
<code> php artisan migrate:fresh --seed </code>

- Lalu jalakan web server anda.
<code> php artisan serve </code>
- Lalu akses url http://localhost:8000
- informasi  Login 

username : admin@gmail.com
password : 123