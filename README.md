# jsTube API

Django API for the current JsTube media service.

This repository intentionally contains source code only. Do not commit production `.env` files, tokens, database dumps, media files, or private keys.

## Local

```sh
python -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
python manage.py test media_api
python manage.py runserver 0.0.0.0:8085
```
