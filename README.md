# app_shift_project
Тестовое задание ШИФТ курс Python
REST-service просмотра текущей зарплаты и даты следующего повышения.

stack:
- Python
- FastAPI
- SQLite

Запуск python3 evrone_fastapi/service/main.py
Добавляем сотрудника через POST /user/signup -> сохраняется в базу данных
Получаем токин через POST /user/signin -> токен действует 2 мин
Что бы получить сведения о сотруднике проходим авторизацию в POST /user/salary и в теле запроса отправляем свой id

