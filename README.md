# Rating Films Checker

Приложение проверяет акутальный рейтинг фильмов на сайте **https://www.imdb.com/list/ls046196709/** с помощью
_Django-Admin Command_, запуская их с помощью
_crontab_.

##### Пример Cron Job(crontab -e):
------

```
*/1 *  *   *   *   /home/dmitriy/Projects/car_price_cheker/check_many.sh
```