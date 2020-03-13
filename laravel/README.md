## Laravel

Clean Laravel

```
php artisan cache:clear && php artisan config:clear && php artisan view:clear && php artisan route:clear && composer dump-autoload

php artisan cache:clear && php artisan config:clear && php artisan view:clear && php artisan route:clear && composer dump-autoload && php artisan responsecache:flush
```

Deploy Project - [Deployer](https://deployer.org/)

```
php vendor/bin/dep deploy homolog

php vendor/bin/dep deploy production
```

Deploy Project with specific branch - [Deployer](https://deployer.org/)

```
php vendor/bin/dep deploy homolog --branch=develop

php vendor/bin/dep deploy production --branch=master
```

Up Server

```
php artisan serve --port=8080 -vvv
```

Up Server for Network

```
php artisan serve --host=192.168.0.57 --port=8989 -vvv
```

Mock crontab on docker

```
while true; do php artisan schedule:run; sleep 60; done
```

Run Seed at specific Seeder

```
php artisan db:seed --class=ExampleSeeder
```

Migrate and Seed same time, and rollback all base

```
php artisan migrate:refresh --seed
```

Update composer

```
composer self-update
```