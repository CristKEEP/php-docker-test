1. build image with `docker build -t php-docker-test .`
2. run a.php with `docker run --rm php-docker-test php a.php`
3. run b.php with `docker run --rm php-docker-test php b.php`
4. `docker-compose.yml` is useless in this case