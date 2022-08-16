## API YaTube 
YaTube is a service for creating posts. Users can leave comments, as well as subscribe to the authors they like.

This project is a REST API for [YaTube project](https://github.com/IuriyLeb/yatube_final)

# Installation

Сlone repository in your local mashine

```bash
git clone https://github.com/IuriyLeb/yatube_final.git
```

Create and activate virualenv

```bash
python -m venv venv
```

```bash
source venv/Scripts/activate
```

Then you need to install requirements

```bash
pip install -r requirements.txt
```

Create and make migrations

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

Run project on your local machine

```bash
python manage.py runserver
```
# Usage

API's domens are in `/api/v1/`

Full usage in redoc documentation

to run redoc use `/redoc`
