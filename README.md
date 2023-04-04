# На Доработке ! 
### Музыкальная платформа / Music-platform

---

### Стек / Stack: 

* HTML / JSX 
* SCSS
* React
* Typescript
* NEST.JS
* NEXT.JS

---

### Этапы разработки: 

### [BACKEND]

* Проектирование диаграммы базы данных
* Сервис, Модуль, Контроллер
* Подключение к БД, описываем схему данных
* REST API, DTO
* Загрузка файлов, раздача статики, FileService
* CORS , завершение разработки сервера

### [FRONTEND] 

* создание NEXT проекта
* Верстка плеера
* Страница с поэтапным созданием трека
* Компонент для загрузки файлов
* Логика плеера, подключение Redux, Next redux wrapper
* Типизация PlayerReducer
* Кастомные хуки useActions, useTypedSelector 
* action creators
* работа с объектом Audio в браузере, проигрывание трека
* Кастомный хук useInput
* Создание трека, запрос на сервер, отправка файлов
* SEO оптимизация, head, title, meta
* Поиск треков, оптимизация запроса на поиск

---

### Backend Итоги: 

1. Есть главный AppModule, в котором подключаются все остальные модули
2. Модуль является изолированной средой, позволяет быстро ориентироваться и разрабатывать приложение 
3. В каждом модуле есть свои сервисы, схемы, контроллеры
4. В контроллерах идет работа с запросами, ответами, с клиент-серверной составляющей 
5. В схемах описываются данные, с которыми идет взаимодействие 
6. В DTO описываем объекты, которые ожидаем на вход в некоторых функциях в контроллерах
7. По итогу это все подключается в Веб-Модуль, который позже был определен как основной при запуске приложения в файле main 
8. Cors для отправки запросов с браузера 

---

### Инструкция по запуску:

* npm run start:dev - запуск сервера
* npm run dev - запуск клиента

---

### Пожалуйста, оставьте звездочку / star, если зашли в гости, мне будет приятно ) ★
