
# Различные варианты кластеризации 


**Кому может быть интересно:**

- Площадки объявлений
- Интернет-сервисы
- Интернет-магазины
- Ритейл / E-commerce
- IT-компания
- Стартапы
- Услуги для бизнеса [b2b] (аутсорс консалтинг аудит)


**Навыки и инструменты:**

- Pandas
- matplotlib
- scipy
- GaussianMixture
- Сluster.hierarchy
- KMean
- DBSCAN()
- PCA
- K-Medoids



**Задачи:** 

Кластеризовать пациентов из задачи создания нейронной сети для мультиклассовой классификации. 


**Что сделано :**

- Данные загружены и проверены;
- Текстовые данные закодированны техникой One Hot Encoding;
- Построена модель KMeans, расчитано необходимое число кластеров техникой "Elbow curve", произведено сравнение разбиения и входных данных
- Построена иерархическая модель кластеризации и  произведено сравнение разбиения и входных данных
- Построена гауссовская модель кластеризации, расчитано необходимое число кластеров аналитическими критериями BIC и AIC, произведено сравнение разбиения и входных данных
- Построена модель кластеризации методом К-медоидов 
- Построена модель кластеризации методом DBSCAN с предварительной сверткой векторов-признаков методом главных компонент и последующей стандартизацией переменных 
- Проверена целесообразность свертки методом главных компонент с последующей стандартизацией независимых переменных для гауссовской модели кластеризации и кластеризации методом к-средних.