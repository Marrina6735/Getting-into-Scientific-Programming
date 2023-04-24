---
## Front matter
title: "ОТЧЕТ ПО 6 ЭТАПУ ИНДИВИДУАЛЬНОГО ПРОЕКТА"
subtitle: "Размещение двуязычного сайта на Github"
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

Размещение двуязычного сайта на Github.

# Задание

1. Сделать поддержку английского и русского языков.
2. Разместить элементы сайта на обоих языках.
3. Разместить контент на обоих языках.
4. Сделать пост по прошедшей неделе.
5. Добавить пост на тему по выбору (на двух языках).

# Выполнение лабораторной работы

1. Сделать поддержку английского и русского языков. Разместить элементы сайта на обоих языках. Разместить контент на обоих языках. (Изображение 1.1-3)

![ссылки на научные и библиометрические ресурсы](image/i6.1.png){ #fig:001 width=100% }
*Изображение 1.1 Сделать записи для персональных проектов*

![ссылки на научные и библиометрические ресурсы](image/i6.2.png){ #fig:001 width=100% }
*Изображение 1.2 Сделать записи для персональных проектов*

![ссылки на научные и библиометрические ресурсы](image/i6.3.png){ #fig:001 width=100% }
*Изображение 1.3 Сделать записи для персональных проектов*

2. Добавим к сайту пост по прошедшей неделе (Изображение 2.1)

![пост по прошедшей неделе](image/i6.4.png){ #fig:001 width=100% }
*Изображение 2.1 пост по прошедшей неделе*

3. Добавить пост на тему по выбору (Изображение 3.1)

![Работа с библиографией](image/i6.5.png){ #fig:001 width=100% }
*Изображение 3.1 языки научного программирования*


# Выводы

В ходе выполнения данного этапа индивидуального проекта добавили двуязычный сайт на Github, а также создали посты.
