tutorial buat panel pterodactyl 
1. sudo su
2. apt update
3. apt upgrade -y
#run panel
4. docker-compose up -d
#buat akun
5. docker-compose run --rm panel php artisan p:user:make
