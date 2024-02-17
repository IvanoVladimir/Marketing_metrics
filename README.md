<!--###### -

### [***`Coдержание`***](#-) :<br>

 - [***Краткое описание проекта***](#Краткое-описание-проекта)
 
 - [***Цель проекта***](#Цель-проекта)
 
 - [***Ключевые задачи***](#Ключевые-задачи)
 
 - [***Ссылка на проект***](https://github.com/IvanoVladimir/karpov_courses/blob/main/Final_project/Mobile_games.ipynb 'Ссылка на проект')

-----> 

### [***`Краткое описание`***](#-)<br>

**Название:** *Оценка маркетинговых кампаний с помощью метрик*

**Стек:**

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-424242?style=for-the-badge&logo=Jupyter&logoColor=BA7400)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/python-1C648D?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Redash](https://img.shields.io/badge/Redash-C85A47?style=for-the-badge&logo=Redash&logoColor=ffdd54)](https://redash.io/)
[![PostgreSQL](https://img.shields.io/badge/postgresql-424242?style=for-the-badge&logo=postgresql&logoColor=005E9F)](https://www.postgresql.org/)

   **Примечание:** Отображение графиков и дашборда не работает даже через  Jupyter nbviewer, решением может быть загрузка файла на локальную машину для дальнейшего просмотра. SQL запросы для простоты отображены в markdown формате для демонстрации умения написания запросов.

---

### [***`Цель`***](#-)<br>

**Оценить, какой из каналов привлечения сработал лучше для приложения по доставке продуктов. Обосновать свои выводы с помощью выбранных метрик и построенных визуализаций.**
 
---

### [***`Этапы выполнения`***](#-)<br>

1. Рассчитал *ROI* для каждого рекламного канала
2. Посчитал среднюю стоимость заказа привлечённых пользователей за первую неделю использования приложения с 1 по 7 сентября 2022 года
3. Для каждой рекламной кампании посчитал *Retention* 1-го и 7-го дня у привлечённых пользователей
4. Для каждого дня посчитал накопительный *ARPPU* и затраты на привлечение одного покупателя(*CAC*)
5. По всем метрикам построил графики и написал выводы
6. Из графиков построил дашборд

---

### [***`Результаты`***](#-)<br>

* Построил графики и дашборд
* Выяснил, что:
  * Первая кампания имеет **положительный ROI**, у второй рекламной кампании **ROI отрицательный**
  * По среднему чеку без статистических тестов отличаются ли группы сказать нельзя, но можно предположить, что различия несущественные. Средний чек во второй группе с **отрицательным ROI даже немного выше**
  * *Retention* почти **в два раза выше у первой группы. Пользователи из первой группы приносят нам больше денег**
  * Для первой рекламной кампании накопительный *ARPPU* **превысил затраты на привлечение одного покупателя (CAC) уже на 5-й день**, тогда как для второй кампании даже **на 7-й день значение CAC всё ещё превышало значение ARPPU**

**Вывод:** канал привлечения пользователей первой рекламной кампании оказался лучше

---

## [***К проекту***](https://github.com/IvanoVladimir/Marketing_metrics/blob/main/Marketing%20metrics.ipynb 'Ссылка на проект') 
<!--## [***К содержанию ->***](#-)-->
<div id="badges" align="center">

<!-- [![GitHub last commit](https://img.shields.io/github/last-commit/IvanoVladimir/E-commerce.svg)](https://github.com/IvanoVladimir/E-commerce) 
[![GitHub commit activity the past week, 4 weeks, year](https://img.shields.io/github/commit-activity/y/IvanoVladimir/E-commerce.svg)](https://github.com/IvanoVladimir/E-commerce)--> 
[![GitHub repo size in bytes](https://img.shields.io/github/repo-size/IvanoVladimir/Marketing_metrics.svg)](https://github.com/IvanoVladimir/E-commerce)
![ViewCount](https://views.whatilearened.today/views/github/IvanoVladimir/Marketing_metrics.svg?cache=remove)
![GitHub top language](https://img.shields.io/github/languages/top/IvanoVladimir/Marketing_metrics.svg?style=flat)

</div>
