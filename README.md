# Шамухаметов Руслан

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-async-009688?logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-pgvector-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-cache%20%2F%20pubsub-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?logo=docker&logoColor=white)
![CI](https://img.shields.io/badge/CI-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

Студент. Ищу первую работу / стажировку: **Junior Python Backend**.
Коммерческого опыта пока нет — всё ниже это pet-проекты.

---

## Стек

**Уверенно использую:**
- Python 3.12, FastAPI, Pydantic v2
- SQLAlchemy 2 (async), Alembic, PostgreSQL (+ pgvector)
- Redis
- pytest (unit + интеграционные через httpx)
- Docker, Docker Compose
- JWT, refresh-токены с ротацией, bcrypt, SSE-стриминг
- RAG / эмбеддинги (pgvector, фоновые воркеры)

**Пробовал, не эксперт:**
React + TypeScript
(фронт для своих проектов пишу, но бэкенд — основная область)

**В планах:** Kafka, Kubernetes

---

## Чем интересно заниматься

- Чистая архитектура, модульная декомпозиция
- Сервисы с LLM / RAG на бэкенде (стриминг, фоновые воркеры)
- Асинхронный Python и работа с БД под нагрузкой

---

## Проекты

### [Nocturn](https://github.com/CaseyJohnson-RS/Nocturn)

Веб-приложение для заметок с AI-ассистентом, который умеет создавать и
редактировать заметки из чата, и семантическим поиском.

Бэкенд: FastAPI с модульной декомпозицией (`auth / notes / tags / rag / ai / admin`),
фоновый воркер для эмбеддингов и очистки, RAG через pgvector, SSE-стриминг ответов
LLM, JWT с refresh-токенами, rate limiting на Redis, CI/CD с автодеплоем.

Живая демка + поднимается через `docker compose up`.

**Python · FastAPI · PostgreSQL + pgvector · Redis · Alembic · Nginx · Docker · CI/CD**

### [Hexagonal-Auth-Service](https://github.com/CaseyJohnson-RS/Hexagonal-Auth-Service)

Сервис аутентификации на гексагональной архитектуре: доменное ядро без зависимостей
от фреймворков, порты на `Protocol`. Полный цикл — регистрация, подтверждение email,
ротация refresh-токенов с детектом повторного использования, восстановление пароля,
журнал security-событий через Redis. Оптимистичные блокировки, токены только в виде
SHA-256-хэшей, покрытие тестами на всех уровнях, CI.

**FastAPI · PostgreSQL (async) · Redis · Alembic · Docker · pytest**

---

## Связь

- Telegram — [@shamukhametov](https://t.me/shamukhametov)
- VK — [casey_johnson](https://vk.com/casey_johnson)
