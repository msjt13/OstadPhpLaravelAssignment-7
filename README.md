
# Assignment 7

## Laravel Installation

- Install Laravel

```bash
composer create-project laravel/laravel ostad-assignment7
```

- Create UserController with resources using following Command

```
php artisan make:controller UserController -r
```

- Mapping Route with UserController
Code
```
Route::get('/user', [UserController::class, 'index']);
```


## RUN the project
```
php artisan serve
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
