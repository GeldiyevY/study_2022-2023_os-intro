---
## Front matter
title: "Лабораторная работа №5"
subtitle: "Подготовил:"
author: "Гелдиев Ыхлас. НПИбд-03-24."

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

Настройка рабочей среды.

# Задание

Настроить рабочую среду.

# Выполнение лабораторной работы

## Установка Менеджер паролей pass

![`dnf install pass`](image/dnf_install_pass.png)

![Инициализируем хранилище](image/pass_init.png)

## Настройка

![list gpg keys](image/gpg_list_keys.png)

![Синхранизация с git](image/pass_git_init.png)

## Настройка интерфейса с броузером

![`dnf install browserpass`](image/dnf_install_browserpass.png)

## Управление файлами конфигурации

![`dnf install`](image/dnf-install_alot.png)

![установка шрифтов](image/install_font-1.png)

![установка шрифтов 2](image/install_font-2.png)

## Подключение репозитория к своей системе

![Подключение репозитория к своей системе 1](image/connect_repo_to_the_sys-1.png)

![Подключение репозитория к своей системе 1](image/connect_repo_to_the_sys-2.png)

# Выводы

Мы смогли настроить нашу систему для дальнейшей работы.

