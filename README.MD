# Укорачиватель ссылок

сайт, на котором любой желающий может сделать короткую ссылку для своего сайта и поделиться ей!

## Описание

сайт для укорачивания ссылок, созданный с использованием микрофреймворка Flask в рамках обучения по программе Python Pro.

## Технологии
* Python
* Flask
* WTForms
* SQLAlchemy

## Как запустить

1. Склонируйте репозиторий
2. Создайте и активируйте виртуальное окружение
```commandline
python -m venv venv
venv\Scripts\activate
```
3. Установите зависимости
```commandline
pip install -r requirements.txt
```
4. Создайте файл .env и укажите настройки подключения к БД и другие параметры.
```
DATABASE_URI=sqlite:///urls.db
SECRET_KEY=YOUR_SECRET_KEY
```
5. Запустите flask приложение
```commandline
flask run
```

## Автор проекта

_**Автор: Бояркин Егор**_
