# Data-Analytics-Projects

**Название проекта:** Маркетинговый анализ приложения Procrastinate Pro+

**Описание инсайтов:** Развлекательное приложение Procrastinate Pro+ последние несколько месяцев компания терпит убытки, несмотря на огромные вложения в рекламу.

**Цель исследования:** выявить причины убытков, разработать рекомендации для сокращения убытков и получения прибыли.

**Задачи исследования:**
1. Изучить откуда приходят пользователи и какими устройствами они пользуются,
2. Определить сколько стоит привлечение пользователей из различных рекламных каналов;
3. Оценить сколько денег приносит каждый клиент,
4. Выяснить когда расходы на привлечение клиента окупаются,
5. Определить какие факторы мешают привлечению клиентов.

**Описание данных:**
Предоставлены данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года:
- лог сервера с данными об их посещениях,
- выгрузка их покупок за этот период,
- рекламные расходы.

**Структура visits_info_short:**

- User Id — уникальный идентификатор пользователя,
- Region — страна пользователя,
- Device — тип устройства пользователя,
- Channel — идентификатор источника перехода,
- Session Start — дата и время начала сессии,
- Session End — дата и время окончания сессии.

**Структура orders_info_short:**

- User Id — уникальный идентификатор пользователя,
- Event Dt — дата и время покупки,
- Revenue — сумма заказа.

**Структура costs_info_short:**

- dt — дата проведения рекламной кампании,
- Channel — идентификатор рекламного источника,
- costs — расходы на эту кампанию.