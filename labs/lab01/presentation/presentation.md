---
## Front matter
lang: ru-RU
title: Лабораторная Работа №1
subtitle: Подготовил
author:
  - Гелдиев Ыхлас
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 26 мая 2006

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

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="100%"}

  * Гелдиев Ыхлас
  * студент
  * стдент кафедры прикладной информатики
  * Российский университет дружбы народов
  * [1032249184@pfur.ru](mailto:1032249184@pfur.ru)
  * <https://GeldiyevY.github.io/ru/>

:::
::::::::::::::

# Вводная часть

## Цель работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

## Задание

Установить Fedora Sway на VirtualBox. А так-же настроить его для дальнейшей работы

# Выполнение лабораторной работы

## Создание необходимых каталогов.

![mkdir](image/cd_mkdir.png){#fig:001}

## Обновления

![*sudo dnf -y group install development-tools*](image/install_dev_tools.png){#fig:003}

##

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

##

![*sudo -i*](image/sudo-i.png){#fig:010}

##

![00keyboard](image/00keyboard.png){#fig:011}

## Установка программного обеспечения для создания документации

![install pandoc](image/install_pandoc.png){#fig:012}

##

![install texlive](image/install_texlife.png){#fig:013}

# Домашнее задание

![dmesg](image/dmesgless.png){#fig:014}

##

![Linux version](image/linux_version.png){#fig:015}

##

![processor Mzh](image/mzh_prc.png){#fig:016}

##

![processor model](image/proccessor_model.png){#fig:017}

## 

![hypervisor detected](image/hypervizor.png){#fig:018}

##

![file system mantling](image/filesystem_mantling.png){#fig:019}

## Выводы

Я приобрел практические навыки установки операционной системы на виртуальную машину.

