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

---

**Первый этап проекта**

**Размещение на Github pages заготовки для персонального сайта.**

Перевощиков Данил Алексеевич

---

## Цель работы:

Разместить заготовку сайта на Github pages.

---

## Основные этапы выполнения работы

**1.** Клонировали щаблон сайта на гитхаб и в локальную папку.

**2.** Запустили hugo server в локальной папке и удалили welcome page.

**3.** Создали репозиторий с названием адреса будущего сайта и локально клонировали его рядом с шаблоном.

**4.** Добавили ветку main будущему сайту и запушили на гитхаб.

**5.** Добавили submodule в папку public в папку с шаблоном. После чего в папке public появились основные файлы нашего сайта.

**6.** Запушили все новые файлы на гитхаб, подождали пока страница загрузится и перешли по адресу сайта.

---

## Основные этапы выполнения работы

Так выглядит наш готовый сайт:

![Готовый сайт.](screens/17.png){ #fig:001 width=70% }

---

## Результат

Мы разместили заготовку сайта на Github pages.