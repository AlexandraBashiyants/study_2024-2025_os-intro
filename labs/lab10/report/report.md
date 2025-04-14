---
## Front matter
title: "Лабораторная работа №10"
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

Цель данной работы --- приобретение практических навыков работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Задание

В этой лабораторной работе необходимо изучить работу редактора vi.

Необходимо научиться:

* Перемещаться по файлу;

* Вставлять текст;

* Удалять и отменять;

* Сохранение и изменение файла.

# Выполнение лабораторной работы

## Задание 1. Создание нового файла с использованием vi

Вызовим vi и создадим файл hello.sh (рис. [-@fig:001]).

![vi hello.sh](image/1.png){#fig:001 width=70%}

Нажмем клавишу i и введем код (рис. [-@fig:002]).

![i](image/2.png){#fig:002 width=70%}


Сохраним и выйдем из файла (рис. [-@fig:004]).

![:qw](image/4.png){#fig:004 width=70%}

Сделаем файл исполняемым (рис. [-@fig:005]).

![chmod](image/5.png){#fig:005 width=70%}

## Задание 2. Редактирование существующего файла

Перейдем к слову HELL и изменим на HELLO (рис. [-@fig:007]).

![HELLO](image/7.png){#fig:007 width=70%}

Заменим LOCAL на local и добим новую строку (рис. [-@fig:009]).

![local и echo](image/9.png){#fig:009 width=70%}

Удалим последнюю строку (рис. [-@fig:010]).

![Удаление](image/10.png){#fig:010 width=70%}

Отменим удаление (рис. [-@fig:011]).

![Отмена](image/11.png){#fig:011 width=70%}

Сохраним файл (рис. [-@fig:012]).

![Сохранение](image/12.png){#fig:012 width=70%}


# Выводы

В этой лабораторной работе мы изучили работу работу редактора vi.
