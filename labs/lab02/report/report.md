---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №2"
subtitle: "Управление версиями"
author: "Леденев Егор Олегович"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью данной работы является изучение идеологии и применения средств контроля версий и освоение умений работать с git.

# Выполнение лабораторной работы

Устанавливаем git, git-flow и gh.

![Загрузка пакетов](image/01.png){ #fig:001 width=70% height=70% }

Зададим имя и email владельца репозитория, кодировку и прочие параметры.

![Параметры репозитория](image/02.png){ #fig:002 width=70% height=70% }

Создаем SSH ключи

![rsa-4096](image/03.png){ #fig:003 width=70% height=70% }

![ed25519](image/04.png){ #fig:004 width=70% height=70% }

Создаем GPG ключ

![GPG ключ](image/05.png){ #fig:005 width=70% height=70% }

Добавляем GPG ключ в аккаунт

![GPG ключ](image/06.png){ #fig:006 width=70% height=70% }

Настройка автоматических подписей коммитов git

![Параметры репозитория](image/07.png){ #fig:007 width=70% height=70% }

Настройка gh

![Связь репозитория с аккаунтом](image/08.png){ #fig:008 width=70% height=70% }

Загрузка шаблона репозитория и синхронизация

![Загрузка шаблона](image/09.png){ #fig:009 width=70% height=70% }

Подготовка репозитория и коммит изменений

![Первый коммит](image/10.png){ #fig:010 width=70% height=70% }

# Вывод

Мы приобрели практические навыки работы с сервисом github.
