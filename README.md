# 🧪 Мини-проект: Тестирование REST API (FastAPI + Postman)

## 📌 Описание

Небольшой учебный проект, в котором я:

- развернул API-сервер на **FastAPI**
- протестировал его вручную через **Postman**
- проверил все основные CRUD-операции

---

## ⚙️ Что реализовано

| Метод  | URL           | Назначение                 |
|--------|---------------|----------------------------|
| GET    | `/tasks`      | Получить список задач      |
| GET    | `/tasks/{id}` | Получить задачу по ID      |
| POST   | `/tasks`      | Создать новую задачу       |
| PUT    | `/tasks/{id}` | Обновить задачу            |
| DELETE | `/tasks/{id}` | Удалить задачу             |

---

## 🛠️ Технологии

- Python + FastAPI
- Postman
- Ручное тестирование
- Markdown

---

## ✅ Проверено вручную

- Успешное создание, редактирование и удаление задач
- Ошибки при дубликатах или несуществующих ID
- Проверка кодов ответа: `200 OK`, `400 Bad Request`, `404 Not Found`
- Swagger-документация
- Скриншоты в папке `/assets/screens`

---

## 📸 Скриншоты

### 🧭 Swagger UI

![Swagger UI](assets/screens/swagger_ui_endpoints.png)

---

### 📤 Успешные запросы

#### POST /tasks (создание задачи)

![Создание задачи](assets/screens/post_create_task_id2_success.png)

#### PUT /tasks (обновление задачи)

![Обновление задачи](assets/screens/post_task_update.png)

#### DELETE /tasks/2 (удаление задачи)

![Удаление задачи](assets/screens/delete_task_success.png)

#### GET /tasks (получение всех задач)

![Получение всех задач](assets/screens/get_all_tasks_success.png)

---

### ❌ Ошибки

#### POST /tasks (дублирующий ID)

![Ошибка дублирующего ID](assets/screens/post_duplicate_id_error.png)

---

### 🖥️ Сервер

#### Логи терминала при тестировании

![Серверные логи](assets/screens/server_logs_terminal.png)

---
## 📂 Структура
- `main.py` — код сервера
- `README.md` — описание
- `assets/` — скриншоты


---

🎯 Цель проекта
Закрепить практику работы с:

API и методами HTTP

ручным тестированием в Postman

Markdown-документацией



🎯 Проект сделал, чтобы закрепить практику работы с API, ручным тестированием и базовой документацией.
