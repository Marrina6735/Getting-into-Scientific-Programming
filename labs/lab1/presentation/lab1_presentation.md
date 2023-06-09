---
## Front matter
lang: ru-RU
title: Лабораторная работа №3
author: |
    Коняева Марина НФИбд-01-21
date: 27.04.2022

## Formatting
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

# Markdown 

## Цель работы

- Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

## Задание 

1. Сделайте отчёт по лабораторной работе 2 в формате Markdown.
2. Предоставить отчёты в 3 форматах: pdf, docx и md (в архиве)

## Теоретическое введение

Markdown — язык текстовой разметки, созданный писателем и блогером Джоном Грубером. Он предназначен для создания красиво оформленных текстов в обычных файлах формата TXT. Вам не нужны громоздкие процессоры вроде Word или Pages, чтобы создавать документы с жирным или курсивным начертанием, цитатами, ссылками и даже таблицами. Достаточно запомнить простые правила Markdown, и можно писать хоть в «Блокноте». Хотя специализированные Markdown-редакторы, конечно, намного удобнее.

## Выполнение лабораторной работы

1. Создадим файл <i>report.md</i> и в нем шаблон отчета

2. Создали папку <i>images</i> для хранения картинок и перенесли туда скриншоты из второй лабороторной работы.

##

3. Запишем отчет по лабораторной работе 2 в markdown file

![отчет в markdown](image/1%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA.png){ #fig:001 width=100% }

##

4. Конвертируем md файл в pdf используя <i>pandoc</i>.

![сконвертируем файл в форматах](image/2%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA.png){ #fig:001 width=100% }

##

5. Конвертируем md файл в docx используя <i>pandoc</i>.
![сконвертируем файл в форматах](image/3%D0%A0%D0%B8%D1%81%D1%83%D0%BD%D0%BE%D0%BA.png){ #fig:001 width=100% }

## Вывод

В ходе данной лабораторной работы научились оформлять отчеты с помощью легковесного языка разметки Markdown.