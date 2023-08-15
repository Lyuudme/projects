# Прогнозирование заказов такси  

<p align="center">
  <img width="300"  src="img/ThanitJuly_42.jpg">
</p>  

## Задача проекта
Разработка системы предсказания объема заказа.  

## Описание проекта  
Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания.  

## Навыки и инструменты  
![Static Badge](https://img.shields.io/badge/pandas-87CEEB)
![Static Badge](https://img.shields.io/badge/numpy-F0E68C)
![Static Badge](https://img.shields.io/badge/statsmodels-yellow)
![Static Badge](https://img.shields.io/badge/matplotlib-lightblue)
![Static Badge](https://img.shields.io/badge/StandardScaler-DC143C)
![Static Badge](https://img.shields.io/badge/sklearn-00CED1)
![Static Badge](https://img.shields.io/badge/pipeline-5F9EA0)
![Static Badge](https://img.shields.io/badge/PCA-FFFFE0)
![Static Badge](https://img.shields.io/badge/GridSearchCV-696969)

## Этапы проекта
- Описание данных и загрузка
- Исследование и анализ данных
- Создание признаков
    - календарные
    - отстающие
    - скользящее среднее
- Подготовка данных к обучению
- Обучение моделей
    - CatBoostRegressor
    - LGBMRegressor
- Сравнение моделей
- Проверка лучшей модели
- Вывод

## Вывод
Обучили `Catboost`, `LightGBM` - лучший RMSE показала `LightGBM` 26.239, `Catboost` отстал всего на 0.001 по RMSE на валидации, при этом значительно уступил по времени обучения.   
Для заказчика выбрана модель `LightGBM`.    
На трейне она показала результат RMSE = 41 vs 59 - у модели с предыдущим предсказанием значения ряда. Модель прошла проверку на адекватность.

## PS
<a href="https://ru.freepik.com/free-vector/online-application-for-call-taxi-service-by-smart-phone_17629097.htm#query=%D1%82%D0%B0%D0%BA%D1%81%D0%B8%20%D0%B6%D0%B5%D0%BB%D1%82%D1%8B%D0%B9&position=10&from_view=search&track=ais">Изображение от jcomp</a> на Freepik


