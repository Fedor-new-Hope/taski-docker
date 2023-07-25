# taski-docker

```
Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Fedor-new-Hope/taski-docker.git
```

```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

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