---
## Front matter
title: "Индивидуальный проект 6 этап"
subtitle: "Размещение двуязычного сайта на Github."
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

- Сделать поддержку английского и русского языков.
- Разместить элементы сайта на обоих языках.
- Разместить контент на обоих языках.
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору (на двух языках).

# Ход работы

**1.** Изменили файл languages.yaml, добавили ссылки на папки ru и en, перевели шапку сайта.(рис. [-@fig:001])

![Добавление ссылок на папки с русской и английской версий.](image/01.png){ #fig:001 width=80% }

**2.** Создали папки en и ru в директории content, заранее переведя всё содержимое файлов (посты, биографию, проекты и т.д.).(рис. [-@fig:002])

![Создание папок en и ru.](image/02.png){ #fig:002 width=80% }

**3.** Изменили параметр defaultContentLanguageInSubdir на true в файле config.yaml.(рис. [-@fig:003])

![Изменение параметра в файле config.yaml.](image/03.png){ #fig:003 width=80% }

В итоге у нас появилась русская версия сайта.(рис. [-@fig:004])

![Русская версия сайта.](image/04.png){ #fig:004 width=80% }


**4.** Добавили пост на тему "Строки в JavaScript" на двух языках.(рис. [-@fig:005;-@fig:006])

![Пост на английском "Строки в Javascript".](image/05.png){ #fig:005 width=80% }

![Пост на русском "Строки в Javascript".](image/06.png){ #fig:006 width=80% }

**5.** Сделали пост по прошедшей неделе на двух языках.(рис. [-@fig:007;-@fig:008])

![Пост по прошедшей неделе на английском.](image/07.png){ #fig:007 width=80% }

![Пост по прошедшей неделе на русском.](image/08.png){ #fig:008 width=80% }