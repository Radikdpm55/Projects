## Анализ эксперимента по сравнению фичей (рабочий)

[ссылка на работу]([https://github.com/Radikdpm55/Projects/tree/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%8D%D0%BA%D1%81%D0%BF%D0%B5%D1%80%D0%B8%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%20%D0%BF%D0%BE%20%D1%81%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D1%8E%20%D1%84%D0%B8%D1%87%D0%B5%D0%B9](https://github.com/Radikdpm55/Projects/blob/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%8D%D0%BA%D1%81%D0%BF%D0%B5%D1%80%D0%B8%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%20%D0%BF%D0%BE%20%D1%81%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D1%8E%20%D1%84%D0%B8%D1%87%D0%B5%D0%B9/Experiment%20HQ%20vs%20antifraud-Copy1%20(1).ipynb))
### Описание проекта:

**Заказчик** : Product Owner

**Задача :**

Определить, какой из инструментов (HQ или Antifraud) лучше отвечает потребностям бизнеса

### Навыки и инструменты

- **python** :
    - **pandas**
    - **numpy**
    - **matplotlib**
    - **sqlalchemy**
    - **clickhouse_connect**
    - **scipy.stats (stats, ttest_ind)**
- **SQL** :
    - **MySQL**
    - **ClickHouse**


### Результат

Разработана метрика для оценки эксперимента, проведён тест на стат значимость различий по этой метрике между группами. 

Рассчитаны доверительные интервалы (95%), на основании анализа принято решение о приоритизации фич
