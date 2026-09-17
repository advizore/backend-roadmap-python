<p align="center">
  <img src="logo.png" alt="Advizore Logo" width="180"/>
</p>

<h1 align="center">🐍 Python Backend Roadmap</h1>

<p align="center">
  <b>Подробный и интересный путь от нуля до Junior Backend-разработчика</b><br>
  Сделано командой <a href="https://t.me/advizoreteam">Advizore</a> с ❤️
</p>

<p align="center">
  <a href="https://t.me/advizoreteam">
    <img src="https://img.shields.io/badge/Telegram-Advizore%20Team-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
  </a>
  <img src="https://img.shields.io/badge/Python-3.11%2B-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-Recommended-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Level-Beginner%20→%20Junior-orange?style=for-the-badge"/>
</p>

---
<div align="center">
## 🗺️ Обзор пути

| Этап | Тема                        | Время        | Сложность     |
|:----:|-----------------------------|:------------:|:-------------:|
| 0    | Подготовка                  | 1–3 дня      | ⭐            |
| 1    | Основы Python               | 2–4 недели   | ⭐⭐           |
| 2    | HTTP и API                  | 1–2 недели   | ⭐⭐           |
| 3    | FastAPI                     | 2–3 недели   | ⭐⭐⭐          |
| 4    | Базы данных                 | 2–3 недели   | ⭐⭐⭐          |
| 5    | Аутентификация              | 1–2 недели   | ⭐⭐⭐          |
| 6    | Асинхронность               | 1–2 недели   | ⭐⭐⭐⭐         |
| 7    | Тестирование                | 1 неделя     | ⭐⭐⭐          |
| 8    | Деплой                      | 1–2 недели   | ⭐⭐⭐          |
| 9    | Продвинутые темы            | по желанию   | ⭐⭐⭐⭐⭐        |
</div>
<div align="center">
## 📚 Что ещё полезно изучить

### Инструменты, без которых сейчас никуда

| Инструмент          | Зачем нужен                          | Когда учить      |
|---------------------|--------------------------------------|------------------|
| **Git & GitHub**    | Контроль версий, портфолио           | С самого начала  |
| **Docker**          | Упаковка приложения                  | После FastAPI    |
| **Postman / Insomnia** | Удобное тестирование API          | На этапе FastAPI |
| **Redis**           | Кэш, очереди, сессии                 | После БД         |
| **Nginx**           | Прокси, SSL, балансировка            | На этапе деплоя  |
| **Linux основы**    | Работа с сервером                    | Перед деплоем    |

### Полезные темы, которые сильно повышают уровень

- [ ] **Pydantic Settings** — правильная работа с конфигами и `.env`
- [ ] **Логирование** (`logging` + структурированные логи)
- [ ] **Валидация данных** на глубоком уровне
- [ ] **Пагинация, фильтрация, сортировка** (лучшие практики)
- [ ] **Фоновые задачи** (ARQ, Celery, Taskiq)
- [ ] **WebSockets** — чаты, уведомления в реальном времени
- [ ] **Очереди сообщений** (RabbitMQ / Redis Streams)
- [ ] **Кэширование** (Redis)
- [ ] **Оптимизация SQL-запросов** (N+1 проблема, индексы)
- [ ] **Безопасность**: SQL-инъекции, XSS, CSRF, Rate Limiting
- [ ] **CI/CD** (GitHub Actions)
- [ ] **Мониторинг** (Sentry + простые метрики)
</div>
---

## 🚀 0. Подготовка 

- [ ] Установить Python 3.11 или 3.12
- [ ] Поставить VS Code + расширение Python + Pylance
- [ ] Научиться создавать виртуальное окружение
- [ ] Понять `pip`, `requirements.txt` и `.gitignore`

**🎯 Мини-челлендж:**  
Напиши скрипт, который выводит «Привет, бэкенд!» и сохраняет текущее время в файл.

---

## 🐍 1. Основы Python 

**Что нужно знать:**
- Переменные, типы, условия, циклы
- Функции (`*args`, `**kwargs`, lambda)
- Списки, словари, множества, кортежи
- Работа с файлами и исключениями
- Модули, пакеты, базовое ООП
- List/Dict comprehensions и декораторы

**Ресурсы:**
- OverAPI - https://overapi.com/
- ТГК - https://t.me/pythonl

**🔥 Проект:** Консольный TODO-менеджер с сохранением в JSON.

---

## 🌐 2. HTTP и работа с API 

- [ ] JSON и CSV
- [ ] Библиотека `requests`
- [ ] Методы HTTP, статус-коды, заголовки
- [ ] Работа с публичными API

**🔥 Проект:** Бот, который проверяет погоду и записывает результат.

---

## ⚡ 3. FastAPI 

Рекомендуемый фреймворк для старта — **FastAPI**.

Порядок изучения:
1. Первый эндпоинт
2. Path & Query параметры
3. Pydantic-модели
4. Dependency Injection
5. Middleware и обработка ошибок
6. CORS

**🔥 Проект:** TODO API с CRUD, фильтрами и автодокументацией `/docs`.

---

## 🗄️ 4. Базы данных (2–3 недели)

- [ ] SQL (SELECT, JOIN и т.д.)
- [ ] PostgreSQL
- [ ] SQLAlchemy 2.0
- [ ] Alembic (миграции)
- [ ] Связи между таблицами

**🔥 Проект:** TODO API + PostgreSQL + пользователи.

---

## 🔐 5. Аутентификация (1–2 недели)

- [ ] JWT
- [ ] Хеширование паролей
- [ ] OAuth2 в FastAPI
- [ ] Защита эндпоинтов

**🔥 Проект:** Регистрация и логин. Задачи видит только владелец.

---

## ⚡ 6. Асинхронность (1–2 недели)

- `async` / `await`
- Асинхронный SQLAlchemy
- Background Tasks
- WebSockets

---

## 🧪 7. Тестирование

- `pytest` + `httpx`
- Фикстуры
- Покрытие основных эндпоинтов

---

## 🚢 8. Деплой

1. Docker + Docker Compose  
2. GitHub Actions  
3. Railway / Render / Fly.io или VPS  
4. Переменные окружения и логирование  

**Цель:** твоё API доступно по публичному URL.

---

## 🚀 9. Продвинутый уровень

- Redis
- Очереди задач (Celery / ARQ)
- GraphQL
- Чистая архитектура
- Мониторинг (Sentry)

---

## 📂 Рекомендуемый порядок проектов

1. 🖥️ Консольный TODO  
2. ⚡ FastAPI TODO (без БД)  
3. 🗄️ FastAPI + PostgreSQL + JWT  
4. 🐦 Мини-блог / Twitter API  
5. 💬 Чат на WebSockets  
6. 🛒 Бэкенд интернет-магазина  

---

## 💡 Главные советы от команды Advizore

- Не пытайся выучить всё сразу  
- Каждую неделю — одна тема + один проект  
- Пиши код руками  
- Ошибки — это нормально  
- Используй искусственный интеллект, как инструмент 

---

## 📞 Связь с нами

<p align="center">
  <a href="https://t.me/advizoreteam">
    <img src="https://img.shields.io/badge/Telegram-Написать%20команде-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Advizore"/>
  </a>
</p>

---

<p align="center">
  <b>Сделано с ❤️ командой <a href="https://t.me/advizoreteam">Advizore</a></b><br>
  Удачи в изучении Backend-разработки!
</p>
