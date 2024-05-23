# Анализ текстов

## Описание проекта
Интернет-магазин «Викишоп» запускает новый сервис, позволяющий пользователям редактировать и дополнять описания товаров, как в вики-сообществах. Требуется инструмент для поиска токсичных комментариев и их отправки на модерацию.

## Навыки и инструменты
- python
- pandas
- numpy
- nltk.stem.WordNetLemmatizer
- sklearn.feature_extraction.text.TfidfVectorizer
- sklearn.linear_model.LogisticRegression
- sklearn.linear_model.SGDClassifier
- sklearn.tree.DecisionTreeClassifier
- sklearn.ensemble.RandomForestClassifier

## Вывод
В проекте была проведена работа по обработке текстов и обучению моделей для классификации комментариев. В результате обучения и тестирования выбрана модель LogisticRegression, показавшая значение метрики F1 = 0.798 на тестовой выборке. Модель соответствует требованиям по качеству (F1 >= 0.75) и рекомендована для использования.

