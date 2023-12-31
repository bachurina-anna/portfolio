# Анализ результатов А/В-теста для увеличения выручки интернет-магазина 

[**ПЕРЕЙТИ К ПРОЕКТУ**](https://github.com/bachurina-anna/portfolio/blob/main/%D0%9F%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B0%20%D0%B3%D0%B8%D0%BF%D0%BE%D1%82%D0%B5%D0%B7%20%D0%B4%D0%BB%D1%8F%20%D1%83%D0%B2%D0%B5%D0%BB%D0%B8%D1%87%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B2%D1%8B%D1%80%D1%83%D1%87%D0%BA%D0%B8/%D0%9F%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B0%20%D0%B3%D0%B8%D0%BF%D0%BE%D1%82%D0%B5%D0%B7%20(%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D0%BE%D0%B2%20%D0%90%D0%92-%D1%82%D0%B5%D1%81%D1%82%D0%B0)%20%D0%B4%D0%BB%D1%8F%20%D1%83%D0%B2%D0%B5%D0%BB%D0%B8%D1%87%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B2%D1%8B%D1%80%D1%83%D1%87%D0%BA%D0%B8%20%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0.ipynb)

**Цель проекта:** Отделом маркетинга крупного интернет-магазина составлен список гипотез для увеличения выручки.\
Необходимо приоритизировать гипотезы и проанализировать результаты А/В-тестирования. 
    
**Задачи проекта:**
1. Применить фреймворк ICE для приоритизации гипотез, и отсортировать их по убыванию приоритета.
2. Применить фреймворк RICE для приоритизации гипотез, и отсортировать их по убыванию приоритета.
3. Построить график кумулятивной выручки по группам, сделать выводы и предположения.
4. Построить график кумулятивного среднего чека по группам, сделать выводы и предположения.
5. Построить график относительного изменения кумулятивного среднего чека группы B к группе A, сделать выводы и предположения.
6. Построить график кумулятивного среднего количества заказов на посетителя по группам, сделать выводы и предположения.
7. Построить график относительного изменения кумулятивного среднего количества заказов на посетителя группы B к группе A, сделать выводы и предположения.
8. Выявить аномалии в данных. Построить точечные графики количества заказов по пользователям и стоимостей заказов. Расчитать 95 -й и 99-й перцентили количества заказов на пользователя и стоимости заказа. Выбрать границу для определения аномальных пользователей.
9. Рассчитать статистическую значимость различий в среднем количестве заказов на посетителя между группами по «сырым» данным, сделать выводы и предположения.
9. Рассчитать статистическую значимость различий в среднем чеке заказа между группами по «сырым» данным, сделать выводы и предположения.
10. Рассчитать статистическую значимость различий в среднем количестве заказов на посетителя между группами по «очищенным» данным, сделать выводы и предположения.
11. Рассчитать статистическую значимость различий в среднем чеке заказа между группами по «очищенным» данным, сделать выводы и предположения.
12. Проанализировать результаты тестирования и принять решение. 

**Данные:** Для анализа взяты:
1. Список из 9 гипотез по увеличению выручки интернет-магазина (файл 'hypothesis.csv')
2. Данные о заказах интернет-магазина за август 2019 года (файл 'orders.csv')
3. Данные о посещении сайта интернет-магазина за август 2019 года (файл 'visitors.csv')

**Этапы проекта:**
1. Обзор и предобработка данных
2. Приоритизация гипотез
3. Анализ результатов A/B-теста\
   3.1. Графики кумулятивных метрик\
   3.2. Анализ аномальных значений\
   3.3. Расчет статистической значимости между группами по "сырым" данным\
   3.4. Расчет статистической значимости между группами по "очищенным" данным
4. Выводы и  рекомендации
