# Деплой веб-приложения

## Описание проекта
Простое React + Express приложение, задеплоенное на Vercel (frontend) и Railway (backend).

## Используемые платформы
- **Frontend**: Vercel
- **Backend**: Railway

## Процесс деплоя

### Backend (Railway)
1. Создала проект на Railway
2. Подключила GitHub репозиторий
3. Настроила environment variables:
   - NODE_ENV=production
   - PORT=5000
   - CLIENT_URL=frontend-url

### Frontend (Vercel)
1. Создала проект на Vercel
2. Подключила GitHub репозиторий
3. Настроила environment variables:
   - VITE_API_URL=backend-api-url

## Проблемы и решения
1. **CORS ошибки** - решила настройкой corsOptions в backend
2. **Environment variables не работали** - для Vite нужно использовать префикс VITE_
3. **SPA routing** - настроила vercel.json для redirects

## Скриншоты
[Добавь скриншоты работающего приложения]

## Ссылки
- Frontend:https:/pr25-deploy-frontend.vercel.app
- Backend API:(https://pr25-deploy-1-05y5.onrender.com)
