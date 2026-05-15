Личный кабинет "Идеальное тело"

Демо: https://DAN-Andrey.github.io/pet_project_crm

Мобильный личный кабинет клиента студии коррекции фигуры: запись на процедуры, трекинг замеров, программа лояльности и AI-ассистент на базе GigaChat.

СТЕК:
- Frontend: React, TypeScript, Redux Toolkit, Vite
- Backend: Node.js, Express, PostgreSQL
- AI: GigaChat API

ФУНКЦИОНАЛ:
- Авторизация по JWT
- Запись на процедуры
- Трекинг замеров
- Программа лояльности
- Чат с AI-ассистентом

ЗАПУСК ЛОКАЛЬНО:

1. Клонировать репозиторий:
git clone https://github.com/DAN-Andrey/pet_project_crm.git
cd pet_project_crm

2. Установить зависимости:
cd server && npm install
cd ../client && npm install

3. Настроить окружение:
Создать файл .env в папке server по образцу .env.example

4. Создать базу данных:
cd server && npm run db

5. Запустить бэкенд (терминал 1):
cd server && npm run dev

6. Запустить фронтенд (терминал 2):
cd client && npm run dev

7. Открыть в браузере:
http://localhost:5173

СТРУКТУРА ПРОЕКТА:
pet_project_crm/
├── client/          # React + TypeScript
├── server/          # Express + PostgreSQL
├── .github/         # CI/CD
└── README.md

АВТОР:
Андрей Данковцев – fullstack-разработчик, выпускник буткемпа Эльбрус
Telegram: https://t.me/DAN_Andrey_13
GitHub: https://github.com/DAN-Andrey
