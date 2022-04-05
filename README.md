# film_distributors_research
Исследование трендов проката на рынке кино в России и СНГ (in progress)

Исходный набор данных получен путем скраппинга данных ресурса kinopoisk.ru. Выборка содержит данные кинопоказов на территории России и СНГ с 04.01.2007 по 27.02.2022.

Данные агрегированы в три таблицы:
  weekends/уик-энды
  weekly_box_offices/сборы уик-эндов
  movies/фильмы.

Проект скраппера: 
  https://github.com/rand0mn/boxoffice_scraper
  
Пример источников:
  Уик-энды: https://www.kinopoisk.ru/index.php?level=42&type=rus&year=2007
  Сборы уик-энда: https://www.kinopoisk.ru/box/weekend/2022-02-18/type/rus/cur/RUB/view/all/
  Информация о фильме: https://www.kinopoisk.ru/film/468373/

TODO:
- Сделать анализ каждого дистрибьютора из топ-10
- Визуализация в tableau
- Сделать статистический тест для определения ключевых признаков, влияющих на сборы и рейтинг

