---
## Front matter
title: "Первый этап индивидуального проекта"
author: "Ортега Вероника"

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

Разместить на Github pages заготовки для персонального сайта

# Задание

* Установить необходимое программное обеспечение.
* Скачать шаблон темы сайта.
* Разместить его на хостинге git.
* Установить параметр для URLs сайта.
* Разместить заготовку сайта на Github pages

# Теоретическое введение

Сайт – это совокупность веб-страниц, объединённых под общим доменом и
связанных ссылками, тематикой и дизайнерским оформлением [1] . Мы будем
создавать статический сайт, для этого нам понадобится Hugo. Hugo — генератор
статических страниц для интернета.

# Выполнение лабораторной работы

1. Установим необходимое програмное обеспечение. Скачаем Hugo и Go. Ска-
чаем необходимый релиз и положим его в папку /tmp/01. Распакованный
файл hugo поместим в usr/local/bin.Проверим версию Hugo.(рис. @fig:001).
![Установка Hugo и Go](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/etap1.png){#fig:001 width=70%}

2. В качестве шаблона индивидуального сайта используется шаблон Hugo
Academic Theme. Переходим по ссылке и создаем репозиторий blog(рис. @fig:002).
![Создание репозитория blog](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/etap2.png){#fig:002 width=70%}

Клонируем репозиторий(рис. @fig:003).
![Клонирование репозитория](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/etap3.png){#fig:003 width=70%}

3. Выполним команду hugo server (создадутся необходимые файлы). Нам
предоставят ссылку. Переходя по ней, открывается наш сайт (пока на него
можно заходить только с моего компьютера)(рис. @fig:004).
![оманда hugo server](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/etap5.png){#fig:003 width=70%}

4. Необходимо создать еще один репозиторий, чтобы наш сайт можно было
открывать с любого компьютера.
Клонируем наш новый репозиторий. Создаем ветку main. Создаем файл
README.md. Добавляем в наш репозиторий.(рис. @fig:005.
![Клонирование репозитория, создание ветки main, создание файла README.md](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/etap4.png){#fig:005 width=70%}

5. Подключаем наш репозиторий к папке public.(рис. @fig:006).
![Подключение репозитория к папке public](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/etap6.png){#fig:06 width=70%} 

Добавление файлов в репозиторий. (рис. @fig:007).
![Добавление файлов в репозиторий](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/etap7.png){#fig:07 width=70%} 

6. Сайт готов. (рис. @fig:008).(рис. @fig:009)(рис. @fig:010).
![Сайт](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/etap8.png){#fig:008 width=70%} 
![Сайт](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/etap9.png){#fig:009 width=70%} 
![Сайт](work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/1.jpeg){#fig:010 width=70%} 

# Выводы

Научились создавать статические сайты с помощью Hugo

# Список литературы{.unnumbered}

1. Что такое сайт (простыми словами)l [Электронный ресурс]. URL: https:
//uguide.ru/chto-takoe-sajt-prostymi-slovami.
 
::: {#refs}
:::
