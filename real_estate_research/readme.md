# Исследование объявлений о продаже квартир

Имеются данные с сервиса Яндекс.Недвижимость - архив объявлений о продаже квартир в Санкт-Петербурге и соседних городах за несколько нет. 

**Цель**. Построить модель прогнозирования рыночной стоимости недвижимости.

**Задача**. Выявить параметры и ценообразующие факторы.

**Стек**: pandas, sklearn (RandomForest, GradientBoosting, RandomizedSearch, GridSearch etc.), XGBoost, plotly, seaborn, numpy, tqdm.

## Краткий вывод
* Выявили факторы, влияющие на стоимость недвижимости
* Обучили несколько моделей, по метрика выбрали лучшую - Gradient Boosting
* Наиболее важные признаки для модели - общая площадь, удаленность от центра и город

## Установка
**Дополнительно нужно обновить библиотеку sklearn и установить библиотеку XGBoost**

```python
pip install --upgrade sklearn
pip install xgboost
```
## Важно
**Рекомендую открыть работу через nbviewer, так как на GitHub не отображаются интерактивные графики plotly**.
[Смотреть проект](https://nbviewer.jupyter.org/github/arsBadoyan/practicumProjects/blob/main/real_estate_research/real_estate_research.ipynb)
