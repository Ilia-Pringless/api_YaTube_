# API_final

API для работы с сервисом Ya_tube

### Как запустить проект:

* Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```
```
source env/bin/activate
```
* Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

* Выполнить миграции:

```
python3 manage.py migrate
```

* Запустить проект:

```
python3 manage.py runserver
```

### ♦ Примеры некоторых Get - запросов к API:

> http://127.0.0.1:8000/api/v1/posts/
>> Получение публикаций.

> http://127.0.0.1:8000/api/v1/groups/
>> Список сообществ.

> http://127.0.0.1:8000/api/v1/follow/
>> Возвращает все подписки пользователя, сделавшего запрос.

