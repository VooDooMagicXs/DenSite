Для того, чтобы запустить эту ебалду:

# npm start
Запускает сервер с помощью команды node server.js
Используйте npm start, когда хотите запустить сервер в продакшн-режиме (например, на сервере или в финальной версии приложения).
Эта команда просто запускает сервер без дополнительных функций, таких как автоматический перезапуск при изменении файлов.
# npm run dev
Запускает сервер с помощью nodemon server.js
nodemon — это утилита, которая автоматически перезапускает сервер при изменении файлов
Используйте npm run dev, когда работаете над проектом в режиме разработки.

Сайт будет по адресу http://localhost:3000/

.env example:  (создать .env в корне)
TELEGRAM_BOT_TOKEN=your-bot-token-here
TELEGRAM_CHAT_ID=your-chat-id-here
