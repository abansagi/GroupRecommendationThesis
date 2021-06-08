# GroupSurvey
 
# Installation

This project works with both Laravel and Vue, to install packages do:
`composer install` for php and `npm install` for JavaScript.

MongoDB is used as database model, thus there are no mandatory migrations. Nevertheless, there is a migration available for the session model, which can be run by running `php artisan migrate`. Finally, routes can be generated by running `php artisan route:scan`.

# Dependencies:

* PHP:
    * "php": "^7.4",
    * "fideloper/proxy": "^4.2",
    * "fruitcake/laravel-cors": "^1.0",
    * "guzzlehttp/guzzle": "^6.3",
    * "jenssegers/mongodb": "4.0.0-alpha.1",
    * "jwilsson/spotify-web-api-php": "^3.4",
    * "laravel/framework": "^7.0",
    * "laravel/tinker": "^2.0",
    * "laravel/ui": "^2.0",
    * "laravelcollective/annotations": "^7.0",
    * "laravelcollective/html": "^6.1",
    * "ext-json": "*"
* JavaScript:
    * "bootstrap-vue": "^2.15.0",
    * "jquery": "^3.5.1",
    * "jquery.redirect": "^1.1.4",
    * "js-cookie": "^2.2.1",
    * "laravel-mix-svg-vue": "^0.2.6",
    * "spotify-web-api-js": "^1.4.0",
    * "vue": "^2.6.11",
    * "vue-axios": "^2.1.5"