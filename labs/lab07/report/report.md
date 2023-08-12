---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №7"
subtitle: "Командная оболочка Midnight Commander"
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

Освоение основных возможностей командной оболочки Midnight Commander.
Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Выполнение лабораторной работы

1 Изучим информацию о mc при помощи справки man.
Воспользуемся справкой и узнаем что для того чтобы войти в командную оболочку мы должны ввести в командной строке mc.

2 Запустим из командной строки mc.

![Запуск mc](image/01.png){ #fig:001 width=70% height=70% }

3 Выполните несколько операций в mc, используя управляющие клавиши

![Выделение](image/02.png){ #fig:002 width=70% height=70% }

![Отмена](image/03.png){ #fig:003 width=70% height=70% }

![Копирование](image/04.png){ #fig:004 width=70% height=70% }

![Перемещение](image/05.png){ #fig:005 width=70% height=70% }

![Информация](image/06.png){ #fig:006 width=70% height=70% }

4 Выполните основные команды меню левой панели. 

![Быстрый просмотр](image/07.png){ #fig:007 width=70% height=70% }

![Информация](image/08.png){ #fig:008 width=70% height=70% }

![Дерево каталогов](image/09.png){ #fig:009 width=70% height=70% }

5 Используя возможности подменю Файл , выполним:

![Просмотр содержимого текстового файла](image/10.png){ #fig:010 width=70% height=70% }

![Отредактируем содержимое текстового файла без сохранения результатов](image/11.png){ #fig:011 width=70% height=70% }

![Создание каталога ](image/12.png){ #fig:012 width=70% height=70% }

![Копирование в файлов в созданный каталог](image/13.png){ #fig:013 width=70% height=70% }

6. С помощью соответствующих средств подменю Команда осуществите: 

![Поиск файлов](image/14.png){ #fig:014 width=70% height=70% }

![История команд](image/15.png){ #fig:015 width=70% height=70% }

![Переход в домашний каталог](image/16.png){ #fig:016 width=70% height=70% }

![Просмотр файла расширений](image/17.png){ #fig:017 width=70% height=70% }

![Просмотр файла меню](image/18.png){ #fig:018 width=70% height=70% }

7. Вызовем подменю Настройки. Изучим опции

![Конфигурация](image/19.png){ #fig:019 width=70% height=70% }

![Внешний вид](image/20.png){ #fig:020 width=70% height=70% }

![Настройки панелей](image/21.png){ #fig:021 width=70% height=70% }

![Подтверждение](image/22.png){ #fig:022 width=70% height=70% }

![Оформление](image/23.png){ #fig:023 width=70% height=70% }

![Кодировка символов](image/24.png){ #fig:024 width=70% height=70% }

![Распознавание клавиш](image/25.png){ #fig:025 width=70% height=70% }

8 Создадим текстовой файл text.txt. 

9 Откроем этот файл с помощью встроенного в mc редактора, и вставим в открытый файл небольшой фрагмент текста, скопированный из любого другого файла или Интернета. 

![Файл с текстом](image/26.png){ #fig:026 width=70% height=70% }

10 Проделаем с текстом следующие манипуляции, используя горячие клавиши:

Удалим строку текста. - F8

![Файл с текстом](image/27.png){ #fig:027 width=70% height=70% }

Выделим фрагмент текста и скопируйте его на новую строку. - F5

![Копирование фрагмента](image/28.png){ #fig:028 width=70% height=70% }

Сохраним файл. - F2

![Сохранение](image/29.png){ #fig:029 width=70% height=70% }

Отменим последнее действие. - Ctrl+U

![Отмена](image/30.png){ #fig:030 width=70% height=70% }

Перейдем в конец файла - PageDown или Ctrl+X

![Переход в конец файла](image/31.png){ #fig:031 width=70% height=70% }

Перейдем в начало файла - PageUp или Ctrl+Z

![Переход в начало файла](image/32.png){ #fig:032 width=70% height=70% }

11 Откроем файл с исходным текстом на языке программирования C

![Файл с программой](image/33.png){ #fig:033 width=70% height=70% }

12 Используя меню редактора, выключим подсветку синтаксиса.

![Цветовыделение синтаксиса](image/34.png){ #fig:034 width=70% height=70% }

# Вывод

В данной работе мы ознакомились с инструментами командной оболочки Midnight Commander. Приобрели навыки практической работы по просмотру каталогов и файлов 
