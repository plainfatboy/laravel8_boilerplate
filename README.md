# Laravel 8 boilerplate

# Stacks
1. PHP-FPM 7.4
2. Nginx 1.9
3. MySQL 8

# Start the services
``` docker-compose up -d ```

# Before start hacking with Laravel framework
1. Create a database in MySQL
2. Create .env file in `app` folder and configure database credentails
3. Access php container by using `docker-compose exec php bash` and run `composer install`
4. You can now access your laravel at http://localhost

# MySQL root credential
- username: root
- password: root

``` The default port (3306) is exposed. Therefore, you can use clients such as MySQL workbench or Table Plus to connect to the database. ```

# Stop the services
``` docker-compose down ```

``` Cheers!!! ```
