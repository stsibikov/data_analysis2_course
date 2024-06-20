# [Методы и средства обработки больших данных](https://www.hse.ru/edu/courses/570803085), ВШЭ, весна 2024.

Бизнес-ориентированный курс по аналитике данных, направленный на сегментацию клиентов и работу с текстовыми данными. Оценка за курс 9/10.

## [Обработка данных, кластеризация KMeans, RFM-анализ](clusterization/EDA_KMeans_RFM_analysis.ipynb)  

Обработка данных, EDA, кластеризация и RFM-анализ клиентов банка.

Проект состоит из:
* Обработки данных (работа с пропущенными и категориальными переменными)
* Разбор преимуществ и недостатков алгоритмов кластеризации KMeans и RFM-анализа
* Выбор оптимального количества кластеров для KMeans с использованием метода локтя с разными метриками и иерархической кластеризацией
* Интерпретация результатов кластеризации и изучение клиентских сегментов
* Интерпретация результатов RFM-анализа и определение основных действий для каждого сегмента
* Сравнение результатов K-средних и RFM-анализа

Библиотеки: pandas, matplotlib, sklearn, yellowbrick

## [Текстовый анализ песен](NLP/NLP_songs.ipynb)

Содержание данного ноутбука:
* Текстовая обработка песен Depeche Mode
* Предобработка текстовых данных - лемматизации, стемминг, удаление стоп-слов
* Рассчет метрик TD-IDF
* Обучение модель Word2Vec и сравнение с TD-IDF
* Анализ текстовых данных (вывод наиболее часто/редко встречающихся слова)

Библиотеки: sklearn, pymorphy2, nltk, gensim.
