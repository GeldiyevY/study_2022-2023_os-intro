---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Подготовил:"
author: "Гелдиев Ыхлас. НПИбд-03-24"

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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Задание

Установить Fedora Sway на VirtualBox. А так-же настроить его для дальнейшей работы

# Выполнение лабораторной работы

## Создание необходимых каталогов.

![mkdir](image/cd_mkdir.png){#fig:001}

## Обновления

![*sudo dnf -y group install development-tools*](image/install_dev_tools.png){#fig:003}

![*dnf update*](image/dnfupdate.png){#fig:004}

## Повышение комфорта работы

![*install tmux*](image/install_tmux.png){#fig:005}

## Автоматическое обновление

![dnf-automatic](image/dnf-automatic.png){#fig:006}

![enable dnf-automatic](image/enable_dnf-automatic.png){#fig:007}

## Отключение SELinux

![selinux permissive](image/disabling_selinux.png){#fig:008}

## Настройка раскладки клавиатуры

![config](image/create_conf_file.png){#fig:009}

![*sudo -i*](image/sudo-i.png){#fig:010}

![00keyboard](image/00keyboard.png){#fig:011}

## Установка программного обеспечения для создания документации

![install pandoc](image/install_pandoc.png){#fig:012}

![install texlive](image/install_texlife.png){#fig:013}

# Домашнее задание

![dmesg](image/dmesgless.png){#fig:014}

![Linux version](image/linux_version.png){#fig:015}

![processor Mzh](image/mzh_prc.png){#fig:016}

![processor model](image/proccessor_model.png){#fig:017}

![hypervisor detected](image/hypervizor.png){#fig:018}

![file system mantling](image/filesystem_mantling.png){#fig:019}

# Выводы

Я приобрел практические навыки установки операционной системы на виртуальную машину.

