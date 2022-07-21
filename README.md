# bisht-next
Repo for holding config for bisht nextcloud instance


# Setup

1. add a postgres password to db.env

2. do a dockercompose up from the given configuration
```bash
docker-compose up -f docker-compose.yml
```

3. add the following to the config.php file under /var/www/html/config
```
  'overwriteprotocol' => 'https',
```