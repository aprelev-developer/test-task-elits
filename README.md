Приложение для Обратной Связи

Это простое веб-приложение на PHP, которое позволяет пользователям отправлять обратную связь через форму. Приложение валидирует ввод, сохраняет его в базу данных и отправляет уведомление по электронной почте.
Содержание

    Особенности
    Требования
    Установка
    Использование
    Структура файлов
    Настройка Базы Данных

Особенности

    Форма обратной связи с полями электронной почты и сообщения.
    Валидация данных формы.
    Сохранение обратной связи в базе данных MySQL.
    Отправка уведомлений по электронной почте.

Требования

    PHP
    MySQL
    Веб-сервер (например, Apache, Nginx)

Установка

    Клонируйте репозиторий на свой локальный компьютер.
    Настройте веб-сервер и настройте его для обслуживания приложения.
    Настройте базу данных, импортировав предоставленный SQL-файл (feedback_db.sql) в вашу базу данных MySQL.

Использование

    Доступ к приложению осуществляется через веб-сервер.
    Заполните форму обратной связи действительным адресом электронной почты и сообщением.
    Отправьте форму.
    Приложение выполнит валидацию ввода, сохранит его в базе данных и отправит уведомление по электронной почте.

Структура Файлов

    Model/FeedbackForm.php: Содержит класс FeedbackFormModel для обработки данных обратной связи.
    Controller/index.php: Обрабатывает отправку формы и взаимодействует с моделью.
    css/main.css: Основной файл стилей для оформления HTML-страниц.
    css/font-style.css: Файл стилей для пользовательских шрифтов.
    index.html: HTML-файл, содержащий форму обратной связи и другой контент.

Настройка Базы Данных

    Название Базы Данных: feedback_db
    Подключение к Базе Данных: MySQL, настроено в конструкторе FeedbackFormModel.
