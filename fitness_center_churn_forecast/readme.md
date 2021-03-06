# Аналитика в сети фитнес-центров

Сеть фитнес-центров разрабатывает стратегию взаимодействия с клиентами на основе аналитических данных.

Основная проблема фитнес-клубов - отток клиентов. Чаще всего, клиенты просто перестают ходить в зал без расторжения договора. Наша задача научиться определять параметры, по которым можно будет сказать, что клиент собирается покинуть наш фитнес-центр и разработать стратегию удержания.

**Цель**: Подготовить план по удержанию клиентов

**Задачи**:
* Научиться прогнозировать вероятность оттока для каждого клиента (задача бинарной классификации);
* Сформировать типичные портреты клиентов (задача кластеризации);
* Сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами.

**Cтек**: pandas, numpy, seaborn, plotly, BayesianOptimization, XGBoost, scipy (dendrogram, linkage), sklearn (StandardScaler, GridSearchCV, RandomizedSearchCV, RandomForest, GradientBoosting etc)

## Краткий вывод
* Обучили несколько моделей и по метрикам выбрали лучшую модель (Gradient Boosting)
* Сегментировали пользователей и описали каждую группу
* Разработали рекомендации по взаимодействую с клиентами

## Установка
**Дополнительно нужно обновить библиотеку plotly и установить библиотеки bayesian-optimization и XGBoost**

```python
pip install --upgrade plotly
pip install xgboost
pip install bayesian-optimization
```
## Важно
**Рекомендую открыть работу через nbviewer, так как на GitHub не отображаются интерактивные графики plotly**.
[Смотреть проект](https://nbviewer.jupyter.org/github/arsBadoyan/practicumProjects/blob/main/fitness_center_churn_forecast/fitness_center_churn_forecast.ipynb)
