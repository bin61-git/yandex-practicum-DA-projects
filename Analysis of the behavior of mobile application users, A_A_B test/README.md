## Данные
Каждая запись в логе — это действие пользователя, или событие, при этом:  
**EventName** — название события;  
**DeviceIDHash** — уникальный идентификатор пользователя;  
**EventTimestamp** — время события;  
**ExpId** — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

## Задача
На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования.

## Описание проекта
Данный проект посвящен событийной аналитике. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/А/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой. Сделал вывод о необходимости признать результат теста отрицательным, изменение шрифта на сайте не влечет статистически значимых различий как в пошаговой, так и в итоговой конверсии пользователей в покупатели.

## Используемые  
### библиотеки 
Python, Pandas, Matplotlib, Seaborn, Plotly   

### навыки и инструменты  
A/B-тестирование, событийная аналитика, продуктовые метрики, проверка статистических гипотез, визуализация данных.