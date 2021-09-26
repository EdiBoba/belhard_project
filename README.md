# BELHARD. Python начальный уровень. Проект

**Если вам не подходят предложенные темы - можно выполнить по своей. Сложность
должна быть не менее, чем первый уровень сложности текущих проектов.**

**Минимальный уровень сложности выполнения равен количеству участников проекта**

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
 используется `Alembic` (Уровень сложности 2)
- во всех проектах (кроме проекта с backend на Django) в качестве инструмента
 тестирования используется `pytest`. В качестве инструмента расчета покрытия
 кода тестами использовать `pytest-cov` (Уровень сложности 3).

## Уровни сложности выполнения

1. :star: Выполнить проект. Продемонстрировать работу проекта;
2. :star::star: Написать миграции к проекту;
3. :star::star::star: Покрыть проект тестами (unit/functional). Обеспечить покрытие >80%;
4. :star::star::star::star: Добавить возможность запустить проект в Docker контейнере.
 Добавить и описать файлы: `Dockerfile` и `.dockerignore`;
5. :star::star::star::star::star: Обеспечить поднятие, остановку и работу сервисов
 (backend, database, tests) через `docker compose`. Описать файл `docker-compose.yml`;
6. :star::star::star::star::star::star: Сделать front-end сторону приложения. Это должен
 быть отдельный сервис на любом современном JavaScript фреймворке (`React.js`, `View`,
 `Angular` и т.д.). Сервис должен также подниматься в `docker compose` из п.5.

## Проектирование базы данных приложения

## Проектирование REST api (все проекты, кроме telegram бота)

## Проектирование чат-бот api (только для проекта telegram бот)

## Проекты

1. Telegram бот;
2. REST api на фреймворках Django и Django REST framework;
3. REST api на фреймворке FastAPI;
4. REST api на фреймворке flask;
5. REST api на фреймворке aiohttp.
