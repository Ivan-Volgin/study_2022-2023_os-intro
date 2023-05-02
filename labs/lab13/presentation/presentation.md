---
## Front matter
lang: ru-RU
title: Лабораторная работа №13
subtitle: Операционные системы
author:
  - Волгин И.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 2 мая 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

## Докладчик

  * Волгин Иван Алексеевич
  * Студент по программе Компьютерные и информационные науки
  * Российский университет дружбы народов
  * <https://github.com/Ivan-Volgin>

## Цели и задачи

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

## Создание нужный подкаталог ~/work/os/lab_prog

![](image/1.png){#fig:001 width=70%}

## Создание в нем файлы calculate.h, calculate.c, main.c и ввести код в них

![](image/2.png){#fig:002 width=49%}
![](image/3.png){#fig:003 width=49%}

## Код файлов calculate.h и main.c

![](image/4.png){#fig:004 width=49%}
![](image/5.png){#fig:005 width=49%}

## Выполнение компиляцию программы посредством gcc.

![](image/6.png){#fig:006 width=70%}

## Создание Makefile

![](image/7.png){#fig:007 width=49%}
![](image/8.png){#fig:008 width=49%}

## Запуск gdb и программы в нем

![](image/9.png){#fig:009 width=49%}
![](image/10.png){#fig:010 width=49%}

## Анализ кода файлов calculate.c  и main.c с помощью утилиты splint.

![](image/11.png){#fig:011 width=49%}
![](image/12.png){#fig:012 width=49%}

## Выводы

В ходе выполнения данной лабораторной работы я приобрел простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

