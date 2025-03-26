---
## Front matter
title: "Лабораторная работа №8"
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

Цель данной работы --- приобретение практических навыков поиска файлов и фильтрации текстовых данных.

# Задание

В этой лабораторной работе необходимо изучить работу поиска файлов и фильтрации текстовых данных.

Необходимо научиться:

* Управлять процессами;

* Проверять использование диска;

* Обслуживание файловых систем.

# Выполнение лабораторной работы


Запишем в файл file.txt названия файлов, содержащихся в каталоге /etc. Допишем в этот же файл названия файлов, содержащихся в нашем домашнем каталоге (рис. [-@fig:001]).

![file.txt](image/1.png){#fig:001 width=70%}

Выведем имена всех файлов из file.txt, имеющих расширение .conf, после чего запишем их в новый текстовой файл conf.txt (рис. [-@fig:002]).

![conf.txt](image/2.png){#fig:002 width=70%}

Определим, какие файлы в нашем домашнем каталоге имеют имена, начинавшиеся с символа c? Предложим несколько вариантов, как это сделать (рис. [-@fig:004]).

![Файлы с с](image/4.png){#fig:004 width=70%}

Выведем на экран (по странично) имена файлов из каталога /etc, начинающиеся с символа h (рис. [-@fig:005]-[-@fig:006]).

![Файлы с h](image/5.png){#fig:005 width=70%}

![Просмотр](image/6.png){#fig:006 width=70%}

Запустим в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log (рис. [-@fig:007]).

![logfile](image/7.png){#fig:007 width=70%}

Удалим файл ~/logfile (рис. [-@fig:008]).

![rm logfile](image/8.png){#fig:008 width=70%}

Запустим из консоли в фоновом режиме редактор gedit (рис. [-@fig:009]).

![gedit &](image/9.png){#fig:009 width=70%}

Определим идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep (рис. [-@fig:010]).

![Идентификатор процесса](image/10.png){#fig:010 width=70%}

Прочтем справку (man) команды kill, после чего используем её для завершения процесса gedit. (рис. [-@fig:011]-[-@fig:012]).

![man kill](image/11.png){#fig:011 width=70%}

![kill gedit](image/12.png){#fig:012 width=70%}

Выполним команды df и du, предварительно получив более подробную информацию об этих командах, с помощью команды man (рис. [-@fig:013]-[-@fig:016]).

![man df](image/13.png){#fig:013 width=70%}

![man du](image/14.png){#fig:014 width=70%}

![df](image/15.png){#fig:015 width=70%}

![du](image/16.png){#fig:016 width=70%}

Воспользовавшись справкой команды find, выведем имена всех директорий, имеющихся в нашем домашнем каталоге (рис. [-@fig:017]).

![find](image/17.png){#fig:017 width=70%}

# Выводы

В этой лабораторной работе мы изучили работу поиска файлов и фильтрации текстовых данных.

