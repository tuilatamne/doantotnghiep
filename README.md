Hướng dẫn chạy đồ án

mở terminal rồi chạy
b1: composer install
b2: cp .env.example .env
b3: php artisan key:generate
b4: chỉnh file trong .env như sau
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=doantotnghiep
DB_USERNAME=root
DB_PASSWORD=
b5: php artisan migrate
b7: npm install
Đã xong thiết lập đồ án
Tiếp theo để chạy cần
npm run dev
php artisan serve

Lưu ý nếu có lỗi quyền truy cập thư mục thì mở terminal lên chạy
chmod -R 775 storage bootstrap/cache
