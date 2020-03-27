Описание моего приложения Django Blog:
это блог где можно добавлять статьи (статьи может размещать только администратор), 
редактировать статьи, добавлять  комментарии (комментарии может добавить любой желающий,
администратор может принять или отклонить комментарий).

Настройка виртуального окружения и установка необходимых библиотек:
pip install -r requirements.txt .

Чтобы развернуть приложение на PythonAnywhere необходимо:
1. Создание учётной записи на PythonAnywhere;
2. Создание API токена для PythonAnywhere (Account -> API token -> Create new API token); 
3. Необходимо вызвать Bash-консоль;
4. В Bash-консоли необходимо запустить специальный помощник: pip3.6 install --user pythonanywhere ;
5. Запустить помощник: pa_autoconfigure_django.py https://github.com/<your-github-username>/my-first-blog.git , где 
<your-github-username> это ник на GitHub;
6. На PythonAnywhere необходимо создать аккаунт администратора: 
(<your-github-username>.pythonanywhere.com) $ python manage.py createsuperuser ;
7. На странице Web доступны ссылка на сайт.

Советы по отладке: http://help.pythonanywhere.com/pages/DebuggingImportError .

