---
## Front matter
title: "Отчёт по лабораторной работе №3"
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

- Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Выполнение лабораторной работы

1. Открываем шаблон работы в Markdown для последующего редактированя (рис. [-@fig:001])

![Первоначальный вид файла](image/1-1.png){ #fig:001 width=70% }

1. Непосредственно редакируем шаблом под тему второй лабороторной работы (рис. [-@fig:002])

![Файл после редактирования](image/1-2.png){ #fig:002 width=70% }

1. Прописываем команду make в консоли и ждём компиляции файла (рис. [-@fig:003])

![Созданные файлы](image/1-3.png){ #fig:003 width=70% }


# Выводы

В ходе выполнения данной лабораторной работы я научился оформлять отчёты с помощью легковесного языка разметки Markdown.
