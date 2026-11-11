# Cloud Lab 01

## Технологии
- Node.js
- Express
- GitHub Codespaces

## Запуск проекта
1. Установите зависимости:
   npm install
2. Запустите сервер:
   npm start

## HTTP-маршруты
- GET / — Главная страница
- GET /api/status — Состояние сервера
- GET /api/services — Список всех сервисов
- GET /api/services/:id — Получение сервиса по ID
- POST /api/services — Добавление нового сервиса
- GET /api/hello?name=... — Приветствие