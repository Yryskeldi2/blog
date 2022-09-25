# Django project BLOG
## команды

> django-admin startproject config. - создает проект если поставить, то проект создается в этой же папке если не поставить то создаться папка config и в ней создаться проект 
> python manage.py startapp app_name - создаться приложение 
> python manage.py makemigrations - проверяет все models, если есть изменения, то создает новый файл в migrations c изменениями 
> python manage.py migrate - считывает все файлы миграций и выполняет в бд (изменяет строение таблиц)
> python manage.py runserver - запускает наш проект на 127.0.0.1:8000
> python manage.py runserver 5000 - запускает наш проект на 127.0.0.1:5000

## setting.py
* BASE_DIR - корневая папка нашего проекта 
* SECRET_KEY - секретный ключ 
* DEBUG - если True, все ошибки будут отображаться по этому на production мы ставим его на False 
* ALLOWED_HOSTS - хосты, на которых разрешен запуск нашего проекта (если список пустой - можно запустить на localhost (127.0.0.1))
* INSTALLED_APPS - все приложения которые будут использовать наш проект 
* MIDDLEWARE - все middleware (функции, которые обрабатывают запрос), котороые будет использовать наш проект 
* ROOT_URLCORN - главный файл urls 
* DATABASES - настройки баз данных которые будет использовать наш проект
 