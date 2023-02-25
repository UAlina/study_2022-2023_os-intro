---
## Front matter
title: "Отчёт по лабораторной работе №3"
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

Целью данной работы является приобретение навыков оформления отчётов с помощью легковесного языка разметки Markdown.

# Задание

Сделать отчёт по лабораторной работе №2 в формате Markdown.

# Выполнение лабораторной работы

## Создание заголовков

Чтобы создать заголовок, используется знак "#" или несколько таких знаков, в зависимости от уровня заголовка. Так для основного пункта мы используем один знак, а для его подпункта - два знака (рис. @fig:001), (рис. @fig:002).

![Создание заголовка в формате markdown](image/1.jpg){#fig:001 width=70%}

![Результат создания заголовка в формате pdf](image/2.jpg){#fig:002 width=70%}

## Создание неупорядоченных и упорядоченных списков

Для создания неупорядоченного списка можно использовать зведочки или тире, для упорядоченного - соответствующие цифры (рис. @fig:003), (рис. @fig:004). Для многоуровневых списков можно использовать отступы. 

![Создание списков в формате markdown](image/3.jpg){#fig:003 width=70%}

![Результат создания списков в формате pdf](image/4.jpg){#fig:004 width=70%}

## Создание изображения 

Чтобы вставить изображение в документ можно с помощью непосредственного указания адреса изображения (рис. @fig:005), (рис. @fig:006). В квадратных скобках указывается подпись к изображению; в круглых скобках указывается URL-адрес или относительный путь изображения, в фигурных скобках указывается идентификатор изображения (#fig:fig1) для ссылки на него по тексту и размер изображения относительно ширины страницы (width=70%).

![Создание изображений в формате markdown](image/5.jpg){#fig:005 width=70%}

![Результат создания изображений в формате pdf](image/6.jpg){#fig:006 width=70%}

## Окончание работы, создание дополнительных форматов отчета 

После заполнения шаблона сохраняем файл и переходим в терминал. При использовании команды make создаются два дополнительных формата с расширениями .docx и .pdf (рис. @fig:007). Для удаления лишних файлов, созданных по шаблону, используется "make clean" (рис. @fig:008).

![Создание дополнительных форматов отчета](image/7.jpg){#fig:007 width=70%}

![Удаление дополнительных форматов отчета](image/8.jpg){#fig:008 width=70%}

# Выводы

В ходе данной лабораторной работы были приобретены навыки оформления отчётов с помощью легковесного языка разметки Markdown. 

