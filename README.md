# 🧩 Task Tracker API

This is a simple REST API built with FastAPI that allows you to manage tasks (like a to-do list). It supports common CRUD operations and automatically generates documentation via Swagger UI.

## 🚀 Features
- Create new tasks
- View all tasks
- Update existing tasks
- Delete tasks
- Built-in Swagger UI for easy testing

## 🛠️ Technologies Used
- Python
- FastAPI
- Uvicorn (ASGI server)
- Pydantic (for data validation)

## ▶️ How to Run Locally

1. Clone the repository and navigate to the project folder.
2. Install the dependencies:
   ```bash
   pip install fastapi uvicorn
   ```

3. Run the application:
   ```bash
   uvicorn task_tracker_api_main:app --reload
   ```

4. Open your browser:
   - Swagger UI: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)
   - Redoc: [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

## 📦 Sample JSON

```json
{
  "id": 1,
  "title": "Submit resume",
  "completed": false
}
```

## 📫 Endpoints

| Method | Endpoint        | Description         |
|--------|------------------|---------------------|
| GET    | `/tasks`         | Get all tasks       |
| POST   | `/tasks`         | Create a new task   |
| PUT    | `/tasks/{id}`    | Update a task       |
| DELETE | `/tasks/{id}`    | Delete a task       |

---

Feel free to fork, test, and extend this project!
