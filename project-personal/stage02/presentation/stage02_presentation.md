---
marp: true

## Front matter
lang: ru-RU
title: Structural approach to the deep learning method
author: |
	Leonid A. Sevastianov\inst{1,3}
	\and
	Anton L. Sevastianov\inst{1}
	\and
	Edik A. Ayrjan\inst{2}
	\and
	Anna V. Korolkova\inst{1}
	\and
	Dmitry S. Kulyabov\inst{1,2}
	\and
	Imrikh Pokorny\inst{4}
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
	\and
	\inst{2}LIT JINR, Dubna, Russian Federation
	\and
	\inst{3}BLTP JINR, Dubna, Russian Federation
	\and
	\inst{4}Technical University of Košice, Košice, Slovakia
date: NEC--2019, 30 September -- 4 October, 2019 Budva, Montenegro

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

figureTitle: "Рис."

---


**Индивидуальный проект 2 этап**

**Добавление к сайту данных о себе**

Перевощиков Данил Алексеевич

---

## Цель работы:

- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Добавить пост на тему "Управление версиями. Git."

---

## Основные этапы выполнения работы

**1.** Запустили локальный сервер hugo в каталоге CV.

**2** Перенесли свой аватар в папку со страницей биографии, переименовали его и удалили старую картинку.

**3** Изменили имя и фамилию, краткую биографию, информацию о образваонии и интересах.

---

## Основные этапы выполнения работы

В итоге наша биография стала выглядеть так (рис. [-@fig:001]):

![Заполненная биография.](image/10.png){ #fig:001 width=70% }

---

## Основные этапы выполнения работы

**4** Перенесли логотип Git в папку с постами, переименовали его и удалили старую картинку.

**5** Изменили название поста, краткую информацию, дату публикации, теги и категории.

**6** Заполнили контент поста.

---

## Основные этапы выполнения работы

В итоге наш пост стал выглядеть так (рис. [-@fig:002;-@fig:003]):

![Открытый пост о Git.](image/08.png){ #fig:002 width=70% }

---

![Краткий вид поста о Git.](image/09.png){ #fig:003 width=80% }