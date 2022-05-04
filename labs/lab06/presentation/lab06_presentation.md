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


**Лабораторная работа №6**

**Поиск файлов. Перенаправление ввода-вывода. Просмотр запущенных процессов**

Перевощиков Данил Алексеевич

---

## Цель работы:

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

---

## Основные этапы выполнения работы

**1.** Осуществили вход в систему, используя соответствующее имя пользователя.

**2** Записали в файл file.txt названия файлов, содержащихся в каталоге /etc. И дописали в этот же файл названия файлов, содержащихся в домашнем каталоге.

**3.** Записали имена всех файлов из file.txt, имеющих расширение .conf в новый текстовой файл conf.txt.

**4.** Определили, какие файлы в домашнем каталоге имеют имена, начинающиеся с символа c.

---

## Основные этапы выполнения работы

**5.** Вывели на экран мена файлов из каталога /etc, начинающиеся с символа h.

**6.** Запустили в фоновом режиме процесс, который записывает в файл ~/logfile файлы, имена которых начинаются с log.

**7.** Запустили из консоли в фоновом режиме редактор gedit.

**8.** Определили идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep.

---

## Основные этапы выполнения работы

**9.** . Прочитали справку (man) команды kill, после чего использовали её для завершения процесса gedit.

**10.** Выполнили команды df и du.

**11.** Воспользовавшись справкой команды find, вывели имена всех директорий, имеющихся в домашнем каталоге.

**12.** Ответили на контрольные вопросы.

---

## Вывод:

Мы ознакомились с инструментами поиска файлов и фильтрации текстовых данных. Приобрели практические навыки: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.