# DS 101

Introduction to Data Science with Python


## Описание


Цель этого воркшопа показать, что data science с правильный набором инструментов гораздо более доступная сфера деятельности, чем может казаться на первый взгляд. Мы ознакомся с тем, как обрабатывать данные, строить модели и оценивать их эффективность. Во второй половине мы попробуем поработать над некоторыми датасетами в группах.
К концу воркшопа вы выйдете с твердым пониманием необходимых инструментов и основ data science.


## Цели
Начнем мы с простых примеров обработки сырых данных и получение из них инсайтов. Для этого мы будем использовать библиотеку Pandas, которая де-факто стала стандартом индустрии.

После того, как мы получим понимание того, что собой представляют наши данные, мы начнем процесс построение моделей.
Используя Scikit Learn, мы рассмотрим то, как построить модель и оценить ее точность для использования в реальных приложения.

Наконец, иметь рабочую модель, которая хорошо описывает данные, не достаточно. Необходимо, как-то представить полученные инсайты более широкому кругу, для этого мы рассмотрим способы визуализации данных.

## Необходимые знание
- Базовое понимание Python
- Понимание основ математики и статистики
- Любопытство и желание работать



##Outline

- Introduction to Jupyter [15 min]
  - What is Jupyter and why
  - Using the notebook to create intactive analysis
  - Sharing notebooks
- Introduction to Pandas [45 min]
  - Reading data
  - Getting a feel of the data
  - Basic statistics
  - Dropping the cruft
  - Quick and dirty visualization
  - The power of the groupby
  - Advance mappings for custom statistics
- Break [5 min]
- Introduction to SciKit Learn [45 min]
  - What is a model
  - How models fit to data
  - Build a few basic models with data from pandas exercises
  - Understanding the error in your model
  - Steps to building better and better models
- Break [5 min]
- Hacking Challenges [15 min]
  - Putting the above work together in teams with prepared challenges
  - Advanced topics as requested
    - Deep Learning
    - Natural Language Processing
  - Where to learn more
  - Get started with Kaggle

## Инструкции по установке

1. Скачайте соответствующий вашей системе файл установки (выбирайте версию Python 3.5) http://conda.pydata.org/miniconda.html.
2. Процесс установки Miniconda для вашей системы описан здесь http://conda.pydata.org/docs/install/quick.html.
3. Для проверки правильности установки conda наберите в командной строке: “conda list”, вы должны увидеть список установленных пакетов.
4. Если у вас не установлен git, то самое время это сделать https://git-scm.com/downloads, https://git-scm.com/book/en/v2/Getting-Started-Installing-Git.
5. Перейдите в папку в который содерится этот код, откройте термина и выполните комманду:
```$ conda env create```
6. Это создаст необходимый нам environment, дальше нам нужно будет его загрузить выполнив комманду:
```$ source activate ds101```
7. Все готово, осталось запустить jupyter:
```$ jupyter notebook```
