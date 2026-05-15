# 💪 Личный кабинет «Идеальное тело»

**Демо:** https://DAN-Andrey.github.io/pet_project_crm

Полноценная система для студии коррекции фигуры:

- **Клиентский личный кабинет:** запись на процедуры, трекинг замеров, программа
  лояльности, AI-ассистент (GigaChat)
- **Админ-панель:** управление процедурами, просмотр записей клиентов, редактирование
  замеров, настройка программы лояльности

---

## 🛠️ Стек

- **Frontend:** React, TypeScript, Redux Toolkit, Vite, React Router
- **Backend:** Node.js, Express, PostgreSQL
- **AI:** GigaChat API

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

```

2. Установить зависимости

```bash
cd server && npm install
cd ../client && npm install

```

3. Настроить окружение Создать файл .env в папке server по образцу .env.example

---

4. Создать базу данных

```bash
cd server && npm run db
```

5. Запустить (два терминала)

Терминал 1 (бэкенд):

```bash
cd server && npm run dev
```

Терминал 2 (фронтенд):

```bash
cd client && npm run dev
```

---

6. Открыть в браузере

http://localhost:5173

---

📁 Структура

```text

pet_project_crm/
├── client/          # React + TypeScript
├── server/          # Express + PostgreSQL
├── .github/         # CI/CD
└── README.md
```
