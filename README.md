## Video Chat Application Example

[Youtube Tutorial link](https://www.youtube.com/watch?v=Jd1RW-0lQOs&t=13s)

#### [@WeCodeTutorials](https://twitter.com/WeCodeTutorials)
[![Logo](https://cdn.pbrd.co/images/HdwCut8.png)](https://www.youtube.com/channel/UCj9VatwdukZjNOnIKcpWcsA)

This project is made for my youtube tutorial on "Create a SPA with Vue.JS 2, Vue-Router, Vuex and Laravel 5.6".

## get it up and running.

After you clone this project, do the following:

```bash
# go into the project
cd Vue-Laravel-SPA

# create a .env file
cp .env.example .env

# install composer dependencies
composer update

# install npm dependencies
npm install

# generate a key for your application
php artisan key:generate

# create a local MySQL database (make sure you have MySQL up and running)
mysql -u root

> create database vuespa_db;
> exit;

# add the database connection config to your .env file
DB_CONNECTION=mysql
DB_DATABASE=vuespa_db
DB_USERNAME=root
DB_PASSWORD=

# run the migration files to generate the schema
php artisan migrate

# run webpack and watch for changes
npm run watch
```

Good Luck :)
