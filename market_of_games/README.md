# Развитие рекламной компании интернет-магазина по компьютерным играм
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/valentinatihova/DA_projects/blob/master/market_of_games/market_of_games_v01.ipynb)
## Данные
Доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). 

*Источник данных*: https://www.kaggle.com/code/iliassekkaf/video-game-sales-eda/data?select=Video_Games_Sales_as_at_22_Dec_2016.csv

Стуруктура данных следущая:
  - Name — название игры
  - Platform — платформа
  - Year_of_Release — год выпуска
  - Genre — жанр игры
  - NA_sales — продажи в Северной Америке (миллионы долларов)
  - EU_sales — продажи в Европе (миллионы долларов)
  - JP_sales — продажи в Японии (миллионы долларов)
  - Other_sales — продажи в других странах (миллионы долларов)
  - Critic_Score — оценка критиков (максимум 100)
  - User_Score — оценка пользователей (максимум 10)
  - Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

## Задача
Необхоимо выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## Используемые библиотеки
Stats, Numpy, Pandas, Seaborn, Datetime, Matplotlib.pyplot, Math, Pandas_profiling
