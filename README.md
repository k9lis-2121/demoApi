# demoApi
Тестовое задание

Этот проект реализует простое CRUD API управления списком пользователей, с валидацией полей. 

Для запуска необходимы: php-8.1, php8.1-pdo-mysql, mysql, composer, symfony-cli

Выполните<br>
`composer install`<br><br>
Создайте файл .env.local и укажите в нем:<br>
`DATABASE_URL="mysql://login:pass@127.0.0.1:3306/nameTable?serverVersion=8&charset=utf8"`<br><br>
Создайте таблицу<br>
`php bin/console doctrine:database:create`<br><br>
Выполните миграцию<br>
`php bin/console doctrine:migrations:migrate`<br><br>
Запустите сервер<br>
`symfony server:start -d`<br><br>
_Ключ -d запускает сервер в фоне, если хотите наблюдать работу сервера в консоли, не указывайте этот параметр_<br>
<br><br>
Приложение готово к работе!<br>
Ознакомится с API можно по адресу<br>
`https://YourDomainOrIP:8000/api`
