# **Проект магазин**



## **Данный проект состоит из четырёх приложений.**
1. **api**. Возвращает информацию по основным позициям магазина - список товаров, каталог, корзина, и т.п.
2. **customer_profile**. Возвращает информацию о профилях покупателей, позволяет редактировать профили.
3. **orders**. Возвращает информацию о заказах, сделанных покупателями.
4. **products**. Возвращает информацию о продуктах.


## Порядок запуска
Для запуска проекта необходимо 
1. Выполнить инициализацию проекта - `python manage.py migrate`
2. Восстановить данные из фикстуры - `python manage.py loaddata db.json`
3. Установить фронтенд - `pip install dist/diploma-frontend-0.6.tar`
4. Запустить проект - `python manage.py runserver`