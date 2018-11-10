<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Install

1. Composer install

```
$ composer install
```
2. Copy .env file. You must copy .env.example to .env file

3. Generate key for your applicaiton

```
$ php artisan key:generate
```
4. Run npm and bower

```
$ npm install
$ bower install
$ npm run dev
```
5. Webpack js and css files

```
$ npm run dev
```
6. Some commands for adminlte packge

- Customize views: If you need full control over the provided views, you can publish them:

```
$ php artisan vendor:publish --provider="JeroenNoten\LaravelAdminLte\ServiceProvider" --tag=views
```

- Get assets (js and css files)

```
$ php artisan vendor:publish --provider="JeroenNoten\LaravelAdminLte\ServiceProvider" --tag=assets --force
```
## License

Laravel version 5.7

Now, Enjoy it!!! Good luck to you :D
