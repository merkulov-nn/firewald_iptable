# firewald_iptable
Домашнее задание
Сценарии iptables

Описание/Пошаговая инструкция выполнения домашнего задания:

Что нужно сделать?

реализовать knocking port

centralRouter может попасть на ssh inetrRouter через knock скрипт

пример в материалах.

добавить inetRouter2, который виден(маршрутизируется (host-only тип сети для виртуалки)) с хоста или форвардится порт через локалхост.

запустить nginx на centralServer.

пробросить 80й порт на inetRouter2 8080.

дефолт в инет оставить через inetRouter.

Формат сдачи ДЗ - vagrant + ansible

реализовать проход на 80й порт без маскарадинга*
