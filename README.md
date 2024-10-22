# 🐳 Django Docker Deployment
## 📖 Описание проекта
Этот проект демонстрирует, как использовать Docker для развертывания Django приложения. Проект включает конфигурационные файлы Docker и Docker Compose, которые позволяют быстро развернуть приложение в контейнерах.

## 🛠️ Технологии
Django: Высокоуровневый фреймворк для веб-разработки на Python.
Docker: Платформа для разработки, доставки и эксплуатации приложений в контейнерах.
Docker Compose: Инструмент для определения и запуска многоконтейнерных Docker приложений.
## ✨ Основные функции
Контейнеризация: Изоляция приложения и его зависимостей в контейнерах.
Упрощенный деплой: Быстрое развертывание приложения на любой системе с Docker.
Легкость масштабирования: Возможность легко масштабировать приложение путем изменения настроек Docker Compose.
## 📁 Структура проекта
project/: Основная папка приложения Django
settings.py: Настройки проекта 
urls.py: Маршрутизация URL
wsgi.py: Настройки для WSGI сервера
db.sqlite3: База данных SQLite
manage.py: Командная утилита Django
Dockerfile: Конфигурационный файл Docker для сборки образа
docker-compose.yml: Конфигурационный файл Docker Compose для запуска контейнеров
requirements.txt: Список зависимостей Python
## 🏗️ Установка и запуск
Клонируйте репозиторий:

git clone https://github.com/nasirovx/deploy_django.git
Перейдите в папку проекта:

cd deploy_django
Постройте и запустите контейнеры с помощью Docker Compose:

docker-compose up --build
Приложение будет доступно по адресу:

http://localhost:8000 или http:// "ваш ipv4" :8000 
