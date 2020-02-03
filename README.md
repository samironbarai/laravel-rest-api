# Laravel REST APi for CRUD operation

You can create REST API following bellow steps

# Installation
1. Clone this repo
```
https://github.com/samironbarai/laravel-rest-api.git
```

2. Install composer packages
```
cd laravel-rest-api
$ composer install
```

3. Create and setup .env file
```
make a copy of .env.example and rename to .env
$ php artisan key:generate
put database credentials in .env file
```

4. Migrate and insert records
```
$ php artisan migrate
$ php artisan tinker
$ factory(App\Customer::class, 100)->create();
```
