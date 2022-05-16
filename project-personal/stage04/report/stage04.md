---
## Front matter
title: "Индивидуальный проект 4 этап"
subtitle: "Добавление к сайту ссылок на научные и библиометрические ресурсы."
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

Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
- vk : https://vk.com/.
- github : https://github.com/.
- Сделать пост по прошедшей неделе.
- Добавить пост на тему "Оформление отчёта".

# Ход работы

**1.** Добавили ссылки на вк и гитхаб, также оставили ссылку на contact.(рис. [-@fig:001])

![Код ссылок.](image/01.png){ #fig:001 width=70% }

В итоге это стало выглядеть так: (рис. [-@fig:002])

![Ссылки на сайте.](image/02.png){ #fig:002 width=70% }

**2.** Сделали пост по прошедшей неделе.(рис. [-@fig:003])

![Код поста по прошедшей неделе.](image/03.png){ #fig:003 width=70% }

В итоге это стало выглядеть так: (рис. [-@fig:004])

![Пост по прошедшей неделе на сайте.](image/04.png){ #fig:004 width=70% }

**3.** Добавили пост на тему "Оформление отчёта".(рис. [-@fig:005])

![Код поста об оформлении отчета.](image/05.png){ #fig:005 width=70% }

В итоге это стало выглядеть так: (рис. [-@fig:006])

![Пост Markdown на сайте.](image/06.png){ #fig:006 width=70% }