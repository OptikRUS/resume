[//]: # ([💾 Скачать резюме]&#40;https://disk.yandex.ru/i/1XMum6k9oq2T7Q "Скачать резюме"&#41;)
# Кирилл М.[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=30&duration=2500&lines=%F0%9F%91%8B;+)](#кирилл-медведко)
### Senior Backend Engineer👨‍💻 | Python3🐍 FastAPI Asyncio | Инфраструктура и архитектура

## Профиль

Senior Backend Engineer с 6+ годами опыта проектирования высоконагруженных распределённых систем на Python. Добился **снижения latency в 36 раз** на таблицах с 20M записей, спроектировал event-driven платформу, обрабатывающую **19M+ событий Kafka**, и обеспечил **zero-downtime деплой** для 15–20 микросервисов. Force multiplier: менторил 4+ инженеров до повышения, внедрил культуру TDD/BDD, снизив количество багов на **70%**, и стандартизировал шаблон микросервисов, сократив время деплоя вдвое.
## Контактная информация:

<p align='left'>
   📫E-mail: <a href='mailto:kirillpydev@gmail.com'>kirillpydev@gmail.com</a>
</p>
<a href="https://t.me/kirillpydev" target="_blank">
	<img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/kirillpydev" target="_blank">
	<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

***

## 💼 Опыт работы:
<a href="https://www.compel.ru/" target="_blank">
<img height="100" src="https://weipu.ru/upload/iblock/28a/compel_logo.png" alt="Компэл">
</a>

**Senior Backend Developer** | Окт 2023 – настоящее время

**Проект**: B2B Microservices Platform (~20M SKU каталог, 15–20 микросервисов, 16–20M записей/сущность)
- Оптимизировал поисковые запросы по таблицам с 20M записей, снизив latency API **с 3500 мс до 95 мс (в 36 раз)** через EXPLAIN ANALYZE-driven денормализацию и точечное B-tree индексирование
- Ускорил массовый импорт 15–20M записей **с 8 часов до 40 минут (в 12 раз)**, оркестрируя циклы drop/rebuild индексов, bulk insert и устранение блокировок транзакций
- Провёл нагрузочное тестирование с **Locust**, выявил узкие места системы и обеспечил **снижение времени отклика в 30 раз** на критичных эндпоинтах
- Спроектировал event-driven пайплайн на **Kafka**, обрабатывающий **16–19M событий**, обеспечив near real-time синхронизацию данных с zero downtime через dual-pipeline стратегию и feature flags
- Реализовал асинхронную выгрузку данных из **MinIO**, устранив ручные процессы и снизив нагрузку на основную базу данных
- Внедрил автоматизированное тестирование с **pytest**, доведя **покрытие кода до 98%** и **сократив количество production-багов на 70%**
- Разработал **C4 L1/L2 архитектурные диаграммы**, ускорив онбординг новых инженеров и сократив совещания по архитектуре на **30%**
- Внедрил **BDD-сценарии** и обучил аналитиков их написанию, снизив возвраты задач на доработку на **35%** и повысив качество требований
- Создал **шаблон микросервиса** со стандартизированной структурой проекта, CI/CD и тулингом — сократив время деплоя нового сервиса **в 2 раза** и обеспечив единообразие кода
- **Менторил 4+ инженеров** в системной архитектуре, TDD и BDD — большинство подопечных достигли повышения или значительного роста навыков
- Оптимизировал процессы спринт-планирования и оценки, увеличив точность прогнозирования сроков на **35%** и сбалансировав нагрузку в команде
- Спроектировал паттерн разделения micro-BE / micro-FE, улучшив горизонтальное масштабирование и обеспечив переиспользование компонентов между проектами
- Интегрировал **Kafka** для асинхронного межсервисного взаимодействия, ускорив обработку заказов на **35%**
- Разработал стратегию декомпозиции для миграции с монолита на микросервисы, сформировав приоритизированный бэклог, ускоривший архитектурный переход

**Стек**: Python3 (FastAPI, SQLAlchemy, FastStream, pytest), PostgreSQL, Docker, Kubernetes, MinIO, Kafka, GitLab, Jira

***

<a href="https://fortech.dev/" target="_blank">
<img height="50" src="https://fortech.dev/static/a32912ca163863d6d8eba37312fee27c/fortech-standart-logo.svg" alt="Fortech">
</a>

**Backend Engineer → Acting Lead** | Июн 2022 – Окт 2023

**Проект**: Аналитика транзакций и веб-приложения (микросервисы)
- Спроектировал и выпустил **пайплайн аналитики транзакций** (RabbitMQ → ClickHouse), заменив PostgreSQL-based отчётность — снизил latency аналитики **с минут до секунд** и разгрузил OLTP-базу
- Внедрил **слоистую архитектуру**, декомпозировав компоненты для улучшения масштабируемости, упрощения юнит-тестирования и ускорения деплоя изменений
- Автоматизировал тестирование с **pytest**, подняв покрытие **с 0% до 92%**, **сократив время дебага на 50%** и стабилизировав релизный цикл
- Внедрил линтеры (**ruff & mypy**) в рабочий процесс, **снизив количество статических ошибок на 25%** и ускорив code review
- Настроил **CI/CD пайплайны** с тестами, линтерами и тайп-чекерами, **сократив время релизного цикла на 40%** и минимизировав production-регрессии
- **Менторил и онбордил** новых инженеров, ускоряя их выход на продуктивность; проводил кросс-командные code review для раннего выявления архитектурных недочётов
- Проводил **технические интервью и performance review**, выявляя зоны роста и повышая общую эффективность команды
- Выполнил **системный анализ** для сторонних интеграций, написал документацию и обучил разработчиков — снизив порог входа в новые интеграции
- Разработал микросервис загрузки файлов с поддержкой **S3/MinIO** и кэшированием метаданных в PostgreSQL, **сократив latency доступа к файлам на 40%** и снизив нагрузку на хранилище

**Стек**: Python3 (FastAPI, Django DRF), PostgreSQL, ClickHouse, RabbitMQ, Docker, S3 (Amazon, MinIO), GitHub, Trello

---
**Проект**: Десктоп-приложение — автоматическое распознавание автомобильных номеров
- Интегрировал алгоритм распознавания на базе OpenCV в систему видеонаблюдения, повысив скорость детекции на **40%** и точность на **30%**
- Оптимизировал декомпозицию и оценку задач, сократив время реализации фич на **20%**
- Спроектировал архитектуру приложения и ERD-диаграммы, выбрав технологии, минимизирующие технический долг
- Автоматизировал сборку Python-приложения в `.exe` через PyInstaller, оптимизировав размер и зависимости — сократив время развёртывания на **50%**

**Стек**: Python3 (OpenCV, PyQt6, SQLAlchemy, PyInstaller), SQLite, Docker, GitHub, Trello

---
**Проект**: Backend мобильного приложения для контрольных органов
- Развернул CI/CD инфраструктуру на GitLab CI и Docker, автоматизировав полный пайплайн сборки-тестирования-деплоя
- Руководил декомпозицией задач и спринт-планированием как acting team lead, обеспечив сбалансированную нагрузку и чёткие требования
- Спроектировал масштабируемую и отказоустойчивую архитектуру мобильного бэкенда (FastAPI + Django Admin + TortoiseORM)
- Разработал высокопроизводительный REST API с ролевой моделью доступа, обеспечив безопасный обмен данными
- Создал Django admin-панель с управлением слотами календаря, автоматизировав планирование и устранив конфликты записей
- Интегрировал Zoom API для автоматического создания видеоконференций и синхронизации с календарём
- Успешно защитил проект перед заказчиком, обосновав архитектурные решения и продемонстрировав надёжность системы

**Стек**: Python3 (FastAPI, Django-админка, TortoiseORM), PostgreSQL, Docker, GitHub, Telegram

***

<a href="https://artw.ru/" target="_blank">
<img height="30" src="https://artw.ru/local/templates/main_new/assets/images/logo-white.svg" alt="ARTW">
</a>

**Python Backend Developer (Acting Lead)** | Апр 2021 – Июн 2022

**Проект**: Платформа для брокеров и клиентов в сфере недвижимости
- Спроектировал и выпустил **сервис расчёта ипотеки** с нуля за 3–4 недели, изолировав доменную логику через FastAPI + Django Admin с feature toggles
- Стабилизировал интеграции со сторонними сервисами (AmoCRM, ДвижAPI), реализовав semaphore-based rate limiter и **устранив 429-ошибки** и паттерн self-DDoS
- Исправил критичный баг консистентности данных, изменив порядок API-вызов/запись-в-БД на атомарные операции и устранив осиротевшие записи
- Продвинул и внедрил тестовое покрытие **с 0% до 50%**, значительно снизив количество production-дефектов
- Взял на себя обязанности team lead: спринт-планирование, декомпозиция фич, управление релизами
- Рефакторил legacy-кодовую базу, сокращая технический долг и улучшая сопровождаемость системы
- Провёл миграцию данных между сервисами с нулевой потерей данных и минимальным downtime
- Проводил кросс-командные code review; внедрил линтеры как последнее качественное улучшение перед выходом из проекта

**Стек**: Python3, FastAPI, TortoiseORM, Django-админка, Celery, pytest, asyncio, aiohttp, PostgreSQL, Redis, GitLab, Docker, Sentry, YouTrack

***

<a href="https://careers.otr.ru/" target="_blank">
<img height="50" src="https://static.tildacdn.com/tild3439-3464-4030-b163-636236366533/Group_615.svg" alt="OTR">
</a>

**Backend Developer** | 2018 – 2021

**Проект**: Админка с интеграцией Dadata API
- Реализовал read-through кэш для Dadata API через PostgreSQL с нормализацией ключей запросов и B-tree индексированием, устранив дублирующие внешние вызовы
- Разработал планировщик автоматической очистки устаревших данных, контролируя рост базы данных
- Спроектировал кэширующий слой с осознанной простотой (PostgreSQL вместо Redis) — оптимально для нагрузки ~100–500 запросов/день

**Стек**: Python (Django), PostgreSQL, Docker, GitHub, Trello

---
**Проект**: IoT-дашборд — показатели приборов (Near Real-Time)
- Разработал Kafka-consumer сервис (single consumer, ~5 msg/sec) с in-memory кэшированием для отображения последнего состояния, приоритизировав latency над durability
- Реализовал слой персистентности с **MongoDB**, сократив время отклика и разгрузив брокер
- Разработал REST API с фильтрацией и пагинацией для кэшированных метрик устройств
- Настроил Docker-based деплой с CI/CD для автоматического развёртывания сервиса

**Стек**: Python (FastAPI, Motor), MongoDB, Kafka, Notion, GitHub

---
**Проект**: Telegram-бот для услуг фотографа с админкой (Tech Lead)
- Спроектировал систему бронирования с PostgreSQL-транзакциями и concurrency control, устранив edge-кейсы двойного бронирования
- Развернул CI/CD пайплайн на Docker и GitHub Actions для автоматической сборки и релизов
- Разработал доменную модель (users → slots → bookings), оптимизированную под workflow планирования
- Реализовал асинхронный планировщик уведомлений с batch-отправкой в рамках rate limits Telegram API
- Менторил junior-разработчика, внедрил Git-based workflow (заменив обмен zip-архивами)
- Управлял коммуникацией с заказчиком, декомпозицией задач и планированием релизов end-to-end

**Стек**: Python (aiogram, Django), PostgreSQL, Docker, Trello, GitHub

---
**Проект**: Бэкенд мобильного приложения
- Спроектировал схему БД, оптимизированную под паттерны доступа мобильного приложения
- Развернул CI/CD инфраструктуру на Docker и GitLab CI
- Разработал REST API, обеспечив быстрый и безопасный обмен данными между мобильным клиентом и сервером
- Создал и улучшил административный интерфейс, снизив нагрузку на поддержку
- Интегрировал сторонние сервисы для расширения функциональности

**Стек**: Python (Django DRF), PostgreSQL, Docker, GitHub, Trello

***

## 🛠 Ключевые навыки:

**Core и Backend**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
![SQLAlchemy](https://img.shields.io/badge/sqlalchemy-%23D71F00.svg?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=for-the-badge&logo=pytest&logoColor=2f9fe3)

**Данные и очереди сообщений**

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)
![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

**Инфраструктура и DevOps**

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-330F63?style=for-the-badge&logo=gitlab&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Sentry](https://img.shields.io/badge/sentry-%23362D59.svg?style=for-the-badge&logo=sentry&logoColor=white)

**Архитектура и качество**

![C4 Model](https://img.shields.io/badge/C4_Model-0078D4?style=for-the-badge)
![TDD](https://img.shields.io/badge/TDD-25A162?style=for-the-badge)
![BDD](https://img.shields.io/badge/BDD-7B68EE?style=for-the-badge)
![Event Driven](https://img.shields.io/badge/Event--Driven-FF6F00?style=for-the-badge)
![Microservices](https://img.shields.io/badge/Microservices-1572B6?style=for-the-badge)

**Инструменты и платформы**

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Miro](https://img.shields.io/badge/Miro-050038?style=for-the-badge&logo=Miro&logoColor=white)

**ОС и IDE**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Mac OS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)
![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)

**AI-инструменты**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/google%20gemini-8E75B2?style=for-the-badge&logo=google%20gemini&logoColor=white)

## 🤝 Soft skills:
- **Force Multiplier**: менторил 4+ инженеров до уровня повышения через структурированное обучение TDD/BDD и воркшопы по архитектуре
- Осваиваю новые технологические стеки за две недели — подтверждено выпуском production-фич на незнакомых фреймворках в первом спринте
- Внедряю **улучшения Agile-процессов** (Scrum, Kanban), измеримо сокращающие время выполнения задач и повышающие предсказуемость спринтов на **35%**
- Доношу сложные архитектурные решения до нетехнических стейкхолдеров — успешно защищал проекты перед руководством заказчика
- Быстро анализирую масштабные системы, выявляя узкие места и оптимизируя критические пути (снижение latency в 36 раз, ускорение импорта в 12 раз)

***

## 🎓 Высшее образование:

<p>
<a href="https://sfedu.ru/" target="_blank">
<img height="100" src="https://sfedu.ru/img/new_design_2020/logo.png" alt="SFU">
</a>
</p>

* Магистратура
  * <a href="https://inep.sfedu.ru/chairs/rte/" target="_blank">Электроника и наноэлектроника</a>

* Бакалавриат
  * <a href="https://inep.sfedu.ru/chairs/rte/" target="_blank">Электроника и наноэлектроника</a>

* <a href="http://mrcpk.tgn.sfedu.ru/" target="_blank">МРЦПКиПК</a>
  * Юриспруденция
* Программирование на Python

***
## <p align="center">🏆 Достижения:</p>
  * Финалист <a href="https://i.moscow/lct" target="_blank">ЛИДЕРЫ ЦИФРОВОЙ ТРАНСФОРМАЦИИ 2025</a>
    * <a href="https://github.com/OptikRUS/resume/blob/files/files/finalist_certificate_lct_2025_msk.pdf" target="_blank">Сертификат</a>
    * <a href="https://github.com/OptikRUS/resume/blob/files/files/finalist_diploma_lct_2025_msk.pdf" target="_blank">Диплом</a>
  * Финалист <a href="https://i.moscow/lct" target="_blank">ЛИДЕРЫ ЦИФРОВОЙ ТРАНСФОРМАЦИИ 2024</a>
    * <a href="https://github.com/OptikRUS/resume/blob/files/files/finalist_certificate_lct_2024_msk.pdf" target="_blank">Сертификат</a>
    * <a href="https://github.com/OptikRUS/resume/blob/files/files/finalist_diploma_lct_2024_msk.pdf" target="_blank">Диплом</a>
  * Финалист <a href="https://leaders2023.innoagency.ru/task_2" target="_blank">ЛИДЕРЫ ЦИФРОВОЙ ТРАНСФОРМАЦИИ 2023</a>
    * <a href="https://github.com/OptikRUS/resume/blob/master/files/leaders_2023_certificate.pdf" target="_blank">Сертификат</a>
    * <a href="https://github.com/OptikRUS/resume/blob/master/files/leaders2023_diplom.pdf" target="_blank">Диплом</a>
  * Финалист <a href="https://i.moscow/lct/krasnodar" target="_blank">ЛИДЕРЫ ЦИФРОВОЙ ТРАНСФОРМАЦИИ 2023 Краснодарский край</a>
    * <a href="https://github.com/OptikRUS/resume/blob/master/files/leaders_2023_krasnodar_certificate.pdf" target="_blank">Сертификат</a>
    * <a href="https://github.com/OptikRUS/resume/blob/master/files/leaders_2023_krasnodar_diplom.pdf" target="_blank">Диплом</a>
  * Хакатон <a href="https://xn--80aaaairqt2ajzt9a.xn--p1ai/" target="_blank">ЕВРАЗА 2.0</a>
    * <a href="https://github.com/OptikRUS/resume/blob/master/files/evraz.pdf" target="_blank">Сертификат</a>
  * Онлайн-хакатон <a href="https://codenrock.com/contests/scbteamchallenge-codenrock/#/" target="_blank">Sovcombank Team Challenge 2022</a>
    * <a href="https://github.com/OptikRUS/resume/blob/master/files/Sovcombank.pdf" target="_blank">Сертификат</a>


***
## <p align="center">💻 Обо мне:</p>
<p>
Senior Backend Engineer, специализирующийся на высоконагруженных распределённых системах, event-driven архитектурах и developer experience.
Обеспечил измеримый бизнес-импакт в B2B маркетплейсах, fintech-аналитике, платформах недвижимости и государственных системах.
Доказанный трек-рекорд трансформации инженерной культуры через менторство, test-driven разработку и архитектурные стандарты —
последовательно повышаю производительность команд. 4x финалист хакатона «Лидеры цифровой трансформации».
</p>

***
<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%23000202&size=25&multiline=true&width=640&lines=%D0%98%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F+%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D1%8F%D0%BB%D0%B0%D1%81%D1%8C+%D0%B2+%D0%BC%D0%B0%D1%80%D1%82%D0%B5+2026+%D0%B3%D0%BE%D0%B4%D0%B0)](#кирилл-медведко)

</div>

***

[//]: # (<div align="center">)

[//]: # (  <a href="https://github.com/OptikRUS/resume/blob/files/files/cv_02_02_2024.pdf" download>)

[//]: # (    💾 Скачать резюме)

[//]: # (  </a>)

[//]: # (</div>)