💪 Личный кабинет «Идеальное тело»
Демо: https://DAN-Andrey.github.io/pet_project_crm

Мобильный личный кабинет клиента студии коррекции фигуры: запись на процедуры, трекинг замеров, программа лояльности и AI-ассистент на базе GigaChat.

🛠️ Стек
Frontend: React, TypeScript, Redux Toolkit, Vite, React Router
Backend: Node.js, Express, PostgreSQL
AI: GigaChat API
Деплой: GitHub Pages (frontend), Render (backend), Neon (PostgreSQL)
📱 Функциональность
Авторизация по JWT
Запись на процедуры (календарь с доступными слотами)
Трекинг замеров тела (графики прогресса)
Программа лояльности (баллы, уровни)
Чат с AI-ассистентом на базе GigaChat
🚀 Запуск локально
Требования
Node.js 20+
PostgreSQL 15+
Шаги
Клонировать репозиторий

git clone https://github.com/DAN-Andrey/pet_project_crm.git
cd pet_project_crm
Установить зависимости

cd server && npm install
cd ../client && npm install
Настроить окружение

Создать файл .env в папке server по образцу .env.example

Создать базу данных

cd server && npm run db
Запустить (два терминала)

Терминал 1 (бэкенд):

cd server && npm run dev
Терминал 2 (фронтенд):

cd client && npm run dev
Открыть в браузере

http://localhost:5173
📁 Структура
pet_project_crm/
├── client/          # React + TypeScript
├── server/          # Express + PostgreSQL
├── .github/         # CI/CD (GitHub Actions)
└── README.md
👤 Автор
Андрей Данковцев – fullstack-разработчик, выпускник буткемпа Эльбрус

Telegram • GitHub
