---
## Front matter
title: "Индивидуальный проект 5 этап"
subtitle: "Добавление к сайту всех остальных элементов."
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

- Сделать записи для персональных проектов.
- Сделать пост по прошедшей неделе.
- Добавить пост на тему "Языки научного программирования".

# Ход работы

**1.** Добавили проект на сайт: указали ссылки на проект на хостинге гитхаб и на сам репозиторий с проектом, добавили картинку preview и небольшое описание.(рис. [-@fig:001])

![Код проекта.](image/01.png){ #fig:001 width=80% }

В итоге это стало выглядеть так: (рис. [-@fig:002])

![Проект на сайте.](image/02.png){ #fig:002 width=80% }

**2.** Сделали пост по прошедшей неделе.(рис. [-@fig:003])

![Код поста по прошедшей неделе.](image/03.png){ #fig:003 width=80% }

В итоге это стало выглядеть так: (рис. [-@fig:004])

![Пост по прошедшей неделе на сайте.](image/04.png){ #fig:004 width=80% }

**3.** Добавили пост на тему "Языки научного программирования".(рис. [-@fig:005])

![Код поста о языках научного программирования.](image/05.png){ #fig:005 width=80% }

В итоге это стало выглядеть так: (рис. [-@fig:006])

![Пост "Языки научного программирования" на сайте.](image/06.png){ #fig:006 width=80% }