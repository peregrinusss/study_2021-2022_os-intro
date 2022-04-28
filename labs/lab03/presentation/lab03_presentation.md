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

**Лабораторная работа №3**

**Markdown**

Перевощиков Данил Алексеевич

---

## Цель работы:

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

## Задачи:

1. Сохранить все изображения из отчета в фомрате docs.
2. Изучить язык разметки markdown.
3. Переделать отчет в формате markdown.

---

## Что такое Markdown?

Эот облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.

---

## Базовые сведения о Markdown

Чтобы создать заголовок, используйте знак ( # ), например:

```
 # This is heading 1
 ## This is heading 2
 ### This is heading 3
 #### This is heading 4
```

Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:

``` This text is **bold** ```

Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:

``` This text is *italic* ```

Блоки цитирования создаются с помощью символа >:

---

## Основные этапы выполнения работы

**1.** Открыли отчет, сделанный в формате docs и экспортировали все изображения в папку, которая находится рядом с проектом.(рис. [-@fig:001])

---

## Основные этапы выполнения работы

![отчет word.](screens/02.png){ #fig:001 width=70% }

---

## Основные этапы выполнения работы

**2.** Используем шаблон отчета markdown и заполняем его в соответствии с отчетом в формате docs.(рис. [-@fig:002])

---

## Основные этапы выполнения работы

![редактирование шаблона.](screens/04.png){ #fig:002 width=70% }

---

## Основные этапы выполнения работы

**3.** Сохраняем документ и загружаем на Github.(рис. [-@fig:003])

---

## Основные этапы выполнения работы

![загрузка отчета на гитхаб.](screens/08.png){ #fig:003 width=70% }

---

## Вывод:

Мы научились оформлять отчёты с помощью легковесного языка разметки Markdown.