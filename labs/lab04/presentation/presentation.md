---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: Операционные системы
author:
  - Башиянц А. К.
institute:
  - Российский университет дружбы народов, Москва, Россия

date: 05 марта 2025

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

Цель данной работы --- приобрести практические навыки правильной работы с репозиториями git.

* Работать с git flow;

* Создавать ветки;

* Работать с журналом изменений;

* Создавать релизы.


# Выполнение лабораторной работы

## Установка copr

![Установка copr](image/1_corp.png){#fig:001 width=70%}

## Установка gitflow

![Установка gitflow](image/2_gf.png){#fig:002 width=70%}

## Установка Node.js

![Установка Node.js](image/3_node.png){#fig:003 width=70%}

## Общепринятые коммиты

Выполним команду для помощи в форматировании коммитов.

![commitizen](image/6_pnpm.png){#fig:006 width=70%}

## Общепринятые коммиты

Выполним команду для помощи в создании логов.

![standard-changelog](image/7_chlog.png){#fig:007 width=70%}

## Создание репозитория git

![Создание репозитория](image/8_repo.png){#fig:008 width=70%}

## Работа с репозиторием

![Работа с репозиторием](image/9_repo.png){#fig:009 width=70%}

## package.json

![package.json](image/10_pack.png){#fig:010 width=70%}

## git cz

![git cz](image/11_cz.png){#fig:a111 width=70%}

## Инициализация git-flow

![Инициализация git-flow](image/12_init.png){#fig:012 width=70%}

## git branch

Проверим, что Вы на ветке develop и загрузим весь репозиторий в хранилище.

![git branch](image/13_branch.png){#fig:013 width=70%}

## Релиз 1.0.0

Установим внешнюю ветку как вышестоящую для этой ветки и Создадим релиз с версией 1.0.0.

![Релиз 1.0.0](image/14_start1.png){#fig:014 width=70%}

## Журнал изменений

Создадим журнал изменений, Добавим журнал изменений в индекс, Зальём релизную ветку в основную ветку

![Настройка релиза](image/15_set.png){#fig:015 width=70%}

## git push --all

Отправим данные на github.

![git push --all](image/16_all.png){#fig:016 width=70%}

## Создание релиза

Создадим релиз на github. Для этого будем использовать утилиты работы с github.

![Создание релиза](image/17_release.png){#fig:017 width=70%}

# Выводы

- В этой лабораторной работе мы изучили работу git.
