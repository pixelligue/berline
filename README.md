# Berline Project

## Структура проекта

### Frontend (React + Vite)
- `/frontend` - React приложение

### Backend (Django)
- `/backend` - Django приложение

## Установка и запуск

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # На Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```