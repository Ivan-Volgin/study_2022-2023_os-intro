---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Основы информационно безопасности"
author: "Волгин иван Алексеевич, НКАбд-01-22"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
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
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Задание

1. Установить на виртуальную машину дистрибутив Rocky.
2. Получите следующую информацию.
    1. Версия ядра Linux (Linux version).
    2. Частота процессора (Detected Mhz processor).
    3. Модель процессора (CPU0).
    4. Объем доступной оперативной памяти (Memory available).
    5. Тип обнаруженного гипервизора (Hypervisor detected).
    6. Тип файловой системы корневого раздела.

# Выполнение лабораторной работы

1. В начале я создаю виртуальную машину, задаю ей имя, тип и версию (рис. [-@fig:001]).

![Создание виртуальной машины](image/1.png){#fig:001 width=70%}

2. Устанавливаю для нее выделяемый размер оперативной памяти и число процессоров (рис. [-@fig:002]).

![Размер оперативной памяти и число процессоров](image/2.png){#fig:002 width=70%}

3. Далее устанавливаю размер жесткого диска для виртуальной машины (рис. [-@fig:003]).

![Размер жесткого диска](image/3.png){#fig:003 width=70%}

4. После этого устанавливаю iso-образ Rocky в оптический привод (рис. [-@fig:004])..

![Установка iso-образа](image/4.png){#fig:004 width=70%}

5. Начинаю настройку системы. Устанавливаю языки поддерживаемые системой, раскладки клавиатуры, часовой пояс. Так же указываю место установки, выбираю набор инструментов, выключаю KDUMP, создаю пользователя и root-пароль и задаю имя хоста (рис. [-@fig:005]).

![Настройка ОС](image/5.png){#fig:005 width=70%}

6. Подключаю образ диска дополнительной гостевой ОС (рис. [-@fig:006]).

![Подключаю образ диска дополнительной гостевой ОС](image/6.png){#fig:006 width=70%}

7. Первые пять пунктов домашнего задания (рис. [-@fig:007]).

![ДЗ 1-5](image/7.png){#fig:007 width=70%}

8. Пункт 6 домашнего задания (рис. [-@fig:008]).

![ДЗ 8](image/8.png){#fig:008 width=70%}

# Выводы

В ходе выполнения этой лабораторной работы я установил ОС Rocky на виртуальную машину и сделал минимально необходимые ее настройки.

