### Использовались фреймворки, библиотеки и БД:\
Frontend: React 18, Redux Toolkit, Bootstrap, Axios\
Backend: Node.js, Express.js, Mongoose, MongoDB\

### Функционал приложения:

1. Пользовательский интерфейс\
   1.1. Логирование и регистрация пользователей\
   1.2. Личный кабинет с возможностями\
   1.2.1. Создавать, редактировать и удалять посты\
   1.2.2. Редактировать свои данные\
   1.3. Писать, читать и удалять (удалять только свои) комментарии под постами всех пользователей и ставить лайки\
   1.4. Для незарегистрированных пользователей возможность читать посты и комментарии\
2. Серверная часть\
   2.1. Присваивает случайную аватарку вновь зарегистрированному пользователю\
   2.2. При удалении пользователем поста, удаляет с БД все данные о комментариях и лайках к этому посту\

Чтобы запустить приложение нужно настроить /server/config/default.json - прописать connection string MongoDB Atlas\

/clent запустить команду npm start
/server запустить команду npm run dev
