# nginx-php-mysql

A simple Docker Compose file to start nginx, php and mysql.

Edit `docker-compose.yml` to change the mysql passwords.

This expects you to put your php files/etc in `code` and the mysql data directory is `mysql` and custom mysql configurations belong in `mysql.d`

Start this with:

```bash
docker-compose up
```

Or, to fork it to the background:

```bash
docker-compose up -d
```

You can then connect to your webserver at http://localhost:8000
