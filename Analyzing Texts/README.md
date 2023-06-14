# Анализ комментариев

## Описание проекта

Необходимо обучить модель выделять токсичные комментарии, чтобы отправить их на модерацию. 




## Инструменты

- **python**
- **pandas**

- nltk.stem.**WordNetLemmatizer**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**



## Вывод

Лучшей из рассмотренных моделей для определения токсичных комментариев стала CatBoostClassifier.
