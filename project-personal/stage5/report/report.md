---
## Front matter
title: "Индивидуальный проект"
subtitle: "Третий этап"
author: "Иван Алексеевич Волгин"

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

Сделать записи о персональном проекте два поста.

# Задание

1. Сделать записи для персональных проектов.
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору.
        - Языки научного программирования.

# Выполнение лабораторной работы

1. Сначала я записи о персональном проекте (рис. @fig:001) (рис. @fig:002).

![Код](image/1.png){#fig:001 width=70%}

![Как это выглядит на сайте](image/2.png){#fig:002 width=70%}

2. Далее я написал некоторую информацию о моем проекте (рис. @fig:003) (рис. @fig:004)

![Код](image/3.png){#fig:003 width=70%}

![Как это выглядит на сайте](image/4.png){#fig:004 width=70%}

3. После этого сделал пост по прошедшей неделе (рис. @fig:005) (рис. @fig:006)

![Код](image/5.png){#fig:005 width=70%}

![Как это выглядит на сайте](image/6.png){#fig:006 width=70%}

4. Затем пост про научные языки программирования (рис. @fig:007) (рис. @fig:086)

![Код](image/7.png){#fig:007 width=70%}

![Как это выглядит на сайте](image/8.png){#fig:008 width=70%}

# Выводы

В ходе выполнения этого этапа индивидуального проекта я добавил на сайт записи о проекте и сделал два поста.


