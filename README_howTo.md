Stylesheet and Javascript files are in the folder assets.

Original SCSS files are stored in the folder assets/style/*.scss
Original Javascript code is stored in the folder assets/js/app.js

* Instructions

* start the local environment with `docker-compose up -d`
* install the dependencies by `composer install`
* install the module uglifyjs `npm i uglify-js`
* Minify javascript with `uglifyjs assets/js/app.js > public/js/app.js`
* Compile SCSS file with `docker exec npm_api node-sass assets/style/source.scss public/style/target.css`
* go to http://localhost:8080/teufel-real-blue-im-test_104508