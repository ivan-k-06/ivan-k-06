# Привет, я Иван 👋

**Backend и веб-разработка · студент 2-го курса ИТМО**

Учусь на 2-м курсе ИТМО по направлению «Системное и прикладное программное обеспечение». Разрабатываю приложения на Java и Spring Boot, работаю с PostgreSQL и внешними API, использую Python и развиваю навыки frontend-разработки на React и TypeScript. Рассматриваю стажировки и junior-позиции в backend и веб-разработке, открыт к работе с разными языками и технологиями.

Мой путь в backend начался с консольного клиент-серверного приложения на Java: UDP, коллекции, многопоточность и JDBC. Затем я перенёс проект на сервлеты, а после — на Spring Boot и Spring Data JPA. Сейчас развиваю проекты, практикую тестирование и автоматические проверки в GitHub Actions.

## Стек

### Бэкенд и базы данных

<p>
  <img src="./assets/badges/java.svg" alt="Java">
  <img src="./assets/badges/spring.svg" alt="Spring Boot">
  <img src="./assets/badges/hibernate.svg" alt="Hibernate">
  <img src="./assets/badges/postgresql.svg" alt="PostgreSQL">
  <img src="./assets/badges/python.svg" alt="Python">
</p>

### Фронтенд

<p>
  <img src="./assets/badges/react.svg" alt="React">
  <img src="./assets/badges/typescript.svg" alt="TypeScript">
  <img src="./assets/badges/javascript.svg" alt="JavaScript">
  <img src="./assets/badges/html5.svg" alt="HTML5">
  <img src="./assets/badges/css3.svg" alt="CSS3">
</p>

### Тестирование

<p>
  <img src="./assets/badges/junit5.svg" alt="JUnit 5">
  <img src="./assets/badges/mockito.svg" alt="Mockito">
</p>

### Инструменты

<p>
  <img src="./assets/badges/docker.svg" alt="Docker">
  <img src="./assets/badges/maven.svg" alt="Apache Maven">
  <img src="./assets/badges/git.svg" alt="Git">
  <img src="./assets/badges/github.svg" alt="GitHub">
  <img src="./assets/badges/github-actions.svg" alt="GitHub Actions">
  <img src="./assets/badges/linux.svg" alt="Linux">
</p>

## Основные проекты

### 🗺️ [Spring Route Manager](https://github.com/ivan-k-06/spring-route-manager)

Учебное веб-приложение для хранения маршрутов, которое развиваю в инструмент для планирования туристических поездок.

- Регистрация и сессионная аутентификация, добавление маршрутов и удаление собственных записей.
- Поиск городов через Nominatim API, расчёт расстояния по координатам и статистика маршрутов.
- Хранение данных через Spring Data JPA и PostgreSQL, запуск приложения и БД через Docker Compose.
- Тесты входа, регистрации, прав удаления и расчёта расстояния; проверка геокодирования с подменой HTTP-ответов.
- GitHub Actions: тестирование и сборка backend, проверка и сборка frontend.

Рабочая серверная версия использует Spring MVC и JSP. Новый интерфейс на **React и TypeScript** пока работает с демонстрационными данными; подключение к backend через JSON API — следующий этап.

**Стек:** `Java 17` · `Spring Boot` · `Spring Data JPA` · `PostgreSQL` · `JUnit 5` · `Mockito` · `Docker` · `React` · `TypeScript`

### 🎵 [Music Bro Bot](https://github.com/ivan-k-06/music-bro-bot)

Telegram-бот, который подбирает музыку по любимым жанрам пользователя через Last.fm API.

- Рекомендации по запросу и ежедневная рассылка в выбранное время с учётом смещения относительно UTC.
- Хранение пользователей и истории в PostgreSQL; проверка истории при подборе нового трека.
- Выбор жанров через inline-клавиатуру, просмотр и очистка истории.
- Интерфейс на русском, английском, немецком, испанском и французском языках.
- Unit-тесты сервиса пользователей: создание профиля, переключение жанров и пересчёт времени уведомлений.
- Запуск приложения и БД через Docker Compose.

**Стек:** `Java 17` · `Spring Boot` · `Spring Data JPA` · `PostgreSQL` · `Telegram Bot API` · `Last.fm API` · `JUnit 5` · `Mockito` · `Docker`

### 📊 [Vacancy Report](https://github.com/ivan-k-06/vacancy-report)

Консольная утилита на Python для анализа выборки вакансий и подготовки отчёта в Markdown.

- Загрузка данных из Remotive API или локального JSON-файла.
- Фильтрация вакансий, удаление дублей и статистика по компаниям, категориям и типам занятости.
- Разделение сетевых запросов, обработки данных и формирования отчёта.
- Тесты обработки данных и API-клиента с подменой ответа, запуск через Docker.

**Стек:** `Python` · `urllib` · `argparse` · `unittest` · `Docker`

## Над чем работаю дальше

- Подключение React-интерфейса Route Manager к backend через REST API.
- Серверная валидация, обработка ошибок и развитие аутентификации.
- Интеграционные тесты PostgreSQL с Testcontainers и миграции схемы БД.
- Развитие CI и практика развёртывания приложений.

## Контакты

- Telegram: [@xelangel69](https://t.me/xelangel69)
- Почта: [rivzkiank@gmail.com](mailto:rivzkiank@gmail.com)
