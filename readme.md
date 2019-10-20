# Run with Docker

## command run for dev mode
``` docker-compose up -d ```

## on linux set permisiion logs
```
sudo chown -R $USER:www-data storage
sudo chown -R $USER:www-data bootstrap/cache

chmod -R 775 storage
chmod -R 775 bootstrap/cache
```

## reference
- https://gist.github.com/amitavroy/e049cf28c891d2b4220e75a88591d9d0
- https://www.digitalocean.com/community/tutorials/how-to-set-up-laravel-nginx-and-mysql-with-docker-compose
- video ; https://www.youtube.com/watch?v=MA-9FdT4Pho
