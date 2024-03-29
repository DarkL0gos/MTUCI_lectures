# MTUCI_lectures
Проект по конспектированию лекций в формате ЛаТеХ. Вдохновлен подобным проектом из МФТИ.

## Экшнс:
- Чекаем изменение главной ветки
- Компиляция latex-action'ом
- Загрузка обратно в папку (и удаление старого артефакта?)
- Выгрузка в releases
- Оттуда ссылаемся на сайт
## Сделать:
- Сайт (в отдельной папке docs с картинкой)
- Две ветки
- Залить весь код 

## На данный момент доступны следующие лекции:

### 1 семестр:
Скородумова Е.А. Алгебра и аналитическая геометрия

### 2 семестр:
Демин Д.Б. Алгебра и аналитическая геометрия
[Последний релиз](https://github.com/DarkL0gos/MTUCI_lectures/releases/latest/download/Dyomin_Algebra.pdf)

Лекции по анализу - в виде черновиков.

## Рекомендуемые настройки: 
```
\documentclass[a4paper]{article}

%Общие настройки документа
\usepackage[12pt]{extsizes}                                         %Размер шрифта
\usepackage[left=2.5cm,right=2.5cm,top=2.5cm,bottom=3cm]{geometry}  %Поля страницы

%Настройки ссылок и гиперссылок
\usepackage{hyperref}                 
\usepackage{xcolor}
\definecolor{linkcolor}{HTML}{799B03} % цвет ссылок
\definecolor{urlcolor}{HTML}{799B03}  % цвет гиперссылок
\hypersetup{pdfstartview=FitH,linkcolor=linkcolor,urlcolor=urlcolor,colorlinks=true}

%Пакеты символов
\usepackage[russian]{babel}           
\usepackage{amsmath}
\usepackage{amssymb}
\usepackage{amsfonts}

%Новые команды 
\newtheorem{defin}{Определение}
\newtheorem{example}{Пример}
\newtheorem{zam}{Замечание}
\newtheorem{theor}{Теорема}

```

