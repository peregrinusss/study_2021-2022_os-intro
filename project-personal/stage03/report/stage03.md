---
## Front matter
title: "Индивидуальный проект 3 этап"
subtitle: "Добававление к сайту достижений"
author: "Перевощиков Данил Алексеевич"

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

- Добавить информацию о навыках (Skills).
- Добавить информацию об опыте (Experience).
- Добавить информацию о достижениях (Accomplishments).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему "Язык разметки Markdown".

# Ход работы

**1.** Добавили информацию о навыках (Skills).(рис. [-@fig:001;-@fig:002])

![Код информации о навыках.](image/01.png){ #fig:001 width=70% }

![Информация о навыках на сайте.](image/02.png){ #fig:002 width=70% }

**2.** Добавили информацию об опыте (Experience).(рис. [-@fig:003;-@fig:004])

![Код информации об опыте.](image/03.png){ #fig:003 width=70% }

![Информация об опыте на сайте.](image/04.png){ #fig:004 width=70% }

**3.** Добавили информацию о достижениях (Accomplishments).(рис. [-@fig:005;-@fig:006])

![Код информации о достижениях.](image/05.png){ #fig:005 width=70% }

![Информация о достижениях на сайте.](image/06.png){ #fig:006 width=70% }

**4.** Сделали пост по прошедшей неделе.(рис. [-@fig:007;-@fig:008])

![Код поста по прошедшей неделе.](image/07.png){ #fig:007 width=70% }

Затем вставили туда текст.

![Пост по прошедшей неделе на сайте.](image/08.png){ #fig:008 width=70% }

**5.** Добавили пост на тему "Язык разметки Markdown".(рис. [-@fig:009;-@fig:010;-@fig:011])

![Код поста о Markdown.](image/09.png){ #fig:009 width=70% }

![Продолжение кода поста о Markdown.](image/10.png){ #fig:010 width=70% }

![Пост Markdown на сайте.](image/11.png){ #fig:011 width=70% }