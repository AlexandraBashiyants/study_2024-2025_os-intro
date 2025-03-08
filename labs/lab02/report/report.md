---
## Front matter
title: "Лабораторная работа №2"
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

Цель данной работы --- изучиение идеологий и применение средств контроля версий, освоение умений по работе с git.

# Задание

В этой лабораторной работе необходимо изучить работу виртуальной машины и ее настройки.

Необходимо научиться:

* Делать базовую настройку git;

* Работать с ключами;

* Настраивать и работать с github.


# Выполнение лабораторной работы

## Установка программного обеспечения

Установим git и gh (рис. [-@fig:001]).

![Установка git](image/1_git.png){#fig:001 width=70%}

## Базовая настройка git

Сделаем базовые настройки git (рис. [-@fig:002]).

![Настройка git](image/2_config.png){#fig:002 width=70%}

## Ключи ssh

Создадим ключ по алгоритму rsa с размером 4096 бит (рис. [-@fig:003]).

![Ключ ssh 4096](image/3_ssh.png){#fig:003 width=70%}

Создадим ключ по алгоритму ed25519 (рис. [-@fig:004]).

![Ключ ssh ed25519](image/4_ssh_ed.png){#fig:004 width=70%}

## Ключи pgp

Сгенерируем ключ (рис. [-@fig:005]-[-@fig:006]).

![Ключ pgp](image/5_gpg.png){#fig:005 width=70%}

![Ключ pgp](image/6_gpg.png){#fig:006 width=70%}

## Добавление PGP ключа в GitHub

Выведем список ключей и скопируем отпечаток приватного ключа (рис. [-@fig:007]).

![Список ключей](image/8_0_list.png){#fig:007 width=70%}

Cкопируем наш сгенерированный PGP ключ в буфер обмена (рис. [-@fig:008]).

![Копирование ключа](image/7_gpg_armor.png){#fig:008 width=70%}

## Настройка автоматических подписей коммитов git

Используя введёный email, укажем Git применять его при подписи коммитов (рис. [-@fig:019]).

![Подпись коммитов](image/8_config.png){#fig:019 width=70%}

## Настройка gh

Авторизируемся (рис. [-@fig:009]-[-@fig:010]).

![Авторизация](image/9_gh.png){#fig:009 width=70%}

![Авторизация](image/10_login.png){#fig:010 width=70%}

## Шаблон для рабочего пространства

Перейдем в необходимый каталог и сколируем каталог (рис. [-@fig:011]).

![git clone](image/11_clone.png){#fig:011 width=70%}

Настроим каталог. Удалим лишние файлы, создадим необходимые файлы (рис. [-@fig:012]) и закоммитим на сервер (рис. [-@fig:013])


![Работа с файлами](image/12_make.png){#fig:012 width=70%}

![git push](image/13_puch.png){#fig:013 width=70%}


# Выводы

В этой лабораторной работе мы изучили работу системы контроля версий и git. 


