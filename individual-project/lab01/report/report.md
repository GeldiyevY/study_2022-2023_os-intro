---
## Front matter
title: "Индевидуальный проект. Этап №1"
subtitle: "Подготовил:"
author: "Гелдиев Ыхлас"

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

Размещение на Github pages заготовки для персонального сайта.

# Задание

- Установить необходимое программное обеспечение.
- Скачать шаблон темы сайта.
- Разместить его на хостинге git.
- Установить параметр для URLs сайта.
- Разместить заготовку сайта на Github pages.

# Выполнение первого этапа индивидуального проекта

## Установить необходимое программное обеспечение.

Для выполнения нам нужен будет gh. Нужно его скачать и авторизоваться (рис. [-@fig:001]).

![*gh auth*](image/gh-auth.png){#fig:001}

## Скачать шаблон темы сайта и Разместить его на хостинге git.

Мы можем использоапть шаблон темы сайта в качестве шаблона (tamplate) для нашего хостинга.

![*gh repo create*](image/gh_repo_create.png){#fig:002}

## Установить параметр для URLs сайта.

Если мы назовем наш репозиторий <username>.github.io то GitHub сам установит на него URL для доступа к этому сайти из интеренета

![*gh repo rename*](image/gh_repo_rename.png){#fig:003}

## Разместить заготовку сайта на Github pages.

![Зайдем на Githun pages](image/github_pages.png){#fig:004}

Как мы видим наш сайт уже получил url и мы можем по нему перейти.

![Наш сайт](image/site_visit.png){#fig:005}

# Выводы

Я научился размещать на Github pages заготовки для персонального сайта.

# Список литературы{.unnumbered}

::: {#refs}
:::
