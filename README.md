<img width="1317" height="332" alt="изображение" src="https://github.com/user-attachments/assets/54e28e9c-9734-4347-a131-bda9d2798ece" />

# Text Classification of Tweets Using Logistic Regression

Data from Kaggle: https://www.kaggle.com/datasets/umitka/twitter-toxic-tweets

В этом проекте я использовал бинарную логистическую регрессию для классификации твитов на токсичные (1) и нетоксичные (0) на набое данных из более 30 тысяч реальных твитов.
Результаты следующие:

Основные метрики (Classification Report)

| Класс          | Precision (Точность) | Recall (Полнота) | F1-Score | Support (Объем) |
|----------------|--------------------|----------------|----------|----------------|
| 0 (Отрицательный) | 0.98               | 0.93           | 0.96     | 5945           |
| 1 (Положительный) | 0.48               | 0.80           | 0.60     | 448            |
| **Accuracy**      |                    |                | 0.93     | 6393           |
| **Macro Avg**     | 0.73               | 0.87           | 0.78     | 6393           |


Матрица ошибок (Confusion Matrix)

,Предсказано: 0,Предсказано: 1
Фактически: 0,5556 (TN),389 (FP)
Фактически: 1,88 (FN),360 (TP)
