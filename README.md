### Описание:

Это API к учебному проекту социальной сети yatube.

С помощью api_yatube можно публиковать записи, комментировать записи, а так же подписываться или отписываться от авторов.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Slexvik/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

### Список эндпоинтов:

доступен по адресу http://127.0.0.1:8000/api/v1/

## Документация

 http://127.0.0.1:8000/redoc/
