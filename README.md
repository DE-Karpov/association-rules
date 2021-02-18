# О проекте
Comaru - это комбинированный алгоритм по нахождению самых эффективных правил, найденных с помощью алгоритмов ассоциативных правил.

---

## Технологии
- Python
- Jupiter Notebook
- [Streamlit](https://docs.streamlit.io/en/stable/api.html "О Streamlit") 

---

## Данные
**Basket.csv** содержит данные о произведенных в магазине транзакциях.
Он содержит 20 столбцов и 7501 объект(транзакцию). 
**retail_dataset.csv** содержит данные о произведенных в продуктовом транзакциях.
Он содержит 7 столбцов и 316 объектов(транзакций)

---

## Алгоритмы ассоциативных правил
- Apriori
- FP-Growth
- ECLAT
- FPMax

---

## Запуск
### Streamlit  
`streamlit run comaru.py`  

### Google colab  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DE-Karpov/comaru/blob/develop/comaru.ipynb#scrollTo=yFOju6zmrc3k&uniqifier=5)

---

## Описание работы

### Тема
Анализ эффективности методов поиска ассоциативных правил

### Решаемая проблема 
Cуществует множество алгоритмов ассоциативных правил, но как понять, какой из них работает эффективнее?
Объединение нескольких подходов для поиска ассоциативных правил дадут нам наиболее уверенный результат.

### Цель работы
Исследование методов ассоциативных правил, реализация алгоритмов.
Придумать и реализовать критерии выявления качества между алгоритмами ассоциативных правил.
Создать программный модуль(библиотеку) для повышения эффективности работы с ассоциативными правилами.

### Задачи исследования
1. Изучить существующие ассоциативные правила, сравнение.
2. Описать существующую задачу и найти подходящую выборку.
3. Анализ критериев алгоритмов ассоциативных правил.
4. Создание собственного критерия сравнения эффективности ассоциативных правил.

### Ожидаемые результаты
Готовый алгоритм, определяющий наиболее эффективные правила, используя новый критерий отбора.
