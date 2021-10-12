### Run docker command

```
docker-compose up -d
```

```
docker-compose run --rm composer update
```

This image contains

```
1. PHP 7.4 FPM
2. Nginx
3. MySql 8.0
4. Composer
```

Instructions:
```
1. Install laravel in src folder
2. Set db host `mysql`, password `12345678`, change you desire database name from docker-compose.yml file
3. Create a folder in this directory called `mysql`

Then you are ready to rock and roll.
```
