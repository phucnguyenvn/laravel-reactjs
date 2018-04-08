## Laravel with ReactJS

A simple application using Laravel framework with ReactJS as a preset,mainly using:

- [Laravel 5.6](https://laravel.com/docs/5.6/installation)
- [ReactJS](https://reactjs.org/docs/hello-world.html)
- [React Router Dom](https://reacttraining.com/react-router/web/guides/quick-start) for Routing.
- [React History](https://github.com/ReactTraining/history) to manage browser history.

## Installation

Clone this repository to your local working folder, simply run this following commands:

```
composer install
php artisan migrate
php artisan db:seed --class=UsersTableSeeder
php artisan preset react
npm install && npm run dev
php artisan serve
```

