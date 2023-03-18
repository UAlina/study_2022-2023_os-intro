---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Этап №2"
author: "Уткина Алина Дмитриевна"

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

Целью данной работы является дополнение сайта данными о себе.

# Выполнение работы

Разместим фотографию владельца сайта, заменив шаблонную фотографию в каталоге ~/work/blog/content/autors/admin (рис. @fig:001).

![Добавление фотографии владельца сайта](image/1.jpg){#fig:001 width=70%}

Разместим краткое описание владельца сайта (рис. @fig:002). В том же файле добавим информацию об интересах (Interests), образовании (Education).

![Изменение краткого описания](image/2.jpg){#fig:002 width=70%}

Добавим пост по прошедшей неделе и на тему "Управление версиями. Git". Для этово отредактируем шаблонные папки и файл _index.md (рис. @fig:003).

![Работа с постами](image/3.jpg){#fig:003 width=70%}

# Выводы

В ходе работы была добавлена дополнительная информация о владельце сайта и добавлены новые посты.


