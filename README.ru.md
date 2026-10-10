🌐 **Русский** · [English](README.md)

# Finance Tracker

Веб-приложение для учёта личных и семейных финансов: транзакции, бюджеты, категории, повторяющиеся платежи и аналитика.

**Стек:** FastAPI · PostgreSQL 16 · React + TypeScript · Vite · Tailwind CSS · Docker Compose · Nginx

---

## Быстрый старт

**Требования:** Docker Desktop (или Docker Engine + Compose v2)

```bash
# 1. Клонируйте репозиторий
git clone <repo-url>
cd finance-tracker

# 2. Скопируйте файл окружения
cp .env.example .env

# 3. Запустите проект
docker compose up --build
```

Готово. При первом запуске backend автоматически загружает тестовые данные.

---

## Ссылки

| Что | URL |
|---|---|
| Фронтенд | http://localhost:5173 |
| Бэкенд (API) | http://localhost:3000 |
| Swagger UI | http://localhost:3000/docs |

---

## Тестовые учётные записи

| Email | Пароль | Описание |
|---|---|---|
| `personal@example.com` | `password123` | Личный бюджет (Иван Личный) |
| `family@example.com` | `password123` | Семейный бюджет (Семья Петровых) |

---

## Разделы приложения

| Раздел | Описание |
|---|---|
| **Dashboard** | Обзор баланса, доходов и расходов за период |
| **Transactions** | Список транзакций с фильтрацией и сортировкой |
| **Categories** | Управление категориями доходов и расходов |
| **Budgets** | Лимиты по категориям и отслеживание выполнения |
| **Recurring** | Повторяющиеся платежи |
| **Reports** | Графики и аналитика по периодам |

---

## Документация проекта

| Файл | Содержимое |
|---|---|
| [`ARCHITECTURE.md`](ARCHITECTURE.md) | Схема БД, структура проекта, REST API, Docker Compose |
| [`report/REPORT.md`](report/REPORT.md) | Журнал разработки |
| [`report/PROMPTS.md`](report/PROMPTS.md) | История промптов |
