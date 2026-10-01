# Cursor

## Project overview

This is a PHP web app built with Laravel. HTTP requests go through routes into controllers; Blade views render the UI. Business logic lives in models, services, and middleware so the app stays easy to grow.

## Tech stack

- **Runtime:** PHP
- **Language:** PHP
- **Framework:** Laravel

## Project structure

```
test-project/
├── app/
│   ├── Http/
│   │   ├── Controllers/     # Request handlers
│   │   └── Middleware/      # Request filters
│   ├── Models/              # Eloquent models
│   └── Providers/           # Service providers
├── bootstrap/
├── config/                  # App configuration
├── database/
│   ├── migrations/
│   ├── seeders/
│   └── factories/
├── public/                  # Front controller and static assets
├── resources/
│   ├── views/               # Blade templates
│   ├── css/
│   └── js/
├── routes/
│   ├── web.php
│   └── api.php
├── storage/
├── tests/
├── artisan
└── composer.json
```
