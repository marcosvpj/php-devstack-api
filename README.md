# php-devstack-api

Work in progress...

## First: configure local hosts to:
```
127.0.0.1       api.developatack.local
```


## After run
- install composer dependencies

## Update config files
See ``environment.config`` and files in directory ``./conf/*``.

## How to use this sample project with PHPStorm
- execute http requests
- execute phpunit tests
- execute codeception rest api tests

## Docker commands with Makefile

make build
make push
make release
make latest
make swarm
make start
make service
make test
make mail
make install
make database
make migrate

## Tests

### How to test a feature with BDD
- persona
- action
- value

### Running Units Tests with PHPUnit
bin/phpunit

### Running Api Tests with Codeception
bin/codecept run

## How to use PHPStorm with Tasks Servers
- clearly given tasks with user stories

### How to test Mail with Mailcatcher
``bash
php -r 'mail("test@example.com","Testing php -v ".phpversion(),"php on ".gethostname());'
``