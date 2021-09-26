# BELHARD. Python начальный уровень. Проект

**Если вам не подходят предложенные темы - можно выполнить по своей. Сложность
должна быть не менее, чем первый уровень сложности текущих проектов.**

Результат выполнения - работающее приложение с исходным кодом в репозитории
на GitHub.

Принять во внимание:
- во всех проектах должен быть написан файл `README.md`, который должен состоять из
 следующих разделов:
  - Заголовок (Title);
  - Описание проекта (description);
  - Ключевые особенности (Key features. 3-4 пункта о том, чем хорош ваш проект);
  - Требования для запуска (Версия python, установленный Docker и т.д.);
  - Запуск проекта (Run project). Если выполнен уровень сложности 4-5, то данный
   раздел должен содержать инструкции, как запустить без Docker и c Docker;
  - Запуск миграций (Run migrations. Если выполнен уровень сложности 2);
  - Запуск тестов (Run tests. Если выполнен уровень сложности 3);
  - Запуск Front-End (Run Front-End). Краткое описание и ссылка на `README.md` файл
  в репозитории с Front-End проектом.
- во всех проектах в качестве базы данных используется `MySQL/Postgres`;
- во всех проектах (кроме проекта с backend на Django) в качестве ORM используется
 `SQLAlchemy`;
- во всех проектах (кроме проекта с backend на Django) в качестве инструмента миграций
 используется `Alembic` (Уровень сложности 2);
- во всех проектах (кроме проекта с backend на Django) в качестве инструмента
 тестирования используется `pytest`. В качестве инструмента расчета покрытия
 кода тестами использовать `pytest-cov` (Уровень сложности 3);
- в качестве менеджера пакетов можно использовать `pip` или `poetry`. Проект должен
 содержать файл `requirements.txt` или файл `pyproject.toml` в зависимости от
 выбранного пакетного менеджера.

## Уровни сложности выполнения

**Минимальный уровень сложности выполнения равен количеству участников проекта!**

:star: Выполнить проект. Продемонстрировать работу проекта;

:star::star: Написать миграции к проекту;

:star::star::star: Покрыть проект тестами (unit/functional). Обеспечить покрытие `>80%`;

:star::star::star::star: Добавить возможность запустить проект в Docker контейнере.
 Добавить и описать файлы: `Dockerfile` и `.dockerignore`;

:star::star::star::star::star: Обеспечить поднятие, остановку и работу сервисов
 (backend, database, tests) через `docker compose`. Описать файл `docker-compose.yml`;

:star::star::star::star::star::star: Сделать аутентификацию/авторизацию
 и разделение прав пользователей (пользователь и администратор);

:star::star::star::star::star::star::star: Настроить GitHub actions для автопрогона
 тестов;

:star::star::star::star::star::star::star::star: Сделать front-end сторону приложения. Это должен
 быть отдельный сервис на любом современном JavaScript фреймворке (`React.js`, `View`,
 `Angular` и т.д.). Сервис должен также подниматься в `docker compose` из п.5.

## Проектирование базы данных приложения

:link: [Схема базы данных](database/README.md)

## Проектирование REST api (все проекты, кроме telegram бота)

:link: [REST api проекта](rest_api/README.md)

## Проектирование чат-бот api (только для проекта telegram бот)

:link: [Чат-бот api](chat_bot_api/README.md)

## Проекты

1. [Telegram бот](telegram_bot/README.md);
2. [REST api на фреймворках Django и Django REST framework](django_project/README.md);
3. [REST api на библиотеке FastAPI](fastapi_project/README.md);
4. [REST api на библиотеке flask](flask_project/README.md);
5. [REST api на библиотеке aiohttp](aiohttp_project/README.md).
