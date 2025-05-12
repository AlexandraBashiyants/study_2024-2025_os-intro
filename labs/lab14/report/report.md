---
## Front matter
title: "Лабораторная работа №14"
subtitle: "Операционные системы"
author: "Башиянц Александра Кареновна"
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
lot: false # List of tables
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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Цель данной работы --- изучить основы программирования в оболочке ОС UNIX. Научиться писать более
сложные командные файлы с использованием логических управляющих конструкций и циклов.


# Задание

В этой лабораторной работе необходимо изучить работу bash-скриптов.

Необходимо научиться:

* Использовать сложные логические управляющие конструкции

* Использовать циклы

# Выполнение лабораторной работы

Создадим файлы ex1.sh-ex4.sh для выполнения работы (рис. [-@fig:001]).

![файлы sh](image/1.png){#fig:001 width=70%}

Напишем скрипт для задания 1 (рис. [-@fig:002]).

![ex1.sh](image/2.png){#fig:002 width=70%}

Выполним файл ex1.sh и проверим корректность выполнения (рис. [-@fig:003]).

![bash ex1.sh](image/3.png){#fig:003 width=70%}

Напишем скрипт для задания 2 (рис. [-@fig:006]).

![ex2.sh](image/6.png){#fig:006 width=70%}

Выполним файл ex2.sh и проверим корректность выполнения (рис. [-@fig:007]).

![bash ex2.sh](image/7.png){#fig:007 width=70%}

Напишем скрипт для задания 3 (рис. [-@fig:008]).

![ex3.sh](image/8.png){#fig:008 width=70%}

Выполним файл ex3.sh и проверим корректность выполнения (рис. [-@fig:009]).

![bash ex3.sh](image/9.png){#fig:009 width=70%}



# Выводы

В этой лабораторной работе мы изучили углубленную работу bash-скриптов.
