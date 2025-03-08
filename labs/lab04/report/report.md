---
## Front matter
title: "Лабораторная работа №4"
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

Цель данной работы --- приобрести практические навыки правильной работы с репозиториями git.

# Задание

В этой лабораторной работе необходимо изучить правильную работу с репозиториями git.

Необходимо научиться:

* Работать с git flow;

* Создавать ветки;

* Работать с журналом изменений;

* Создавать релизы


# Выполнение лабораторной работы

## Установка git-flow

Установим copr  (рис. [-@fig:001]) и gitflow (рис. [-@fig:002]).

![Установка copr](image/1_corp.png){#fig:001 width=70%}

![Установка gitflow](image/2_gf.png){#fig:002 width=70%}

## Установка Node.js


Установим Node.js (рис. [-@fig:003]).

![Установка Node.js](image/3_node.png){#fig:003 width=70%}


Установим pnpm (рис. [-@fig:004]).

![Установка pnpm](image/4_pnpm.png){#fig:004 width=70%}

## Настройка Node.js

Для работы с Node.js добавим каталог с исполняемыми файлами, устанавливаемыми yarn, в переменную PATH (рис. [-@fig:005]).

![setup](image/5_setup.png){#fig:005 width=70%}


## Общепринятые коммиты

Выполним команду для помощи в форматировании коммитов (рис. [-@fig:006]).

![commitizen](image/6_pnpm.png){#fig:006 width=70%}

Выполним команду для помощи в создании логов (рис. [-@fig:007]).

![standard-changelog](image/7_chlog.png){#fig:007 width=70%}

## Создание репозитория git

Создадим репозиторий на GitHub  (рис. [-@fig:008]).

![Создание репозитория](image/8_repo.png){#fig:008 width=70%}

Настроим репозиторий и сделаем первый коммит (рис. [-@fig:009]).

![Работа с репозиторием](image/9_repo.png){#fig:009 width=70%}

Скорртектируем файл package.json (рис. [-@fig:010]).

![package.json](image/10_pack.png){#fig:010 width=70%}



Выполним коммит (рис. [-@fig:a111]).

![git cz](image/11_cz.png){#fig:a111 width=70%}

Инициализируем git-flow (рис. [-@fig:012]).

![Инициализация git-flow](image/12_init.png){#fig:012 width=70%}

Проверим, что Вы на ветке develop и загрузим весь репозиторий в хранилище(рис. [-@fig:013]).

![git branch](image/13_branch.png){#fig:013 width=70%}

Установим внешнюю ветку как вышестоящую для этой ветки и Создадим релиз с версией 1.0.0 (рис. [-@fig:014]).

![Релиз 1.0.0](image/14_start1.png){#fig:014 width=70%}

Создадим журнал изменений, Добавим журнал изменений в индекс, Зальём релизную ветку в основную ветку (рис. [-@fig:015]).

![Настройка релиза](image/15_set.png){#fig:015 width=70%}

Отправим данные на github (рис. [-@fig:016]).

![git push --all](image/16_all.png){#fig:016 width=70%}

Создадим релиз на github. Для этого будем использовать утилиты работы с github (рис. [-@fig:017]).

![Создание релиза](image/17_release.png){#fig:017 width=70%}



# Выводы

В этой лабораторной работе мы изучили работу git.

