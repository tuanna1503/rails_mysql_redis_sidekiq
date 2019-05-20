# README
1. Init rails+mysql:
docker-compose run web rails new . --force --no-deps --database=mysql

 Nếu báo lỗi, change owner của thư mục về owner hiện hành rồi chạy lại câu lệnh trên:
chown -R $USER. *

2. Build Image:
docker-compose build
3. Start app:
docker-compose up

 docker-compose run web rake db:create
