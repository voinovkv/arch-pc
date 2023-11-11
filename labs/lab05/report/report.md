---
## Front matter
title: "Отчет по лабораторной работе №5"
author: "Воинов Кирилл"

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

Приобретение практических навыков работы в Midnight Commander. Освоение инструкций языка ассемблера mov и int.

# Выполнение лабораторной работы

1. Открываю Midnight Commander.(рис. @fig:001).

![Открытие Midnight Commander](image/1.png){#fig:001 width=70%}

2. Перехожу в каталог ~/work/arch-pc созданный при выполнении лабораторной работы No4.(рис. @fig:002).

![Переход в каталог ~/work/arch-pc](image/2.png){#fig:002 width=70%}

3. С помощью функциональной клавиши F7 создаю папку lab05 и перехожу в созданный каталог.(рис. @fig:003) и (рис. @fig:004)

![Создание папки lab05](image/3.png){#fig:003 width=70%}

4. Пользуясь строкой ввода и командой touch создаю файл lab5-1.asm.(рис. @fig:004)

![Переход в созданный каталог и создание файла lab5-1.asm](image/4.png){#fig:004 width=70%}

5. С помощью функциональной клавиши F4 открываю файл lab5-1.asm для редактирования во встроенном редакторе. (рис. @fig:005)

![Открытие файла lab5-1.asm](image/5.png){#fig:005 width=70%}

6. Ввожу текст программы из листинга 5.1, сохраняю изменения и закрываю файл.(рис. @fig:006) и  (рис. @fig:007)

7. С помощью функциональной клавиши F3 открываю файл lab5-1.asm для просмотра. Убеждаюсь, что файл содержит текст программы. (рис. @fig:006) и  (рис. @fig:007)

![Ввод текста программы из листинга 5.1 1](image/6.png){#fig:006 width=70%}

![Ввод текста программы из листинга 5.1 2](image/7.png){#fig:007 width=70%}

8. Оттранслирую текст программы lab5-1.asm в объектный файл. Выполню компоновку объектного файла и запускаю получившийся исполняемый файл. (рис. @fig:008)

![Оттранслирование, компоновка, запуск получившегося исполняемого файла](image/10.png){#fig:008 width=70%}

9. Скачиваю файл in_out.asm со страницы курса в ТУИС.(рис. @fig:009)

![Скаченный файл](image/12.png){#fig:009 width=70%}

10. Копирую файл in_out.asm в тот же каталог, что и файл с программой, в которой он используется.(рис. @fig:010)

![Копирование файла в нужный каталог](image/13.png){#fig:010 width=70%}

11. С помощью функциональной клавиши F6 создаю копию файла lab5-1.asm с именем lab5-2.asm. Выделяю файл lab5-1.asm, нажимаю клавишу F6, ввожу имя файла lab5-2.asm и нажимаю клавишу Enter.(рис. @fig:011)

![Создание копии файла lab5-1.asm с именем lab5-2.asm](image/15.png){#fig:011 width=70%}

12. Исправляю текст программы в файле lab5-2.asm с использование подпрограмм из внешнего файла in_out.asm в соответствии с листингом 5.2. Создаю исполняемый файл и проверяю его работу.(рис. @fig:012) и (рис. @fig:013)

![Исправление текста файла lab5-2.asm](image/17.png){#fig:012 width=70%}

![Создание исполняемого файла и проверка его работы](image/18.png){#fig:013 width=70%}

13. В файле lab5-2.asm заменяю подпрограмму sprintLF на sprint. Создаю исполняемый файл и проверяю его работу. Разница в том, что sprintLF работает аналогично sprint, но при выводе на экран добавляет к сообщению символ перевода строки. То есть в первом случае ввод происходил на следующей строке после 'Введите строку:' а во втором - на этой же строке.(рис. @fig:014)

![Результат замены в lab5-2.asm](image/19.png){#fig:014 width=70%}

# Задание для самостоятельной работы

1. Создаю копию файла lab5-1.asm с названием lab5-1_1.asm. Вношу изменения в программу.(рис. @fig:015)

![lab5-1_1.asm](image/20.png){#fig:015 width=70%}

2. Получаю исполняемый файл и проверяю его работу. На приглашение ввожу свою фамилию.(рис. @fig:016)

![lab5-1_1.asm результат](image/Результат.png){#fig:016 width=70%}

3. Создаю копию файла lab5-2.asm. Исправляю текст программы с использование подпрограмм из внешнего файла in_out.asm.(рис. @fig:017)

![lab5-2_1.asm](image/23.png){#fig:017 width=70%}

4. Создаю исполняемый файл и проверяю его работу.(рис. @fig:018)

![lab5-2_1.asm результат](image/22.png){#fig:018 width=70%}

# Выводы

На этой лабораторной работе я приобрел практические навыки работы в Midnight Commander, освоил инструкции языка ассемблера mov и int.

