# Оптимизация производственных расходов в металлургическом комбинате

## Описание проекта
Тема: Промышленность. Оптимизация производственных расходов металлургического комбината. Цель: уменьшить потребление электроэнергии путём контроля температуры стали.

## Навыки и инструменты
- python
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sklearn.model_selection
- sklearn.metrics
- sklearn.linear_model.LinearRegression
- sklearn.preprocessing.StandardScaler
- sklearn.dummy.DummyRegressor
- catboost.CatBoostRegressor
- lightgbm.LGBMRegressor

## Вывод
На основе данных, полученных из различных источников, была построена модель, предсказывающая температуру стали. Лучшей моделью оказалась CatBoostRegressor с MAE 5.86 на тестовой выборке. Анализ значимости признаков показал, что наибольшее влияние на температуру оказывают начальная температура, время нагрева, время между замерами, и количество добавляемых материалов. Эти результаты позволяют рекомендовать оптимизацию этих параметров для улучшения производственного процесса.

