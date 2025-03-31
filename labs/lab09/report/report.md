---
## Front matter
title: "Лабораторная работа №9"
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

Цель данной работы --- приобретение практических навыков по просмотру каталогов и файлов; манипуляций
с ними.

# Задание

В этой лабораторной работе необходимо изучить работу командной оболочки Midnight Commander.

Необходимо научиться:

* Просматривать каталоги;

* Просматривать и редактировать файлы;

* Взаимодействовать с файлами и каталогами.

# Выполнение лабораторной работы

Изучим команду mc (рис. [-@fig:001]-[-@fig:002]).

![man mc](image/1.png){#fig:001 width=70%}

![man mc](image/2.png){#fig:002 width=70%}

Откроем mc (рис. [-@fig:003]).

![mc](image/3.png){#fig:003 width=70%}


Изучим возможности подменю Файл (рис. [-@fig:004]).

![Файл](image/4.png){#fig:004 width=70%}

Изучим возможности подменю Команда (рис. [-@fig:005]).

![Команда](image/5.png){#fig:005 width=70%}

Изучим возможности подменю Настройки (рис. [-@fig:006]).

![Настройки](image/6.png){#fig:006 width=70%}

Создадим файл text.txt (рис. [-@fig:007]).

![text.txt](image/7.png){#fig:007 width=70%}

Откроем в mc файл нажав F4 (рис. [-@fig:008]).

![text.txt](image/8.png){#fig:008 width=70%}

Удалим строку с помощью ctrl+K (рис. [-@fig:009]).

![Удаление строки](image/9.png){#fig:009 width=70%}

Скопируем строку на новую с помощью F5 (рис. [-@fig:010]).

![Копия строки](image/10.png){#fig:010 width=70%}

Перенесем строку с помощью F6 (рис. [-@fig:011]).

![Перенос строки](image/11.png){#fig:011 width=70%}

Сохраним файл (рис. [-@fig:012]).

![Сохранение](image/12.png){#fig:012 width=70%}

Перейдем в конец файла (ctrl+end), добавим текста. Перейдем в начало файла (ctrl+home), добавим текста (рис. [-@fig:013]).

![Переход в начало и конец](image/13.png){#fig:013 width=70%}

# Выводы

В этой лабораторной работе мы изучили работу Midnight Commander.

