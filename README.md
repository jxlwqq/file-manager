# File manager for laravel-admin

File manager for Cloud Storage, based on [Media manager for local disk](https://github.com/laravel-admin-extensions/media-manager).

## Screenshot

<img src="https://user-images.githubusercontent.com/2421068/55272835-f5780d80-52fd-11e9-9f56-07ea778925c5.png">

## Installation

```bash
composer require jxlwqq/file-manager
```

Add a disk config in `config/admin.php`:

```php
'extensions' => [
    'file-manager' => [
           // Select a local disk that you configured in `config/filesystem.php`
           'disk' => 'public'
    ],
],
```

Open `http://localhost/admin/file-manager`.


## More resources

[Awesome Laravel-admin](https://github.com/jxlwqq/awesome-laravel-admin)

## License

Licensed under [The MIT License (MIT)](LICENSE).
