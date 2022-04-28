---
## Front matter
title: "Отчёт по лабораторной работе №2"
subtitle: "Тема: работа в Markdown"
author: "Подволоцкий Иван Дмитриевич"

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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
#tableTitle: "Таблица"
#listingTitle: "Листинг"
#lofTitle: "Список иллюстраций"
#lotTitle: "Список таблиц"
#lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

- Изучить идеологию и применение средств контроля версий
- Освоить умения по работе с git

# Выполнение лабораторной работы

1. Создание учётной записи на Github (рис. [-@fig:001])

![Личная информация на Github](image/1.png){ #fig:001 width=70% }

1. Базовая настройка git (рис. [-@fig:002])

![Настройка](image/2.png){ #fig:002 width=70% }

1. Создание ключей ssh и pgp (рис. [-@fig:003])

![Создание ключей](image/3.png){ #fig:003 width=70% }

1. Создание репозитория курса на основе шаблона (рис. [-@fig:004])

![Создание и настройка репозитория](image/4.png){ #fig:004 width=70% }

1. Настройка каталога курса и отправка файлов на сервер (рис. [-@fig:005])

![Настройка каталога](image/5.png){ #fig:005 width=70% }

# Выводы

В ходе выполнения данной лабораторной работы я изучил идеологию и применение
средств контроля версий, а также освоил умения по работе с git.


::: {#refs}
