<p align="center">
  <img src="assets/header.svg" alt="Владислав Субарев — Python backend-разработчик" width="100%" />
</p>

Пишу backend на Python: REST API, интеграции с внешними сервисами и работу с базами данных. В командных проектах занимаюсь серверной логикой, тестами и разбором замечаний к pull request.

Учусь в **ГУАП** на направлении "Информатика и вычислительная техника", а также на программе **«Профессия Python-разработчик» в Skillbox**. Ищу возможности развиваться в Python backend-разработке и работать над полезными продуктами в команде.

## С чем работаю

| Направление | Технологии |
| :--- | :--- |
| API и интеграции | Python, FastAPI, Pydantic, HTTPX, requests |
| Данные | PostgreSQL, SQLite, SQLAlchemy asyncio, Alembic |
| Проверка кода | pytest, pytest-asyncio, Ruff |
| Среда разработки | Git, Docker Compose, Poetry, Linux / macOS |

## Проекты

### [Авача: бэкенд для гонки на Камчатке](https://github.com/St3pAn1ndzy/kamchatka_race_back/tree/develop)

Командный проект хакатона Skillbox. Работал над публичным API и админкой: от моделей и миграций базы данных до сервисов, роутов и тестов. По ссылке выше открывается рабочая ветка `develop`.

**Мой вклад:**

- [Справочники гонки](https://github.com/St3pAn1ndzy/kamchatka_race_back/pull/34): модели сезонов и дисциплин в SQLAlchemy, связи этапов и участников, миграция Alembic, схемы Pydantic, репозитории, сервис и роуты FastAPI.
- [Публичное API](https://github.com/St3pAn1ndzy/kamchatka_race_back/pull/19): схемы ответов, запросы к базе и роуты для новостей, расписания и FAQ.
- Административные операции: [назначение трекеров участникам](https://github.com/St3pAn1ndzy/kamchatka_race_back/pull/40), [создание и корректировка судейских отметок](https://github.com/St3pAn1ndzy/kamchatka_race_back/pull/41), аудит изменений и обработка конфликтов при записи.
- Маршруты: [импорт KML/GPX с предпросмотром](https://github.com/St3pAn1ndzy/kamchatka_race_back/pull/63), [замена трассы](https://github.com/St3pAn1ndzy/kamchatka_race_back/pull/64) с сохранением GPS-истории и пересчётом прогресса.
- Подготовка к показу: [демосценарий трекера и SOS](https://github.com/St3pAn1ndzy/kamchatka_race_back/pull/66), [инструкции запуска и руководство по админке](https://github.com/St3pAn1ndzy/kamchatka_race_back/pull/68). Также работал над тестами API и сервисов на pytest.

`FastAPI` · `PostgreSQL` · `SQLAlchemy` · `Alembic` · `Redis` · `pytest`

### МИРОНИКО · сайт логистической компании

Работал над сайтом с серверной и статической версиями на общих шаблонах. Тексты и контакты хранятся в JSON; отдельные Python-скрипты проверяют обязательные поля и собирают каталог для публикации.

`Python` · `FastAPI` · `Jinja2` · `HTML / CSS`

### [MovieBot · поиск фильмов в Telegram](https://github.com/vladsu-dev/moviebot)

Учебный проект с внешним API: поиск по названию и жанру, подборки фильмов, постраничная навигация и сохранение истории запросов в SQLite.

`pyTelegramBotAPI` · `requests` · `Peewee` · `SQLite`

## Что мне интересно в разработке

Понятные границы модулей, предсказуемые ошибки API и тесты, которые проверяют поведение приложения. Сейчас углубляюсь в асинхронный Python, транзакции и многозадачность.

<details>
<summary>За пределами Python</summary>

Экспериментирую с macOS-приложениями на Swift и SwiftUI. Один из проектов — прототип MacWinGameLauncher для управления профилями запуска Windows-приложений через Wine. Это исследовательский проект, совместимость с произвольными играми не заявляю.

</details>

---

**Санкт-Петербург · Python backend · открыт к junior-позициям и стажировкам**
