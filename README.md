Данный проект представляет собой площадку для размещения и обмена информацией владельцев котов и кошек о своих животных.

**Стек:**
- Python;
- Django;
- Nginx;
- Gunicorn;
- React.

**Запуск проекта.**

Клонировать репозиторий:
```
git clone git@github.com:d1g-1t/infra_sprint1.git
```
Перейти в папку проекта, активировать виртуальное окружение, установить зависимости, выполнить миграции:
```
cd infra_sprint1
python3 -m venv venv
source venv/scripts/activate
python3 -m pip install --upgrade pip
pip install -r requirements.txt
python manage.py migrate
```
Запуск проекта:
```
python manage.py runserver
```

Проект будет доступен по адресу: http://localhost:8000/

# Автор:

**Павел Охрим**
