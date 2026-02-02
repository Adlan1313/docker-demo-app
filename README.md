# Dockerized FastAPI App on Yandex Cloud

## Описание
Это простой FastAPI сервис, который был запущен на виртуальной машине в Yandex Cloud и упакован в Docker контейнер.  
Проект демонстрирует навыки:
- Создание виртуальной машины в Yandex Cloud
- Установка и настройка Docker
- Контейнеризация приложения
- Запуск и проверка сервиса через веб

---

## Структура проекта

- `app/` — приложение на FastAPI
- `Dockerfile` — контейнеризация
- `requirements.txt` — Python зависимости
- `README.md` — документация

---

## Как запустить локально

1. Склонируй репозиторий
```bash
git clone https://github.com/USERNAME/docker-demo-app.git
cd docker-demo-app

2. Собери Docker образ
docker build -t docker-demo-app:1.0 .

3. Запусти контейнер
docker run -d --name demo-app -p 80:8000 docker-demo-app:1.0

4. Проверь работу
Главная страница: http://<IP_вашей_ВМ>/


