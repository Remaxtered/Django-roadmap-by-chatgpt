Общая стратегия
---------------

* Учимся по мере возникновения проблем и задач — "решать по мере поступления".
* Параллельно осваиваем связанные технологии (Git, Docker, Redis, Celery, DRF).
* Проекты максимально приближены к реальной работе и тестовым заданиям для собеседований.
* Постепенно переходим от простых приложений к полноценным системам.

Roadmap по Django
=================

### Уровень 1\. Основы Django и практическая базовая реализация

Цель: понять архитектуру Django, создать первый проект, реализовать CRUD с авторизацией.

| Микротема | Описание | Pet-проект | Полезная статья/видео |
| --- | --- | --- | --- |
| 1\. Установка и базовая настройка Django | Создание проекта и приложения | -   | [Django beginner tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Tutorial_local_library_website) (часть 1) |
| 2\. Разбор архитектуры: MVT (Model-View-Template) | Теория и принципы | -   | [Django Architecture](https://realpython.com/django-architecture/) |
| 3\. Создание моделей, миграции, админка | Модели и CRUD | Каталог товаров | [Creating Models & Admin](https://docs.djangoproject.com/en/4.2/intro/tutorial02/#creating-models) |
| 4\. Работа с шаблонами (Jinja / Django Templating Language) | Шаблоны и теги | Каталог товаров | [Django Templates](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Template_language) |
| 5\. Авторизация и регистрация | Пользователи, login/logout | Сайт с авторизацией | [User Authentication](https://auth0.com/blog/user-authentication-with-django/) |

### Уровень 2\. Расширение навыков, ООП, формы, CBV

Цель: научиться работать с классами, CBV, формами, реализовать расширенный CRUD.

| Микротема | Описание | Pet-проект | Полезная статья/видео |
| --- | --- | --- | --- |
| 6\. Класс Based Views (CBV) | От обычных функций к классам | Каталог с фильтрацией | [Django Class-Based Views](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Tutorial_local_library_website#class-based-views) |
| 7\. Работа с Django Forms и ModelForm | Обработка данных формы | Регистрация / добавление товара | [Django Forms](https://docs.djangoproject.com/en/4.2/topics/forms/) |
| 8\. Объектно-ориентированное программирование в Django | Понимание классов, наследование | -   | [OOP in Python & Django](https://realpython.com/object-oriented-programming-python/) |

### Уровень 3\. Базы данных, миграции, авторизация, рольи, безопасность

Цель: полноценно работать с базой, реализовать разные уровни доступа.

| Микротема | Описание | Pet-проект | Полезная статья/видео |
| --- | --- | --- | --- |
| 9\. Работа с базой данных, Django ORM, миграции | Создание сложных связей | Интерактивный сайт с заказами | [Django ORM](https://docs.djangoproject.com/en/4.2/topics/db/models/) |
| 10\. Пользователи, роли, permissions | Разграничение доступа | Админка \+ пользовательский раздел | [Django Permissions](https://simpleisbetterthancomplex.com/tutorial/2018/02/19/how-to-implement-role-based-permissions-in-Django.html) |
| 11\. Пользовательские модели (Custom User) | Расширение стандартной модели | Авторизация по email | [Custom User Model](https://django.readthedocs.io/en/stable/topics/auth/customizing.html) |

### Уровень 4\. Улучшение интерфейса, анимации, динамика, API

Цель: сделать пользовательский интерфейс удобным, научиться работать с API.

| Микротема | Описание | Pet-проект | Полезная статья/видео |
| --- | --- | --- | --- |
| 12\. Pagination (пагинация) | Разделение больших списков | Каталог с пагинацией | [Django Pagination](https://realpython.com/django-pagination/) |
| 13\. AJAX, динамическое обновление данных | Без перезагрузки | Корзина, фильтры | [Using AJAX with Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Request_and_response) |
| 14\. Frontend с Bootstrap или Tailwind | Адаптивный дизайн | Все проекты с красивым интерфейсом | [Bootstrap + Django](https://simpleisbetterthancomplex.com/tutorial/2017/08/19/how-to-use-bootstrap-in-django.html) |

### Уровень 5\. Контейнеризация, контроль версий, тестирование

Цель: подготовка к развертыванию, автоматизации, тестированию.

| Микротема | Описание | Pet-проект | Полезная статья/видео |
| --- | --- | --- | --- |
| 15\. Гит и GitHub | Контроль версий | Общий репозиторий проектов | [Git tutorial](https://git-scm.com/docs/git-clone) |
| 16\. Docker и docker-compose | Контейнеризация проекта | Развертывание проекта | [Docker + Django](https://testdriven.io/blog/dockerizing-django/) |
| 17\. Написание тестов (unit, integration) | Проверка кода | Тестовые сценарии | [Django Testing](https://docs.djangoproject.com/en/4.2/topics/testing/overview/) |

### Уровень 6\. Redis, Celery — асинхронность и кеширование

Цель: реализовать фоновую работу и кеш.

| Микротема | Описание | Pet-проект | Полезная статья/видео |
| --- | --- | --- | --- |
| 18\. Redis как кеш и брокер сообщений | Быстрый доступ и очередь | Кеширование популярных данных | [Redis & Django](https://realpython.com/redis-python/) |
| 19\. Celery для фоновых задач | Асинхронные задачи | Отправка почты / импорт данных | [Celery + Django](https://docs.celeryq.dev/en/stable/django/first-steps-with-django.html) |

### Уровень 7\. API с DRF

Цель: разработать REST API для своих проектов.

| Микротема | Описание | Pet-проект | Полезная статья/видео |
| --- | --- | --- | --- |
| 20\. Основы DRF: сериализаторы, ViewSet, маршруты | Создание API | API CRUD для каталога товаров | [DRF tutorial](https://www.django-rest-framework.org/tutorial/quickstart/) |
| 21\. Аутентификация и права доступа | Безопасный API | API по ролям | [DRF authentication](https://www.django-rest-framework.org/api-guide/authentication/) |

Итоговые pet-проекты (для собеседований и портфолио)
----------------------------------------------------

* Интернет-магазин (Full-stack): авторизация, каталог, корзина, заказы, API.
* CMS-система: управление контентом, разграничение доступа.
* Бронирование/записи: расписание, платежи, уведомления.
* Тестовое задание: Имитация реальной работы — аналитика, административные панели.

Дополнительные ресурсы (по каждой теме)
---------------------------------------

* [https://testdriven.io/](https://testdriven.io/)
* [https://realpython.com/](https://realpython.com/)
* [https://django.forums.net/](https://django.forums.net/)
