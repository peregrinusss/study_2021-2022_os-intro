---
## Front matter
title: "Индивидуальный проект 2 этап"
subtitle: "Добавление к сайту данных о себе"
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

- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Добавить пост на тему "Управление версиями. Git."

# Ход работы

**1.** Запустили локальный сервер hugo в каталоге CV.(рис. [-@fig:001])

![Запуск локального сервера.](image/01.png){ #fig:001 width=70% }

**2.** Заполнение биографии

**2.1** Перенесли свой аватар в папку со страницей биографии, переименовали его и удалили старую картинку.(рис. [-@fig:002])

![Замена аватара.](image/02.png){ #fig:002 width=70% }

Сохраняем и проверяем.(рис. [-@fig:003])

![Наш сайт с обновленным аватаром.](image/03.png){ #fig:003 width=70% }

**2.2** Изменили имя и фамилию, краткую биографию, информацию о образваонии и интересах.(рис. [-@fig:004])

![Обновленная биография.](image/04.png){ #fig:004 width=70% }

**3.** Добавление поста о Git.

**3.1** Перенесли логотип Git в папку с постами, переименовали его и удалили старую картинку.(рис. [-@fig:005])

![Замена картинки поста.](image/05.png){ #fig:005 width=70% }

**3.2** Изменили название поста, краткую информацию, дату публикации, теги и категории.(рис. [-@fig:006])

![Оглавление поста о Git.](image/06.png){ #fig:006 width=70% }

**3.3** Заполнили контент поста.(рис. [-@fig:007])

![Контент поста о Git.](image/07.png){ #fig:007 width=70% }

В итоге наш пост стал выглядеть так (рис. [-@fig:008;-@fig:009]):

![Открытый пост о Git.](image/08.png){ #fig:008 width=70% }

![Краткий вид поста о Git.](image/09.png){ #fig:009 width=70% }