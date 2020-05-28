# Laravel 6.0 CRUD

### Installation

1. Clone repository
```
$ git clone https://github.com/risingworld777/laravel-crud-with-restful-api.git
```

2. Enter folder
```
$ cd laravel-crud-with-restful-api
```

3. Install composer dependencies
```
composer install
```

4. Generate APP_KEY
```
php artisan key:generate
```

5. Configure .env file, edit file with next command `$ nano .env`
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=***
DB_PASSWORD=***
```

6. Run migrations
```
php artisan migrate
```

7. Create Server
```
php artisan serve
```

8. Access project
```
http://127.0.0.1:8000/products
```
