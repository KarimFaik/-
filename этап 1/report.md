---
## Front matter
title: "Индивидуальный проект. Этап 1"
subtitle: "Информационная безопасность "
author: "Фаик Карим"

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

Этап 1. 
Установка Kali Linux
Установите дистрибутив Kali Linux в виртуальную машину.
В качестве среды виртуализации предлагается использовать VirtualBox.
Сайт Kali Linux: https://www.kali.org/
Учётные данные по умолчанию:
логин: root;
пароль: toor.

# Ход работы

1. Скачивание Kali linux.


![изображение 1](image/image1.png)

*изображение 1*

2. Установка Kali linux: 

![изображение 2](image/image2.png)

*изображение 2*

3. Запуск Kali linux в Vbox.

![изображение 3](image/image3.png)

*изображение 3*

4. Вход в Kali linux.

![изображение 5](image/image4.png)

*изображение 5*


# Вывод

Было установлинно дистрибутив Kali Linux в виртуальной машине.
