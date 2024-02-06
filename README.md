## Описание
Данный проект представляет из себя социальную сеть, в которой доступен следующий функционал:

* Создние поста
* Возможность прокомментировать чей-либо пост
* Подписаться или отписаться на какого-либо автора

### Используемые технологии:

* Python 3.11.3
* Django 3.2.16
* Django Rest Framework 3.12.4
* JWT + Joser

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/maximpontryagin/api_final_yatube.git
```

```
cd API_FINAL_YATUBE
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py makemigrations
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
