---
## Front matter
title: "ОТЧЕТ ПО ЛАБОРАТОРНОЙ РАБОТЕ № 2"
author: "Воинов Кирилл Викторович"

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

Целью работы является изучить идеологию и применение средств контроля версий. Приобрести
практические навыки по работе с системой git.


# Ход работы

1. Создаю учётную запись на сайте https://github.com/ и заполняю основные данные. (рис. @fig:001).

![Учетная запись github](image/1.png){#fig:001 width=70%}

2. Делаю предварительную конфигурацию git, открыв терминал и введя следующие команды, указав
имя и email владельца репозитория. (рис. @fig:002 и рис. @fig:003).

![Ввод имени владельца репозитория](image/2.png){#fig:002 width=70%}

![Ввод email владельца репозитория](image/3.png){#fig:003 width=70%}

3. Настраиваю utf-8 в выводе сообщений git. (рис. @fig:004).

![Настройка utf-8](image/4.png){#fig:004 width=70%}

4. Задаю имя начальной ветки, параметр autocrlf и параметр safecrlf. (рис. @fig:005).

![Ввод имени начальной ветки, параметров autocrlf и safecrlf](image/5.png){#fig:005 width=70%}

5. Генерирую ключи для последующей идентификации пользователя на сервере репозиториев. (рис. @fig:006).

![Генерация ключей](image/6.png){#fig:006 width=70%}

6. Копирую из локальной консоли ключ в буфер обмена(рис. @fig:007).

![Копирование ключа в буфер обмена](image/7.png){#fig:007 width=70%}

7. Загружаю сгенерированный открытый ключ. (рис. @fig:008).

![Ключ в github](image/8.png){#fig:008 width=70%}

8. Создаю каталог для предмета «Архитектура компьютера». (рис. @fig:009).

![Создание каталога "Архитектура компьютера"](image/9.png){#fig:009 width=70%}

9. Перехожу в каталог курса и клонирую созданный репозиторий. (рис. @fig:010).

![Клонирование репозитория](image/10.png){#fig:010 width=70%}

10. Удаляю лишние файлы. (рис. @fig:011).

![Удаление лишних файлов](image/11.png){#fig:011 width=70%}

11. Создаю необходимые каталоги. (рис. @fig:012).

![Создание каталога](image/12.png){#fig:012 width=70%}

12. Отправляю файлы на сервер. (рис. @fig:013 и рис. @fig:014).

![Отправка файлов (1)](image/13.png){#fig:013 width=70%}

![Отправка файлов (2)](image/14.png){#fig:014 width=70%}

13. Проверяю правильность создания иерархии рабочего пространства в локальном репозитории и
на странице github. (рис. @fig:015 и рис. @fig:016).

![Проверка (1)](image/15.png){#fig:015 width=70%}

![Проверка (2)](image/16.png){#fig:016 width=70%}

# Задания для самостоятельной работы

1. Создаю отчет по выполнению лабораторной работы в соответствующем каталоге
рабочего пространства. (рис. @fig:017).

![Создание отчета](image/17.png){#fig:017 width=70%}

2. Копирую отчеты по выполнению предыдущих лабораторных работ в соответствующие каталоги
созданного рабочего пространства. (рис. @fig:018).

![Копирование предыдущего отчета](image/18.png){#fig:018 width=70%}

3. Загружаю файлы на github. (рис. @fig:019).

![Загрузка файлов на github](image/19.png){#fig:019 width=70%}

# Вывод

Выполнив эту лабораторную работу, я изучил идеологию и применение средств контроля версий,
приобрёл практические навыки по работе с системой git.

