# PROJECT-5.
### Задача регрессии
В ходе проекта будем строить модель, которая будет предсказывать общую продолжительность поездки на такси в Нью-Йорке.

---
Известно, что стоимость такси в США рассчитывается на основе фиксированной ставки и тарифной стоимости, величина которой зависит от времени и расстояния. Тарифы варьируются в зависимости от города.

В свою очередь, время поездки зависит от множества факторов, таких как направление поездки, время суток, погодные условия и так далее.

Таким образом, если мы разработаем алгоритм, способный определять длительность поездки, мы сможем прогнозировать её стоимость самым тривиальным образом, например, просто умножая стоимость на заданный тариф.

Сервисы такси хранят огромные объёмы информации о поездках, включая такие данные, как конечная и начальная точки маршрута, дата поездки и её продолжительность. Эти данные можно использовать для того, чтобы прогнозировать длительность поездки в автоматическом режиме с привлечением искусственного интеллекта.

---

Задача, которую мы будем решать, была представлена в качестве [Data Science-соревнования платформе Kaggle](https://www.kaggle.com/competitions/nyc-taxi-trip-duration/overview 'New York City Taxi Trip Duration') с призовым фондом в 30 000 $ в 2017 году.

---

Бизнес-задача: определить характеристики и с их помощью спрогнозировать длительность поездки на такси.

Техническая задача: построить модель машинного обучения, которая на основе предложенных характеристик клиента будет предсказывать числовой признак — время поездки такси, то есть решить задачу регрессии.

**ОСНОВНЫЕ ЦЕЛИ:**

1. Сформировать набор данных на основе нескольких источников информации.
2. Спроектировать новые признаки с помощью Feature Engineering и выявить наиболее значимые при построении модели.
3. Исследовать предоставленные данные и выявить закономерности.
4. Построить несколько моделей и выбрать из них ту, которая показывает наилучший результат по заданной метрике.
5. Спроектировать процесс предсказания длительности поездки для новых данных.

---
Датасеты, используемые в проекте:
* [Тренировочный датасет с информацикй о поездках на такси в Нью-Йорке за 2016 год](https://www.kaggle.com/competitions/nyc-taxi-trip-duration/overview 'train.csv')
* [файл с праздничными датами](https://lms-cdn.skillfactory.ru/assets/courseware/v1/33bd8d5f6f2ba8d00e2ce66ed0a9f510/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/holiday_data.csv 'holiday_data.csv')
* [Файл с данными из OSRM для поездок из тренировочной таблицы](https://drive.google.com/file/d/1ecWjor7Tn3HP7LEAm5a0B_wrIfdcVGwR/view?usp=sharing 'osrm_data_train.csv')
* [Датасет содержащий информацию о погодных условиях в Нью-Йорке в 2016 году](https://lms-cdn.skillfactory.ru/assets/courseware/v1/0f6abf84673975634c33b0689851e8cc/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/weather_data.zip 'weather_data.csv')


Ссылка на ноутбук:
* [Project-5.ipynb](https://github.com/Blooodniy/PROJECT-5/blob/master/Project-5.ipynb)
