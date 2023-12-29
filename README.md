# 932021.Martunov.K.lab12

Лабораторная работа №12 по предмету Web-технологии Цель работы: Работа с HTML-формами

Описание:
•	Создание HTML-форм в ASP.NET Core.
•	Использование расширений HtmlHelper для создания компонентов форм.
•	Использование Tag Helpers для создания компонентов форм.
•	Обработка полученных с Web-страницы данных.
•	Механизм Model Binding.

Задание: Для двух чисел необходимо реализовать сервис для выполнения 4 базовых операций (сложение, вычитание, умножение, деление). Необходимо предусмотреть обработку ошибок (деление на ноль).


# Requirements
- PHP 8.2
- Composer
- Docker

# How to install
1) Установить composer по инструкции с официального сайта: https://getcomposer.org/download/
2) Установить docker по инструкции с официального сайта: https://docs.docker.com/engine/install/
3) Открыть докер и дождаться его запуска, должно открыться следующее окно:
![image]([https://github-production-user-asset-6210df.s3.amazonaws.com/50704060/289779901-191f2e21-e11f-4ebb-b642-289863e8a0d4.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20231229%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231229T171917Z&X-Amz-Expires=300&X-Amz-Signature=0f04fe5d45c29529a0fbb1de4284c588653fc8710ab76862a98808f25afda576&X-Amz-SignedHeaders=host&actor_id=125989850&key_id=0&repo_id=730560215])
4) Склонировать данный репозиторий через терминал PhpStorm, либо консоль, предварительно убедитесь, что вами выбрана верня директория <br>
(`git clone [https://github.com/Siaelnodel/932021.Martunov.K.lab11.git]`)
5) `cd 932021.Martunov.K.lab11`
6) `composer update`
7) `composer install`
8) `docker compose up --build -d`
9) `docker exec -it uca-php bash`
10) `chmod -R 777 /var/www`
11) Открыть `http://localhost:2003`
