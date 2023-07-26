# UsedSell
Площадка для продажи подержаных вещей
## Стек:
    - python3.10,
    - Django 3.2.6,
    - Postgres 12.4-alpine

### Установка зависимостей

Выполнить следующую команду в терминале:\
`pip install -r requirements.txt`

### Запуск приложения

Перейти в папку market_postgres и выполнить команду:\
`docker-compose up --build`\
Перейти в папку skymarket и выполнить команду:\
`python .\manage.py runserver`\
Приложение доступно по адресу:\
`http://127.0.0.1:3000/`
