# Анализ бизнес-показателей (LTV, ROI, CTR, Converion rate)

## Описание проекта
Есть данные о пользователях развлекательного приложения, привлечённых с 1 мая по 27 октября 2019 года: лог сервера с данными об их посещениях, выгрузка их покупок за этот период, рекламные расходы. Предстоит изучить: откуда приходят пользователи и какими устройствами они пользуются, сколько стоит привлечение пользователей из различных рекламных каналов; сколько денег приносит каждый клиент, когда расходы на привлечение клиента окупаются, какие факторы мешают привлечению клиентов.

## Цель исследования
На основании данных о заходах пользователей в приложение, истории их покупок и рекламных расходах выяснить причины, по которым компания терпит убытки и предложить пути оптимизации маркетинговой стратегии.

## Описание данных
Структура visits_info_short

User Id — уникальный идентификатор пользователя,
Region — страна пользователя,
Device — тип устройства пользователя,
Channel — идентификатор источника перехода,
Session Start — дата и время начала сессии,
Session End — дата и время окончания сессии.

Структура orders_info_short

User Id — уникальный идентификатор пользователя,
Event Dt — дата и время покупки,
Revenue — сумма заказа.

Структура costs_info_short

dt — дата проведения рекламной кампании,
Channel — идентификатор рекламного источника,
costs — расходы на эту кампанию.

## Используемые библиотеки
pandas
numpy
matplotlib
seaborn
