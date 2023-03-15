# Taxi_Trip_Duration_Prediction

В рамках данного проекта была решена задача построения модели, которая предсказывает общую продолжительность поездок на такси в Нью-Йорке. 

Основной набор данных - это набор данных, выпущенный Комиссией по такси и лимузинам Нью-Йорка, который включает время доставки, географические координаты, количество пассажиров и несколько других переменных.

Для достижения цели были реализованы следущие шаги: 

1) Проведен разведочный анализ данных (EDA). 
2) На основе имеющихся данных, а также данных о погоде из другого соревнования kaggle и встроенном наборе данных о праздниках в США , были созданы новые переменные, которые должны улучшить качество работы моделей (feature engeneering). 
3) В качестве базовой модели была использована Linear Regression. Наилучшее качество на тестовой части данных показали модели Random Forest и XGboost. Для подбора гиперпараметров для XGboost модели был использован фреймворк Optuna.
