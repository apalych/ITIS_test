## Тестовый проект для прохождения курса ITIS-Upgrade
Данный проект отвечает на три вопроса:
1. Посетители из какой страны совершают больше всего действий на сайте?
2. Посетители из какой страны чаще всего интересуются товарами из определенных категорий?
3. В какое время суток чаще всего просматривают определенную категорию товаров?

Все необходимые зависимости указаны в файле `requirements.txt`.
Для проверки работоспособности необходимо проделать следующее:
1. Установить необходимые библиотеки:
```python
pip3 install -r requirements.txt
```
2. Сгенерировать базу данных из логов:
```python
python create_db.py
```
3. Запустить основную программу:
```python
export FLASK_APP=app.py
```
```python
flask run
```
4. Зайти на запущенный веб-сервер по адресу `127.0.0.1:5000`, либо по адресу: `localhost:5000` и проверить работоспособность

