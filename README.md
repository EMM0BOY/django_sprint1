# Blogicum
## Описание проекта:
Blogicum - учебный проект, имитирующий социальную сеть для публикации личных дневников.<br/>
Это веб-сайт, на котором пользователь может создать свою страницу и публиковать на ней сообщения («посты»).<br/>
Для каждого поста нужно указать категорию — например «путешествия», а также опционально локацию, с которой связан пост.<br/> 
Пользователь может перейти на страницу любой категории и увидеть все посты, которые к ней относятся.<br/>
Также пользователи могут заходить на чужие страницы, читать и комментировать чужие посты.<br/>

## СТЕК технологий:
* Python == 3.10.12
* Django == 3.2.16

## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

```sh
git clone git@github.com:FeodorPyth/django_sprint1.git
```

```sh
cd django_sprint1
```

Cоздать и активировать виртуальное окружение:

```sh
python3 -m venv venv
```

```sh
source venv/bin/activate
```

Установить зависимости из файла requirements.txt:

```sh
python -m pip install --upgrade pip
```

```sh
pip install -r requirements.txt
```

Выполнить миграции:

```sh
python manage.py migrate
```

Запустить проект:

```sh
python manage.py runserver
```

