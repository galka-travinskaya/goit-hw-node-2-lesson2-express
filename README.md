# goit-hw-node-2-lesson2-express

1. создаем package.json - npm init -y
2. package.json добавляем "type": "module" для импортов
3. npm install nodemon -DE
4. npm install commander
5. npm i express morgan cors got -E
6. npm i dotenv -E
7. npm install --save express-validator
8. npm install -E express-validator

1. 0.03 app.js
2. 0.04 folder routes/api/weather.js
3. 0.07 axios ft. got
4. 0.09 logger morgan - помогает понят что на какой раутинг пошло и как работало
5. 0.10 подключаем cors
6. 0.11 обработчик ошибок 
7. 0.16 не запуск сервера в app.js
8. 0.18 folder bin/server.js
9. 0.19 подключаем порт
10. 0.20 подключаем morgan
11. 0.21 пишем скрипты start, start:dev
12. 0.23 express.Router
13. 0.24 weather.js
14. 0.28 подключаем роуты в апп
15. 0.30 обработчик ошибок
16. 0.41 [https://home.openweathermap.org/api_keys]
17. 0.42 files .env, .env.example
18. 0.43 file .gitignore
19. 0.45 weather.js - выдаем погоду
20. 0.46 dotenv - позволяет перетаскивать переменные окружения и помещать в process.env
21. 0.49 добавляем в weather.js got
22. 0.51 res.query
23. 0.54 соединяем req в response
24. 0.57 исправляем ошибку
25. 1.03 достаем только name, weather, clouds
26. 1.04 валидация данных [express-validator] - [https://express-validator.github.io/docs/]
27. 1.18 heroku
28. 1.20 для примера репа с проектом на всех языках [https://github.com/gothinkster/realworld]