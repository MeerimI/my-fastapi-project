# QuizApp

## Описание
FastAPI приложение для управления викторинами.

## Запуск приложения
1. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```
2. Запустите сервер:
    ```bash
    uvicorn app.main:app --reload
    ```

## Эндпоинты
- **GET /** — Health Check
  ```json
  {
    "status_code": 200,
    "detail": "ok",
    "result": "working"
  }
