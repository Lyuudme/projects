# Прогнозирование заказов такси  

<p align="center">
  <img width="300"  src="img/ThanitJuly_42.jpg">
</p>  

## Задача проекта
Разработка системы предсказания объема заказа.  

## Описание проекта  
Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания.  

## Навыки и инструменты  
![Static Badge](https://img.shields.io/badge/pandas-green)
![Static Badge](https://img.shields.io/badge/numpy-yellowgreen)
![Static Badge](https://img.shields.io/badge/seaborn-yellow)
![Static Badge](https://img.shields.io/badge/matplotlib-lightblue)
![Static Badge](https://img.shields.io/badge/plotly-blue)
![Static Badge](https://img.shields.io/badge/sklearn-darkblue)
![Static Badge](https://img.shields.io/badge/pipeline-purple)
![Static Badge](https://img.shields.io/badge/PCA-pink)
![Static Badge](https://img.shields.io/badge/GridSearchCV-orange)

## Этапы проекта
- Описание данных и загрузка
- Предобработка данных
- Анализ данных
- Функции для вычисления промежуточной и итоговой sMAPE
- Подготовка данных к построению моделей
- Обучение моделей. Этап Флотации.
- Обучение моделей. Этап Final.
- Проверка лучших моделей на тесте
- Вывод

  ## Вывод
  Лучший результат на флотации показала линейная регрессия с sMAPE = 6.26.  
  Лучший результат final показал Случайный лес sMAPE = 9.02. Итоговая sMAPE на train = 8.33.

  Итоговая sMAPE на test получилась хуже, чем на train 9.38 vs 8.33.

  Итоговая sMAPE наших лучших моделей на тесте получилась лучше, чем константной 9.38 vs 9.83.

  ## PS


