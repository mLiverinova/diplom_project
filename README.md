# Решение задачи машинного обучения модели по предсказанию цены на недвижимость

# Содержание файла кода (формат .ipynb)

1. Описание проекта
2. Описание данных
3. Подключение бибиотек
4. Функции, используемые в коде
5. Загрузка, очистка и разведывательный анализ данных
   1. Загрузка данных
   2. Обработка пропусков
   3. Создание новых признаков
   4. Обработка выбросов данных
6. Исследование данных
7. Создание модели
   1. Модель линейной регрссии
   2. Модель полиномиальной регресии
   3. Модель случайного леса и оптимизация гиперпараметров
8. Заключение

## Описание проекта

Разработка модели для агентства недвижимости с целью увеличения скорости и качества совершения сделок путем прогнозирования стоимости недвижимости методами машинного обученияю

Проект состоит из следующих этапов:
1. Загрузка, разведывательный анализ и обработка данных.
2. Выделение наиболее значимых факторов, влияющих на стоимость недвижимости.
3. Построение модели для прогнозирования стоимости недвижимости.

## Описание исходных данных данных

* 'status' — статус
* 'private pool' и 'PrivatePool' — наличие собственного бассейна;
* 'propertyType' — тип объекта недвижимости;
* 'street' — адрес объекта;
* 'baths' — количество ванных комнат;
* 'homeFacts' — сведения о строительстве объекта (содержит несколько
типов сведений, влияющих на оценку объекта);
* 'fireplace' — наличие камина;
* 'city' — город;
* 'schools' — сведения о школах в районе;
* 'sqft' — площадь в футах;
* 'zipcode' — почтовый индекс;
* 'beds' — количество спален;
* 'state' — штат;
* 'stories' — количество этажей;
* 'mls-id' и 'MlsId' — идентификатор MLS (Multiple Listing Service, система
мультилистинга);
* 'target' — цена объекта недвижимости (целевой признак, который
необходимо спрогнозировать).
