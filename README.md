# 💪 Личный кабинет «Идеальное тело»

Личный кабинет клиента студии коррекции фигуры: запись на процедуры, трекинг замеров, программа лояльности и **AI-ассистент на базе GigaChat**.


---

## 📱 О проекте

Это полноценный **fullstack-пет-проект**, который я сделал после буткемпа Эльбрус. Клиентская часть — адаптивное SPA, серверная — REST API с PostgreSQL.

### Что умеет приложение:

| Функция | Описание |
|---------|----------|
| 🔐 **Авторизация** | JWT-токены, защищённые маршруты |
| 📅 **Запись на процедуры** | Календарь с доступными слотами |
| 📏 **Трекинг замеров** | Графики прогресса, история изменений |
| 🎁 **Программа лояльности** | Баллы, скидки, уровни |
| 🤖 **AI-ассистент** | Интеграция с GigaChat (чат-бот с советами) |

---

## 🛠️ Стек технологий

### Фронтенд
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)

### Бэкенд
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### Инструменты и деплой
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

---

## 🚀 Запуск проекта локально

### Требования
- Node.js 20+
- PostgreSQL 15+

### Инструкция

1. **Клонируй репозиторий**
```bash
git clone https://github.com/DAN-Andrey/pet_project_crm.git
cd pet_project_crm

2. **Установить зависимости**
```bash
cd server && npm install
cd ../client && npm install

3. **Настроить окружение**
Создать файл .env в папке server по образцу .env.example

4. **Создать базу данных**
```bash
cd server && npm run db
