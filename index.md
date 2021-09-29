# Vue.js + Laravel SPA + Vuetify + CrudBooster

Designed is powered by [Vuetify framework](https://vuetifyjs.com/en/) based on Material Design.

The goal is to start a new SPA project quickly with routes and components structure already in place.

__What's included:__

- Laravel 7 default project
- Vue.js boilerplate with Components: App, Header, Navbar, Footer, Sidebar
- Three menu items using Vue Router: Homepage (dynamic data from API), About and Contact (both static texts) 
- One Laravel model Product with Migrations+Seeds, one API call to get all products, using API Resource
- Crudbooster Backend

- - - - -

## How to use

- Clone the repository with `git clone`
- Copy `.env.example` file to `.env` and edit database credentials there
- Run `composer install`
- Run `php artisan key:generate`
- Run `php artisan migrate --seed` (it has some seeded data for your testing)
- Run `php artisan crudbooster:install` (Install Backend)
- Run `npm install`
- Run `npm run dev`
- That's it: launch the main URL. 


## License

Modified from [LaravelDaily](https://github.com/LaravelDaily/Laravel-Vue-SPA-Vuetify).
Basically, feel free to use and re-use any way you want.

---
