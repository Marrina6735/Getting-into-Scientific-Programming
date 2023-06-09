---
## Front matter
lang: ru-RU
title:  Графики.
author: Коняева Марина Александврона
institute: Российский Университет Дружбы Народов
date: 18 май, 2023, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Цель работы

Научиться строить различные виды графиков: параметрические, неявных функций, в полярных координатах. Обучиться работе с комплексными числами, изображать их на координатной плоскости.  

# Выполнение лабораторной работы

## Параметрические графики 

Построим график трёх периодов циклоиды радиуса 2. Для этого определим параметр как вектор в некотором диапазоне, затем вычислим x и y.

![](image/01.png){width=50% height=50%}  
 
Полученный график : 

![](image/02.png){width=50% height=50%}   

## Полярные координаты 

Графики в полярных координатах строятся аналогичным образом. Построим улитку Паскаля.

![](image/03.PNG){width=50% height=50%}  

Полученный график:

![](image/04.PNG){width=50% height=50%}

## Полярные координаты 

Более того, можно построить данный график в полярных осях.

![](image/05.PNG){width=50% height=50%}

Полученный график:

![](image/06.PNG){width=50% height=50%}

## Графики неявных функций  

Следует построить неявно определённую функцию с помощью ezplot. Зададим график функции, используя лямбда-функцию.  

![](image/07.PNG){width=50% height=50%}  

После чего построим ее график.

![](image/08.PNG){width=50% height=50%} 

## Графики неявных функций  

Найдём уравнение касательной к некоторой окружности. Сначала построим круг, используя лямбда-функцию. Далее найдём уравнение касательной.

![](image/09.PNG){width=40% height=40%}
 
Полученный график: 

![](image/10.PNG){width=40% height=40%} 

## Комплексные числа

Зададим два комплексных числа и запишем основные арифметические операции с ними: сложение,вычитание,  умножение, деление.  

![](image/11.PNG){width=40% height=50%} 

Построим графики в комплексной плоскости, используя команду compass, используя команды, показанные ниже: 

![](image/12.PNG){width=40% height=50%} 

## Комплексные числа

Полученный график:

![](image/13.PNG){width=50% height=50%} 

## Специальные функции  

Построим гамма-функцию Г(х+1) и n! на одном графике.

![](image/15.PNG){ #fig:015 width=40% height=40%} 

Полученный график:

![](image/16.PNG){ #fig:016 width=40% height=40%}

## Специальные функции

Разделив область значения на отдельные интервалы, можно убрать артефакты вычислений. 

![](image/17.PNG){ width=30% height=30%}

Полученный график:

![](image/18.PNG){width=40% height=40%}

# Вывод  

В ходе выполнения данной работы я научилась строить различные виды графиков: параметрические, неявных функций, в полярных координатах. Также поработала с комплексными числами, научилась изображать их на координатной плоскости. А также построила гамма-функцию и график факториала. 