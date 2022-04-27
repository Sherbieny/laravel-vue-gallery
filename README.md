# Laravel Vue Image Gallery Application

#### A gallary application showing images data from <a href="https://jsonplaceholder.typicode.com/" target="_blank">{JSON} Placeholder</a> API

<br>

### Features

-   Features provide by <a href="https://github.com/cretueusebiu/laravel-vue-spa" target="_blank">cretueusebiu
    /
    laravel-vue-spa</a> project which this project is based on

    -   Laravel 8
    -   Vue + VueRouter + Vuex + VueI18n + ESlint
    -   Pages with dynamic import and custom layouts
    -   Login, register, email verification and password reset
    -   Authentication with JWT
    -   Socialite integration
    -   Bootstrap 5 + Font Awesome 5

<br>

-   Gallery rendering images in responsive grid with pagination
-   Logged in users can favourite/unfavourite images
-   Guest gallery rendering:
    -   On Saturday and Sunday: Most favourited images by registered users
    -   Rest of the week: Logged in users with most favourite count

### Installation

-   clone the project
-   create/edit `.env` file with your database configuration
-   `php artisan key:generate`
-   `php artisan jwt:secret`
-   `php artisan migrate`
-   `npm install`

### Usage

-   Development
    -   `npm run dev`
    -   OR `npm run watch` for continues syncing during development
-   Production
    -   `npm run build`

##### Please refer to the original project for more information
