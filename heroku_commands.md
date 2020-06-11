## (all commands are used in the root directory of django(where manage.py is))
## - heroku login --> to login to heroku
## - pip install gunicorn --> to install gunicorn
## - pip install django-heroku --> to install django-heroku
## (add import django_heroku to settings.py file)
## (add django_heroku.settings(locals() to end of settings.py file))
## - pip freeze --> requirements.txt
## (create Procfile and write web: gunicorn youappname.wsgi to it)
## (add .gitignore python from github)
## (push the repo to gihub)
## - heroku create yourappname --> create heroku app and domain as well
## (add your heroku generated domain to allowed hosts in settings.py file)
## - heroku addons --> to check if you have an activated database
## - heroku addons:create heroku-postgresql:hobby-dev --> to create a database if it isn't created
## - git push heroku master --> pushing the repo to heroku
## - heroku logs --tail --> get logs of failed heroku push
## - heroku run python manage.py migrate -> create tables in database
## - heroku open --> to open the created heroku app
## - heroku run bash --> to open heroku bash interface(helpful in creating django superuser)
## - python manage.py createsuperuser --> create django superuser to the app(be sure to enter this command in heroku bash interface)


