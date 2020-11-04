# prerequisites

You need to run below commands

- docker
- docker-compose

# How to launch Laravel app

```sh
docker-compose up -d server
```

then, open http://localhost:8000 on your browser.

# How to run "artisan" commands

```sh
docker-compose run --rm artisan ...
```

# How to run "npm" commands

```sh
docker-compose run --rm npm ...
```
