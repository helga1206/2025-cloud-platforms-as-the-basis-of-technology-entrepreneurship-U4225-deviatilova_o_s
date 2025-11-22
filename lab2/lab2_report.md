University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2025/2026
Group: U4125
Author: Deviatilova Olga
Lab: Lab2
Date of create: 22.11.2025
Date of finished: 24.11.2025

# Лабораторная работа №2

## 1. Создала Cloud Run контейнер с именем hello-service

![](screen1.jpg)

![](screen2.jpg)

## 2. Протестировала сервис в браузере

![](screen3.jpg)

## 3. Посмотрела логи и метрики, увидела, что контейнер запускается, ошибок нет

![](screen4.jpg)

![](screen5.jpg)

![](screen6.jpg)

## 4. Затем создала новую версию и изменила порт на 8090

![](screen7.jpg)

![](screen8.jpg)

## 5. После проверила работу и выдалась ошибка

![](screen9.jpg)

## 6. Задала переключение трафика
Решила сделать распределение 50/50 между первой и второй версиями, в результате чего, если открывался запрос через первый - то все шло успешно, а через второй - с ошибкой.

![](screen10.jpg)

![](screen11.jpg)

## 7. Удаление созданного сервиса

![](screen12.jpg)

![](screen13.jpg)
