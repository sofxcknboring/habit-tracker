```
pip install -r requirements.txt
```

```
cp .env.example .env
```

```
python manage.py migrate
```

```
python manage.py test
```

```
python manage.py csu
```

```
celery -A config beat -l info -S django
```

```
celery -A config worker -l INFO
```

Док: /redoc
