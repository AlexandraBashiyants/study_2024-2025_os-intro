---
## Front matter
lang: ru-RU
title: Лабораторная работа №6
subtitle: Операционные системы
author:
  - Башиянц А. К.
institute:
  - Российский университет дружбы народов, Москва, Россия

date: 

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---



# Вводная часть

## Цели и задачи

Цель данной работы --- приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

* Работать с директориями через командную строку;

* Получать информацию о командах;

* Создавать и удалять директории.


# Выполнение лабораторной работы

## Домашний каталог

![](image/1.png){#fig:001 width=70%}

## ls

![ls](image/2.png){#fig:002 width=70%}

## ls -l

![ls -l](image/3.png){#fig:003 width=70%}

## ls -a

![ls -a](image/4.png){#fig:004 width=70%}

## /var/spool

Определим, есть ли в каталоге /var/spool подкаталог с именем cron.

![/var/spool](image/5.png){#fig:005 width=70%}

## Владелец

![](image/7.png){#fig:007 width=70%}

## Создание каталогов

![](image/8_new.png){#fig:008 width=70%}

## Создание каталогов одной командой

![](image/9_0.png){#fig:039 width=70%}

## Удаление каталогов одной командой

![](image/9_3.png){#fig:009 width=70%}

## Попытка удаления

![](image/10_rm.png){#fig:010 width=70%}

## man ls

![](image/11_ls.png){#fig:011 width=70%}

## ls -R

С помощью команды man определим, какую опцию команды ls нужно использовать для просмотра содержимое не только указанного каталога, но и подкаталогов, входящих в него. Для этого нужно дописать -R.

![](image/12_r.png){#fig:012 width=70%}

## ls -l --time=ctime

С помощью команды man определим набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов. Для этого нужно дописать --time=ctime.

![](image/13_sort.png){#fig:013 width=70%}


## man cd

![man cd](image/14_cd.png){#fig:014 width=70%}

## man pwd

![man pwd](image/15_pwd.png){#fig:015 width=70%}

## man mkdir

![man mkdir](image/16_mkdir.png){#fig:016 width=70%}

## man rm

![man rm](image/17_rm.png){#fig:017 width=70%}

## man ls

![man ls](image/18_rm.png){#fig:018 width=70%}





# Выводы

- В этой лабораторной работе мы изучили взаимодействие пользователя с системой посредством командной строки.
