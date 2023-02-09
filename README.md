# Сборка Docker для разработки 
<p>Внутри MySQL, PostgreSQL, Redis, PHP с установленными расширениями, xdebug и phalcon</p>

## Настройки
<p>Основные настройки - через .env файл</p>

## Хранение данных
### Сайт
<p>Разработку кладем сюда   ->  /data/site</p>

### Базы данных
<p>MySQL       ->   \data\db\mysql</p>
<p>PostgreSQL  ->   \data\db\pgsql</p>
<p>Redis       ->   \data\db\redis</p>




### Инициализация данных СУБД
<p>MySQL       ->   \mysql\initdb.d</p>
<p>PostgreSQL  ->   \pgsql\initdb.d</p>




## Расширения PHP, composer и т.д.
<p>Контейнер php-fpm</p>
<p>SSH доступен после старта сервиса</p>
<code>#service ssh start</code>
<p>Для доступа создан пользователь docker с паролем docker</p>

## Запуск
<code>$ docker-compose build</code>
<code>$ docker-compose up</code>

