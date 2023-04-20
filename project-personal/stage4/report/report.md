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

Зарегистрироваться на некоторых источниках и добавить на сайт ссылки на них.

# Задание

Добавить к сайту ссылки на научные и библиометрические ресурсы.

    Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
        eLibrary : https://elibrary.ru/;
        Google Scholar : https://scholar.google.com/;
        ORCID : https://orcid.org/;
        Mendeley : https://www.mendeley.com/;
        ResearchGate : https://www.researchgate.net/;
        Academia.edu : https://www.academia.edu/;
        arXiv : https://arxiv.org/;
        github : https://github.com/.
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору:
        Оформление отчёта.
        Создание презентаций.
        Работа с библиографией.

# Выполнение лабораторной работы

Сначала я зарегистрировался на нужных источниках и добавил на сайт ссылки на них (рис. @fig:001), сохранил изменения в файле и они отобразились на сайте (рис. @fig:002).

![Содержание файла](image/1.png){#fig:001 width=70%}

![Изменения на сайте](image/2.png){#fig:002 width=70%}

Затем нужно было создать пост о прошедшей неделе, я его написал (рис. @fig:003) и также сохранил изменения в файле, чтобы они отобразились на сайте (рис. @fig:004).

![Содержание файла](image/3.png){#fig:003 width=70%}

![Изменения на сайте](image/4.png){#fig:004 width=70%}

После этого нужно было написать пост о том, как создавать отчеты. Я, идентично предыдущему пункту, создал файл и написал в нем пост (рис. @fig:005), а затем сохранил его, чтобы отобразить изменения на сайте (рис. @fig:006)

![Содержание файла](image/5.png){#fig:005 width=70%}

![Изменения на сайте](image/6.png){#fig:006 width=70%}

# Выводы

В ходе выполнения этой лабораторной работы я научился добавлять на сайт ссылки на сторонние ресурсы, а так же создал два новых поста.

