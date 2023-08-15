# Определение стоимости автомобиля

<p align="center">
  <img width="300" src="img/9377233.jpg">
</p>  

## Задача проекта
Разработка системы рекомендации стоимости автомобиля на основе его описания.  

## Описание проекта  
Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.  

## Навыки и инструменты  
![Static Badge](https://img.shields.io/badge/pandas-48D1CC)
![Static Badge](https://img.shields.io/badge/numpy-BC8F8F)
![Static Badge](https://img.shields.io/badge/seaborn-FFC0CB)
![Static Badge](https://img.shields.io/badge/matplotlib-lightblue)
![Static Badge](https://img.shields.io/badge/OrdinalEncoder-blue)
![Static Badge](https://img.shields.io/badge/sklearn-6A5ACD)
![Static Badge](https://img.shields.io/badge/pipeline-purple)
![Static Badge](https://img.shields.io/badge/PCA-pink)
![Static Badge](https://img.shields.io/badge/GridSearchCV-F4A460)
![Static Badge](https://img.shields.io/badge/бустинг-6495ED)

## Этапы проекта
- Описание данных и загрузка
- Предобработка данных
- Подготовка данных для обучения моделей
    - категориальные признаки
    - деление на выборки
- Обучение моделей
    - CatBoostRegressor
    - LGBMRegressor
    - DecisionTreeRegressor
- Анализ моделей
- Вывод

  ## Вывод
Мы обучили 3 модели на предоставленных данных об авто - Catboost, LightGBM, Decision Tree. Более точной оказалась LightGBM с RMSE = 1591.     На втором месте по точности Catboostc RMSE = 1659. Далее идет DecisionTree с RMSE = 1947.
LightGBM - лучшая модель для нашей задачи. На тесте показала хороший результат RMSE = 1579, уверенно пройдя проверку на адекватность константной моделью (RMSE = 4818).

## PS
<a href="https://ru.freepik.com/free-vector/gradient-mini-car-illustration_58513097.htm#page=2&query=%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C&position=6&from_view=search&track=sph">Изображение от pikisuperstar</a> на Freepik

