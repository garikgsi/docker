# Сборка Docker для разработки 
Внутри MySQL, PostgreSQL, Redis, PHP с установленными расширениями, xdebug и phalcon

## Настройки
Основные настройки - через .env файл

## Хранение данных
### Сайт
/data/site

### Базы данных
MySQL       \data\db\mysql
PostgreSQL  \data\db\pgsql
Redis       \data\db\redis

### Инициализация данных СУБД
MySQL       \mysql\initdb.d
PostgreSQL  \pgsql\initdb.d

## Расширения PHP, composer и т.д.
Контейнер php-fpm
SSH доступен после старта сервиса #service ssh start

## Запуск
$ docker-compose build
$ docker-compose up
