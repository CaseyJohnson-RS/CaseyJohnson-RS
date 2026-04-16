# Шамухаметов Руслан

Студент. Ищу первую работу / стажировку: **Junior Python Backend**.
Коммерческого опыта пока нет — всё ниже это pet-проекты.

---

## Стек

**Уверенно использую:**
- Python 3.12, FastAPI, Pydantic
- SQLAlchemy 2 (async), Alembic, PostgreSQL (+ pgvector)
- Redis
- pytest
- Docker, Docker Compose
- JWT, Argon2 / bcrypt, SSE-стриминг

**Пробовал, не эксперт:**
Nginx (как reverse proxy), RAG / эмбеддинги, React + TypeScript
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
Приложение для заметок с AI-ассистентом и семантическим поиском.
Бэкенд: модульный монолит на FastAPI (модули `auth / notes / tags / rag / ai / admin`), фоновый воркер для эмбеддингов и очистки, RAG через pgvector, SSE-стриминг ответов LLM, JWT с refresh-токенами, rate limiting, Alembic-миграции, seed админа, тесты на pytest.
Весь стек поднимается через `docker compose up`.

**Python · FastAPI · PostgreSQL + pgvector · Redis · Alembic · Nginx · Docker**

### [Auth-Service-Hexagonal](https://github.com/CaseyJohnson-RS/Auth-Service-Hexagonal)
Учебный сервис аутентификации — разбор гексагональной архитектуры на практике: JWT, refresh-токены, подтверждение email, сброс пароля, журнал security-событий.

**FastAPI · PostgreSQL (async) · Alembic · Docker**

### [Symptoms](https://github.com/CaseyJohnson-RS/Symptoms)
Unity-проект на C#. Побочный интерес.

---

## Связь

- Telegram — [@casey_johnson](https://t.me/casey_johnson)
- VK — [casey_johnson](https://vk.com/casey_johnson)
