---
## Front matter
title: "ОТЧЕТ ПО ЛАБОРАТОРНОЙ РАБОТЕ № 3"
subtitle: "Введение в работу с Octave"
author: "Коняева Марина Александровна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Ознакомится с основными операциями для работы в Octave..


# Выполнение лабораторной работы

## Простейшие операции

Включим журналирование сессии. Продемонстрируем, что Octave можно использовать как простейший калькулятор. Для этого вычислим выражение, зададим вектор и ковектор, а также матрицу.

![Простейшие операции](image/01.PNG){ #fig:001 width=70% height=70%}

## Операции с векторами

Зададим два вектора-столбца, выполним операции сложения векторов, Скалярное умножение, Векторное умножение и вычислим норму вектора.


![Операции с векторами 1](image/02.PNG){ #fig:002 width=70% height=70%}


![Операции с векторами 2](image/03.PNG){ #fig:003 width=70% height=70%}


## Вычисление проектора


Введём два вектора-строки. Вычислим проекцию вектора u на вектор v.

![Вычисление проектора](image/04.PNG){ #fig:004 width=70% height=70%}

##	Матричные операции


Введём матрицы A и B. Вычислим произведение матриц AB, затем вычислим произведение матриц B^TA. Вычислим 2A − 4I. Найдём определитель | A |, обратную матрицу A−1, собственные значения и ранг матрицы.

![Вычисление проектора](image/05.PNG){ #fig:005 width=70% height=70%}

![Вычисление проектора](image/06.PNG){ #fig:006 width=70% height=70%}

![Вычисление проектора](image/07.PNG){ #fig:007 width=70% height=70%}

##	Построение простейших графиков


Построим график функции sin x на интервале [0, 2π]. Создадим вектор значений x, зададим вектор y = sin x, построим график. В результате получим следующий график. Затем улучшим внешний вид графика. Зададим красный цвет для линии и сделаем её потолще, подгоним диапазон осей, нарисуем сетку, подпишем оси, сделаем заголовок графика и зададим легенду.

![Построение простейших графиков 1](image/08.PNG){ #fig:008 width=70% height=70%}

Сначала был получен следующий график:

![Построение простейших графиков 2](image/09.PNG){ #fig:009 width=70% height=70%}

Затем получили более красивый и наглядный график заданной функции:

![Построение простейших графиков 3](image/10.PNG){ #fig:010 width=70% height=70%}

### 6.	Два графика на одном чертеже


Для того чтобы начертить два графика на одном чертеже, нужно использовать команду hold on. Сделаем один график, затем добавим график регрессии, зададим сетку, оси и легенду.

![Два графика на одном чертеже 1](image/11.PNG){ #fig:011 width=70% height=70%}

![Два графика на одном чертеже 2](image/12.PNG){ #fig:012 width=70% height=70%}

## График y=x^2 sin x


Зададим вектор x (0, 2pi). Построим график y=x^2 sin x, используя поэлементное возведение в степень и поэлементное умножение. Сохраним графики в виде файлов.

![График y=x^2 sin x](image/13.PNG){ #fig:013 width=70% height=70%}

![График y=x^2 sin x](image/14.PNG){ #fig:014 width=70% height=70%}

![График y=x^2 sin x](image/15.PNG){ #fig:015 width=70% height=70%}


## Сравнение циклов и операций с векторами 
Сравним эффективность работы с циклами и операций с векторами. Для этого вычислим сумму:

![Сумма](image/16.PNG){ #fig:016 width=70% height=70%}


Очистим память и рабочую область фигуры, вычислим сумму с помощью цикла, создадим файл loop_for.m, функции tic и toc служат для запуска и остановки таймера, запустим файл loop_for.m. Вычислим сумму с помощью операций с векторами. Создадим файл loop_vec.m, запустим его. Завершим запись в файл.

Ниже мы можем наблюдать, что с помощью векторов компьютер вычисляет заданную сумму намного быстрее. 

![Сравнение циклов и операций с векторами 1](image/17.PNG){ #fig:017 width=70% height=70%}

![Сравнение циклов и операций с векторами 2](image/18.PNG){ #fig:018 width=70% height=70%}

![Сравнение циклов и операций с векторами 3](image/19.PNG){ #fig:019 width=70% height=70%}

![Сравнение циклов и операций с векторами 4](image/20.PNG){ #fig:020 width=70% height=70%}

# Вывод

В ходе выполнения данной работы я ознакомилась с основными операциями для работы в Octave. 

# Конрольные вопросы 

Контрольные вопросы в данной лабораторной работе отсутствуют.