## Описание проекта
Этот проект содержит анализ данных о кэшбэке клиентов банка Tinkoff за последние 3 месяца. Данные включают информацию о суммах кэшбэка по различным категориям покупок, а также активность клиентов (количество коммуникаций, активаций, просмотров).

## Структура данных
Файл tinkoff_cashback.csv содержит следующие колонки:

# Основные метрики клиента
- client_id - уникальный идентификатор клиента
- cb_merch_last_3_month - кэшбэк от мерчантов за последние 3 месяца
- cb_bank_last_3_month - кэшбэк от банка за последние 3 месяца
- cb_merch_before - кэшбэк от мерчантов ранее
- cb_bank_before - кэшбэк от банка ранее
- cnt_communication - количество коммуникаций с клиентом
- cnt_activation - количество активаций
- cnt_view - количество просмотров

# Категории покупок (за последние 3 месяца)
Air, Beauty shop, Book store, Children, Cinema, Clothes, Electronics, Fastfood, Fuel, House, Jewelry, Other, Pet shop, Pharmacies, Supermarkets, Taxi, Transport

# Категории покупок (ранее)
Те же категории с суффиксом _before (например, Air_before, Beauty shop_before и т.д.)
