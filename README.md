Курсовая работа по  Курсу DRF

1.Скопируйте проект с Github

2,После закачки проекта введите команду в консоли в папке проекта: (python -m venv venv; затем venv/scripts/activate)

3.Перенисите зависимости: pip install -r requirements.txt

4.Создайте новый БД

5.Активируйте миграции (python manage.py migrate)

6.Внесите свои настройки, в файл .env.example, переименуйте в .env

7.Зарегистрируйте суперпользователя (python manage.py csu)

8.Активируйте Redis (redis-server)

9.Запускайте проект (python manage.py runserver)

10.Запустите во второй вкладке celery beat: celery -A config beat -l info -S django

11.Запустите в терминале celery worker: celery -A config worker -l INFO 

Зайдите в телеграм бот, и нажмите /start

