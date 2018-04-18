# Im
These are my laravel code application that I learned in university. I hope it can inspire you.

How to Make Blog use Laravel Framework

How to use
- Download clone repository and extract it
	```sh
	$ git clone https://github.com/Imroatussadiyah/
	```
- Masuk ke direktori aplikasi dan jalankan composer
	```sh
	$ cd laravel_blog
	$ composer install
	```
- Setting .env dan key application
	```sh
	$ mv .env.example .env
	$ php artisan key:generate
	```
- Edit database name, database username dan database password

	> DB_DATABASE=your_db.

 	> DB_USERNAME=your_mysql_username.
 	
	> DB_PASSWORD=your_mysql_password.

- Migrate table
	```sh
	$ php artisan migrate
	```

- Buka browser di 127.0.0.1:8000
- Register new account
- Login
