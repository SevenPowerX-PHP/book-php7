# PHP7
Максим Кузнецов, Игорь Симдянов.

> Новинки PHP 7
> Шаблоны проэктирования, итераторы и генераторы
> Приёмы работы с СУБД PostgresSQL
> Взаимодействие с базами данных NoSQL(Redis)

Исходные коды: https://github.com/igorsimdyanov/phpworkshop

Вопроссы: https://github.com/igorsimdyanov/phpworkshop/issue

Электронный архив с исходными кодами к книге также можно скачать по ссьmке
ftp:l/ftp.bhv.ru/9785977538176.zip

## PHPServer

php -S localhost:4000 - Запускаем server на 4000 port
http://localhost:4000/
Ctr + C Останавливаем server
для Linux :
sudo php -S localhost:80 -t web
> если уже запущен например Веб-сервер apache то нужно остановить 
> параметр -t можно настроить папку с которой запускается сайт webroot папку
> прописываем в host файле 
> Unix - /etc/hosts 
> Windows - С:\Windows\systemЗ2\drivers\etc\hosts
> псевдонимы
> 127.0.0.1         site.dev
> 127.0.0.1       www.site.dev
> 127.0.0.1         site.loc
> 127.0.0.1       www.site.loc
> 127.0.0.1         site.local
> 127.0.0.1       www.site.local

После добавления новых псевдонимов в host файл их можно использовать совме­стно со встроенным сервером, например http://site.dev:4000/.

> php-S 0.0.0.0:4000 -t web -c /etc/php/7.2/php.ini

