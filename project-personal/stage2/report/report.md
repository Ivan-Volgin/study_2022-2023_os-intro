---
## Front matter
title: "Индивидуальный проект"
subtitle: "Второй этап"
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

Добавить к сайту данные о себе.

# Задание

- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору:
    - Управление версиями. Git.
    - Непрерывная интеграция и непрерывное развертывание (CI/CD).




# Выполнение лабораторной работы

1. Сперва я добавил нужную информацию о себе (рис. @fig:001) (рис. @fig:002).

![](image/1.png){#fig:001 width=70%}

![](image/2.png){#fig:002 width=70%}

2. Далее нужно было создать пост про прошлую неделю (рис. @fig:003) (рис. @fig:004)

![](image/3.png){#fig:003 width=70%}

![](image/3.3.png){#fig:004 width=70%}

3. Затем нужно было создать еще один пост. Тема на выбор. Я сделал про контроль версий гит. (рис. @fig:005) (рис. @fig:006)

![](image/4.png){#fig:005 width=70%}

![](image/4.4.png){#fig:006 width=70%}

# Выводы

В ходе выполнения второго этапа индивидуального проекта я научился добавлять на сайт информацию о владельце (обо мне) и создавать посты на различные темы.

::: {#refs}
:::
