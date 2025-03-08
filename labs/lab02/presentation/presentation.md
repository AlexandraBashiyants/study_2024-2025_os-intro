---
## Front matter
lang: ru-RU
title: Лабораторная работа №2
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

Цель данной работы --- изучиение идеологий и применение средств контроля версий, освоение умений по работе с git.

* Делать базовую настройку git;

* Работать с ключами;

* Настраивать и работать с github.

# Выполнение лабораторной работы

## Установка программного обеспечения

![Установка git](image/1_git.png){#fig:001 width=70%}

## Базовая настройка git

Сделаем базовые настройки git.

![Настройка git](image/2_config.png){#fig:002 width=70%}

## Ключи ssh

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

Создадим ключ по алгоритму rsa с размером 4096 бит.

![Ключ ssh 4096](image/3_ssh.png){#fig:003 width=100%}

:::
::: {.column width="50%"}

Создадим ключ по алгоритму ed25519.

![Ключ ssh ed25519](image/4_ssh_ed.png){#fig:004 width=100%}

:::
::::::::::::::

## Ключи pgp

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![Ключ pgp](image/5_gpg.png){#fig:005 width=100%}

:::
::: {.column width="50%"}

![Ключ pgp](image/6_gpg.png){#fig:006 width=100%}

:::
::::::::::::::

## Добавление PGP ключа в GitHub

Выведем список ключей и скопируем отпечаток приватного ключа.

![Список ключей](image/8_0_list.png){#fig:007 width=70%}

## Настройка автоматических подписей коммитов git

Используя введёный email, укажем Git применять его при подписи коммитов.

![Подпись коммитов](image/8_config.png){#fig:019 width=70%}


## Настройка gh

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![Авторизация](image/9_gh.png){#fig:009 width=100%}

:::
::: {.column width="50%"}

![Авторизация](image/10_login.png){#fig:010 width=100%}

:::
::::::::::::::


## Шаблон для рабочего пространства

Перейдем в необходимый каталог и сколируем каталог.

![git clone](image/11_clone.png){#fig:011 width=70%}

## Шаблон для рабочего пространства

Настроим каталог. Удалим лишние файлы, создадим необходимые файлы и закоммитим на сервер.d

![Работа с файлами](image/12_make.png){#fig:012 width=70%}

# Выводы

- В этой лабораторной работе мы изучили работу системы контроля версий и git. 
