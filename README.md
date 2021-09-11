# Catbox (ныне Catbox LTS)
Проект группы мини-приложений в одном сайте (ранее Catbin)<br>
Из-за неизвестного конфликта с Максимом Жуйковым, вся команда CBXGroup приняла решение о закрытие проекта Catbox.<br>
Поэтому я решил сделать проект опенсурс-ным.<br><br>
Работает на PHP, SQL, JS, HTML, CSS

<b>UPD 12.08.2021:</b> Catbox продолжит своё развитие, под форком https://github.com/MaksimMohooks/Catbox и статусом LTS.<br>
<b>UPD 08.09.2021:</b> Catbox LTS меняет лицензию на MIT License<br>
<b>UPD 11.09.2021:</b> Обновления главного репизитория itsyuni/Catbox до версии LTS 1.1

## Как поставить Catbox на свой сервер?
- Легко, загружаем файлы на сервер, а на MySQL сервер импортируем файл CatboxDB.sql это наша БД.
- А в /classes/DB.php меняем данные базы данных на Ваши.
- И всё, у вас собственный инстанс Catbox ;)

## Требования к серверу
- PHP 7 или 8 версии
- Любая версии MySQL (желателен PMA для удобства)
- И думаю, прямые руки, ведь ничего сложного
