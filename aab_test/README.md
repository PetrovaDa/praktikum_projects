# A/A/B- тест в приложении
A/B-тест, визуализация, статистический тест

## Описание проекта 

#### Объект исследования - данные мобильного приложения по продаже продуктов питания

#### Цель - определить какой шрифт лучше.

#### Задачи: 

    - Изучить воронку продаж, проанализировать поведение пользователей
    - Исследовать результаты A/A/B-эксперимента

    Группы экспеимента: 2 контрольные со старыми шрифтами и экспериментальная — с новыми шрифтами

## Описание данных
Каждая запись в логе — это действие пользователя, или событие.

    EventName — название события;
    DeviceIDHash — уникальный идентификатор пользователя;
    EventTimestamp — время события;
    ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

В данном проекте мной были изучены принципы событийной аналитики. Я построила
воронку продаж, исследовала путь пользователей до покупки. Проанализировала
результаты A/B-теста введения новых шрифтов. Сравнила 2 контрольных группы между
собой, убедилась в правильном разделении трафика, а затем сравнила с тестовой группой

### Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.

