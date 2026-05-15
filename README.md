markdown
# 💪 Личный кабинет «Идеальное тело»

**Демо:** https://DAN-Andrey.github.io/pet_project_crm

Мобильный личный кабинет клиента студии коррекции фигуры: запись на процедуры, трекинг замеров, программа лояльности и AI-ассистент на базе GigaChat.

---

## 🛠️ Стек

- **Frontend:** React, TypeScript, Redux Toolkit, Vite, React Router
- **Backend:** Node.js, Express, PostgreSQL
- **AI:** GigaChat API
- **Деплой:** GitHub Pages, Render, Neon

---

## 📱 Функциональность

- Авторизация по JWT
- Запись на процедуры (календарь)
- Трекинг замеров тела
- Программа лояльности
- Чат с AI-ассистентом

---

## 🚀 Запуск локально

### Требования
- Node.js 20+
- PostgreSQL 15+

### Шаги

1. Клонировать репозиторий
```bash
git clone https://github.com/DAN-Andrey/pet_project_crm.git
cd pet_project_crm
Установить зависимости

bash
cd server && npm install
cd ../client && npm install
Настроить окружение
Создать файл .env в папке server по образцу .env.example

Создать базу данных

bash
cd server && npm run db
Запустить (два терминала)

Терминал 1 (бэкенд):

bash
cd server && npm run dev
Терминал 2 (фронтенд):

bash
cd client && npm run dev
Открыть в браузере

text
http://localhost:5173
📁 Структура
text
pet_project_crm/
├── client/          # React + TypeScript
├── server/          # Express + PostgreSQL
├── .github/         # CI/CD
└── README.md
