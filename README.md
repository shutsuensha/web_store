# Order Tracking Web Application
## Demo app - [Dolce Vita Wear](https://shutsuensha.pythonanywhere.com/)

![Обзор сайта](./overview.gif)
Вы можете посмотреть видеообзор сайта в репозитории [здесь](./overview.mp4).

## Описание
Веб-приложение для отслеживания заказов, разработанное на Django. Оно позволяет пользователям выбирать и фильтровать категории/товары, добавлять их в корзину, редактировать корзину, оформлять или удалять заказы. Также есть возможность оставлять и редактировать комментарии к товарам, а администратор может управлять категориями, товарами и заказами.

Приложение уведомляет пользователей о статусе заказа по электронной опчте, а администрацию — через Telegram-бота.

## Основные функции
- Фильтрация товаров по категориям
- Добавление товаров в корзину и редактирование содержимого корзины
- Оформление и удаление заказов
- Оповещения по электронной почте и через Telegram-бота
- Возможность оставлять комментарии к товарам
- Интеграция с Google One Tap для упрощенной аутентификации
- Поддержка авторизации через Python Social Auth
- Панель администратора для управления товарами, категориями и заказами
- Отзывчивый дизайн с возможностью выбора светлой или темной темы

## Технологии
Проект построен с использованием следующих технологий:
- **Python**: язык программирования
- **Django**: веб-фреймворк
- **Django ORM**: для работы с базой данных
- **Django Mail**: для отправки уведомлений по email
- **Telegram Bot API**: для уведомлений через телеграм-бота
- **Google One Tap**: для аутентификации пользователей
- **Python Social Auth**: для интеграции с социальными сетями

## Установка и запуск проекта

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/yourusername/order-tracking-webapp.git
    ```
   
2. Установите необходимые зависимости:
    ```bash
    pip install -r requirements.txt
    ```

3. Выполните миграции базы данных:
    ```bash
    python manage.py migrate
    ```

4. Запустите сервер разработки:
    ```bash
    python manage.py runserver
    ```

## Настройки

1. Для работы почтовых уведомлений настройте почтовый сервис в `settings.py`.
2. Для интеграции с Telegram Bot API укажите токен бота в переменных окружения.

## Контакты
Автор проекта: **Даниил Куприянчик**  
Email: dankupr21@gmail.com
Telegram: [@evalshine](https://t.me/evalshine)

