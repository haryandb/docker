# Dockerfile
## Untuk laravel php 7.4
```bash
docker build -t php75 .
docker run -it -v .:/app php75 bash
composer install
```
