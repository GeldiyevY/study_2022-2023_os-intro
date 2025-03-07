---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
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
  * студент кафедры прикладной информатики
  * Российский университет дружбы народов
  * [1032249184@pfur.ru](mailto:1032249184@pfur.ru)

:::
::::::::::::::

# Вводная часть

## Цель работы

Получение навыков правильной работы с репозиториями git.

## Задание

Выполнить работу для тестового репозитория.
Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

# Выполнение лабораторной работы

## Установка git-flow

![dnf corp enable](image/dnf_enable.png){#fig:001}

##

![install gitflow](image/install_gitflow.png){#fig:002}

## Установка Node.js

![install notejs](image/install_notejs.png){#fig:003}

##

![install pnpm](image/install_pnpm.png){#fig:004}

## Настройка Node.js

![pnpm setup](image/pnpm_source.png){#fig:005}

## Общепринятые коммиты

![*pnpm add -g commitizen*](image/pnpm_add.png){#fig:006}

## Создание репозитория git

![Делаем первый коммит и выкладываем на github](image/create_git.png){#fig:007}

##

![Конфигурация общепринятых коммитов](image/pnpm_init.png){#fig:008}

##

![Сконфигурим формат коммитов](image/package.json.png){#fig:009}

##

![Добавим новые файлы, Выполним коммит и Отправим на github](image/git_add_cz_push.png){#fig:010}

##

![Конфигурация git-flow](image/git_flow_init.png){#fig:011}

##

![Загрузите весь репозиторий в хранилище](image/git_push_all.png){#fig:012}

##

![Зальём релизную ветку в основную ветку](image/git_flow_finish.png){#fig:013}

##

![Отправим данные на github](image/git_push.png){#fig:014}

##

![Создадим релиз на github](image/git_create_release.png){#fig:015}

## Работа с репозиторием git и Создание релиза git-flow

![Разработка новой функциональности и Создадим релиз с версией 1.2.3](image/flow_feature_branch.png){#fig:016}

##

![Обновите номер версии в файле package.json](image/change_version_package_json.png){#fig:017}

##

![Создадим журнал изменений  и Добавим журнал изменений в индекс](image/git_flow_release_1.2.3.png){#fig:018}

##

![Отправим данные на github и Создадим релиз на github с комментарием из журнала изменений](image/git_release_create_v1.2.3.png){#fig:019}

# Выводы

## Выводы

В этой Лабораорной работе я получил навыки правильной работы с репозиториями git.
