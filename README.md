# Lumen App
This is my first project on Lumen App from Laravel.

### Install
```bash
composer create-project laravel/lumen lumen_app
```

### PHP Development Server
```bash
php -S localhost:8000 -t public
```

### Key Generate
```bash
composer require maxsky/lumen-app-key-generator
```

Then go to app/Console/Kernel.php
```bash
protected $commands = [
        \Illuminate\Console\KeyGenerateCommand::class,
    ];
```

