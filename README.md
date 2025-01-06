# Dockerfile
## Untuk laravel php 7.4
```bash
docker build -f Dockerfile.laravel.php74 -t php75 .
docker run -it -v .:/app php75 bash
composer install
```
