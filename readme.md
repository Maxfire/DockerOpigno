# Basic Docker distribution Opigno LMS 2.2

To install it just run:

```
docker-compose up
```

In the project directory, afterwards go into docker by doing:

```
docker exec -ti {DOCKER_NAME} bash
```

And install TinCanPHP via Composer:

```
composer require rusticisoftware/tincan:@stable
```

Follow the instructions and that's it!, easy right?.

NOTE: db set up:
* database name `local_drupal`;
* dabatase user `drupal`;
* database password `drupal`;
* database host `db`.

