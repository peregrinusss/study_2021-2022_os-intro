---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Markdown"
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

Научиться оформлять отчеты с помощью легковесного языка разметки Markdown.

# Ход работы

**1.**
Установка шаблона и редактирование титульного листа.(рис. [-@fig:001])

![Шаблон отчета рабораторной работы.](screens/01.png){ #fig:001 width=70% }


**2.**
Экспорт всех скриншотов из отчета лабораторной работы №2, сделанного с помощью MS Word.(рис. [-@fig:002;-@fig:003])

![Отчет лабораторной работы №2.](screens/02.png){ #fig:002 width=70% }

![Скачивание скриншотов.](screens/03.png){ #fig:003 width=70% }


**3.**
Перенос всех данных из отчета word в отчет markdown.(рис. [-@fig:004;-@fig:005;-@fig:006])

![Перенос данных.](screens/04.png){ #fig:004 width=70% }

![Продолжение переноса данных.](screens/05.png){ #fig:005 width=70% }

![Завершение переноса данных.](screens/06.png){ #fig:006 width=70% }


**4.**
Загрузка отчета на GitHub.(рис. [-@fig:007;-@fig:008;-@fig:009])

![Коммит изменений.](screens/07.png){ #fig:007 width=70% }

![Push данных на GitHub.](screens/08.png){ #fig:008 width=70% }

![Отчет на Github.](screens/09.png){ #fig:009 width=70% }


# Вывод

Мы научились оформлять отчеты с помощью легковесного языка разметки Markdown.