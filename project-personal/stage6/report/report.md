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

Сделать русскую и английскую локализацию.

# Задание

1. Сделать поддержку английского и русского языков.
2. Разместить элементы сайта на обоих языках.
3. Разместить контент на обоих языках.
4. Сделать пост по прошедшей неделе.

# Выполнение лабораторной работы

1. Сначала я создал две папки для двух локализаций ru и en (рис. @fig:001), а затем зашел в config в файл отвечающий за языки, добавил русский и указал для них пути(рис. @fig:002).

![Две директории](image/1.png){#fig:001 width=70%}

![Добавил два языка](image/2.png){#fig:002 width=70%}

2. Далее проверил, как все получилось на сайте (рис. @fig:003) и приступил к переписыванию всего контента на русский или английский язык, в разных местах по разному.

![Код](image/3.png){#fig:003 width=70%}

3. После этого я написал пост по прошедшей неделе на двух языках (рис. @fig:004) (рис. @fig:005).

![Код](image/4.png){#fig:004 width=70%}

![Как это выглядит на сайте](image/5.png){#fig:005 width=70%}

# Выводы

В ходе выполнения этого этапа индивидуального проекта я добавил на сайт русскую и английскую локализацию и сделал один поста.


