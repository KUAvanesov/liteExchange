# liteExchange синхронизация с 1с

#liteExchange - это фреймворк, содержащий большое количество готовых решений для выполнения задач синхронизации и интеграции на платформе 1с.

Ключевая особенность фреймворка - практически мгновенный обмен, недостижимая скорость для привычных инструментов.

## Решаемые задачи:
1. Организация Backend на платформе 1с.
2. Отправка данных на сторонний сервер для обработки.
3. Синхронизация баз 1с с возможностью описать код конвертации объектов
3.1. Одинаковые базы 1с
3.2. Похожие базы 1с
3.3. Разные базы 1с
3.4. Риб (ускорение до онлайн)

## Компоненты фреймворка:
1. Легкий HTTP коннектор.
2. Продвинутый механизм конвертации в JSON и обратно:
2.1. для простых типов данных
2.2. с контролем типов и преобразованием типов в простые
2.3. для наборов записей регистров

3. Продвинутый механизм конвертации объектов 1с в простые типы и обратно
4. Анализатор данных, извлекающий ссылки из объекта в массив, для последующей передачи в доугую базу.

## Особенности и тебования
Поставляется в виде расширения

Минимальные требования - платформа 8.3.9 и режим совместимости 8.3.9 для устаревших конфигураций
Подробнее о том, как в УПП 1.3. получить режим совместимости 8.3.9 и чем это грозит тут: <..>

## Концепция решения

## Существующие альтернативы
* DATAREON MQ - содержит встроенный коннектор с 1с, реализует обмен в формате XML. Решает часть задач, как liteExchange, но ео надо уметь готовить.
* Rabbit MQ - для высоконагруженных систем. Требоует коннектора и внешней компоненты для работы с 1с
* Универсальный обмен данными XML - невероятно медленный
* Правила обмена КД2 - еще более медленные
* Правила обмена КД3 и омбен через универсальный формат - быстрее КД2, но надо уметь из готовить. Обмен опять через XML.

## Примеры решаемых задач.
1. Обмен с AMO CRM, Битрикс 24, Интернет магазинами в реальном времени.
2. Передача данных для обработки на удаленные сервера и системы.
3. Синхронизация с другой 1с.
4. Параллельная работа в нескольких копиях 1с (почти РИБ)
5. 

Больше кейсов в канале телеграмм:
https://t.me/liteExchange_channel

## 3 причины выбрать
