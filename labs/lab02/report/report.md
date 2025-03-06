---
## Front matter
title: "Лабораторная работа №2"
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

Изучить идеологию и применение средств контроля версий и освоить умения по работе с git.

# Задание

- Создать базовую конфигурацию для работы с git.
- Создать ключ SSH.
- Создать ключ PGP.
- Настроить подписи git.
- Зарегистрироваться на Github.
- Создать локальный каталог для выполнения заданий по предмету.

# Выполнение лабораторной работы

Установим git (рис. [-@fig:001]).

![*dnf install git*](image/install_git.png){#fig:001}

Установка gh (рис. [-@fig:002]).

![*dnf install gh*](image/install_gh.png){#fig:002}

Установка gh (рис. [-@fig:003]).

![*dnf install gh*](image/install_gh.png){#fig:003}

## Базовая настройка git

![*git config*](image/git_config.png){#fig:004}

## Создайте ключи ssh

![*ssh-keygen*](image/ssh-keygen.png){#fig:005}

## Создайте ключи pgp

![*gpg*](image/gpg.png){#fig:006}

## Настройка автоматических подписей коммитов git и Настройка gh

![*git config* and *gh auth*](image/git_config2_gh_auth.png){#fig:007}

## Сознание репозитория курса на основе шаблона

![*mkdir*](image/mkdir_op_sys.png){#fig:008}

![*gh create*](image/gh_create_clone.png){#fig:009}

## Настройка каталога курса

![*rm package.json*](image/rm_package.png){#fig:010}

![*make prepare*](image/echo_make.png){#fig:011}

![*git push*](image/git_push.png){#fig:012}

# Выводы

В этой лабораторной работе я научился пользоваться git. А так-же настроил каталог курса.

