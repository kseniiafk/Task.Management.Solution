<img width="2787" height="1375" alt="image" src="https://github.com/user-attachments/assets/cad5aeca-4903-435a-85ef-9eae12e4ed97" />
<img width="2543" height="1214" alt="image" src="https://github.com/user-attachments/assets/76dca5b6-e5ad-4198-9002-ef1705689fb8" />
<img width="2614" height="1329" alt="image" src="https://github.com/user-attachments/assets/991ea2a0-ac85-4363-bf94-f208e7fcc5a0" />

Технологии
Python

http.server (сервер)

requests (клиент)

JSON

Файлы проекта
server.py — серверная часть

client.py — клиентская часть

requirements.txt — зависимости проекта

Функционал сервера
GET / — возвращает информацию о сервере и текущее время

POST /data — принимает JSON-данные, возвращает результат обработки

Порт: 8080

Корректные HTTP-ответы с заголовками

Функционал клиента
Отправка GET-запросов

Отправка POST-запросов с JSON-данными

Обработка ответов сервера

Обработка возможных ошибок

Запуск проекта
Установить зависимости:

pip install -r requirements.txt

Запустить сервер:

python server.py

Запустить клиент:

python client.py
