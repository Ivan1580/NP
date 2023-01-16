---
## Front matter
lang: ru-RU
title: Отчёт по лабораторной работе 1 + 2
author: 'Цуприков Иван Анатольевич'
date: 24 декабря, 2022

## Formatting
toc: false
slide_level: 2
theme: metropolis
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

## Цель работы

Изучение идеалогии и применение средств контроля версий. Освоение умения по работе с git.

## Задание

Лабораторная работа подразумевает регистрацию на github, соединение его с виртуальной машиной и изучение основ.

# Выполнение лабораторной работы

1. Задал базовые настройки git. Задал имя и email владельца репозитория, настроил utf-8 в выводе сообщений. Настроил верификацию и подписал коммиты git. Задал параметры autocrlf и safecrlf(рис.1).

   ![рис.1. Объем памяти.](images/1.png){ #fig:002 width=60% }

---

2. Создал ключи ssh по разным алгоритмам rsa(рис.2) и ed(рис.3). Также создал pgp ключ.

   ![рис.2. Ключи](images/2.png){ #fig:003 width=60% }
   ![рис.3. Ключи](images/3.png){ #fig:003 width=60% }

---

3. Добавил ключ PGP ключ в настройки в github (рис.4).

   ![рис.5. PGP ключ](images/4.png){ #fig:004 width=60% }

---

4. Настроил автоматические подписи коммитов и связал между собой виртуальную машину и github (рис.5).

   ![рис.5. Установка соединения.](images/5.png){ #fig:005 width=60% }

---

5. Создал репозитории по шаблону (рис.5).

   ![рис.6. Репозитории.](images/6.png){ #fig:006 width=60% }

---

# Выводы

Приобрел навыки работы с git, изучил основные функции, а также соединил его с виртуальной машиной.


## {.standout}

Спасибо за внимание
