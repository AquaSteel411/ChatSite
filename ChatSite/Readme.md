# <a id='up'>Chat Site</a>

### Оглавление:
- [Полезные адреса для ознакомления с работой](#1)
- [Аккаунты](#2)
- [Инструкция по запуску](#3)

### <a id='1'>Полезные адреса для ознакомления с работой</a>:
- http://127.0.0.1:8000/accounts/signup/ - регистрация
- http://127.0.0.1:8000/accounts/login/ - логин
- http://127.0.0.1:8000/chat/list_users - список пользователей
- http://127.0.0.1:8000/chat/list_room/ - список чатов (в которых состоит пользователь)
---

### <a id='2'>Аккаунты</a>:
- Admin
```
login: admin
password: admin
```
- popov_d1994@mail.ru
```
login: popov_d1994@mail.ru
password: Seraphim1994
```

- popovd1994@gmail.com
```
login: evropolkuz@gmail.com
password: Seraphim1994
```
---
### <a id='3'>Инструкция по запуску</a>:
- Установка зависимостей (все библиотеки есть в файле requirements.txt):
Данные библиотеки можно установить через pip install -r requirements.txt (предварительно удалив из файла ```channels==3.0.5 ```):
```
django
django-allauth
django-filter
djangorestframework
markdown
python-dotenv
Pillow
channels-redis==2.4.2
```
Библиотеку ```channels==3.0.5 ``` устанавливать отдельно (при установке через pip install -r requirements.txt конфликтует с ```channels-redis==2.4.2```);
- Запустить в отдельном терминале ```redis-server``` (в моем случае это Windows PowerShell);
- Запустить приложение находясь в дериктории с manage.py ```python manage.py runserver```;
- Авторизоваться через один из предложенных аккаунтов, либо создав свой;
- Все работает.


---
Было реализовано по ТЗ все кроме редактирования личной информации, просто не хватило времени.
Так же не хватило времени на красивое оформление и коментарии. 
Все негодование поводу текущего модуля и задания выскажу в обратной связи. Так обучать нельзя!

[Вверх](#up)
