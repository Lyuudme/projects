# Отток клиентов банка  

<p align="center">
  <img width="300" heihgt="100" src="img/ONKJB70.jpg">
</p>  

## Задача проекта
На основе данных из банка определить клиента, который может уйти.  

## Описание проекта  
Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.  
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком..  

## Навыки и инструменты  
![Static Badge](https://img.shields.io/badge/pandas-AFEEEE)
![Static Badge](https://img.shields.io/badge/numpy-5F9EA0)
![Static Badge](https://img.shields.io/badge/seaborn-CD5C5C)
![Static Badge](https://img.shields.io/badge/matplotlib-C0C0C0)
![Static Badge](https://img.shields.io/badge/SMOTE-48D1CC)
![Static Badge](https://img.shields.io/badge/sklearn-AFEEEE)
![Static Badge](https://img.shields.io/badge/pipeline-F08080)
![Static Badge](https://img.shields.io/badge/PCA-BC8F8F)
![Static Badge](https://img.shields.io/badge/GridSearchCV-696969)
![Static Badge](https://img.shields.io/badge/RandomizedSearchCV-87CEEB)

## Этапы проекта
- Описание данных и загрузка
- Предобработка данных
- Подготовка признаков
- Деление на выборки
- Исследование баланса классов
- Модели без баланса классов
    - DecisionTreeClassifier
    - RandomForestClassifier
    - LogisticRegression
- Взвешивание классов
- Upsampling
- Изменение порога
- Сравнение моделей
- Вывод

  ## Вывод
Дисбаланс классов влияет на качество модели.

Дерево решений - единственная модель, у которой метрики f1 и auc_roc не сильно отличаются при дисбалансе и балансе.

Модель лог.регрессии без учета дисбаланса классов показала наихудший результат, но все равно оказалась лучше Dummy модели.

Наилучшая модель - Случайный лес с class_weight='balanced' с метриками на трейне: f1=0.62 и roc_auc=0.88 и на тесте: f1=0.63 и roc_auc=0.77.  

  ## PS  
  <a href="https://ru.freepik.com/free-vector/business-background-design_1086763.htm#page=2&position=48&from_view=author">Изображение от Vectorarte</a> на Freepik






