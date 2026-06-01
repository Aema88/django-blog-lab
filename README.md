# Django Blog Lab

Навчальний веб-додаток у вигляді простого блогу, розроблений для лабораторної роботи.

## Технології

- Python
- Django
- SQLite
- HTML/CSS
- Git/GitHub
- Visual Studio Code

## Функціонал

- Реєстрація користувачів
- Авторизація та вихід із системи
- Скидання пароля
- Профіль користувача
- Створення записів
- Перегляд записів
- Коментарі до записів
- Адмін-панель Django

## Структура проєкту

```text
blog_lab/
├── blog/                  # Django-додаток блогу
│   ├── models.py          # Моделі Post, Comment, Profile
│   ├── views.py           # Представлення
│   ├── forms.py           # Форми
│   ├── urls.py            # URL-адреси додатку
│   └── admin.py           # Налаштування адмін-панелі
│
├── config/                # Налаштування Django-проєкту
│   ├── settings.py
│   └── urls.py
│
├── templates/             # HTML-шаблони
│   ├── base.html
│   ├── blog/
│   └── registration/
│
├── manage.py
├── requirements.txt
├── README.md
└── .gitignore