---
## Front matter
lang: ru-RU
title: Лабораторная работа №1
subtitle: Настройка рабочего окружения. Система контроля версий Git
author:
  - Федорова А. И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 21 февраля 2026

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

  * Федорова Анжелика Игоревна
  * Студент
  * Российский университет дружбы народов
  * Предмет: Математическое моделирование

# Цель работы

## Цель

- Настроить рабочее окружение для работы с Git
- Создать репозиторий курса на основе шаблона
- Настроить SSH- и GPG-ключи
- Освоить работу с git flow

# Выполнение лабораторной работы

## Установка Quarto

Установка Quarto с помощью пакетного менеджера dnf.

![Установка Quarto](image/1.png){#fig-001 width=60%}

## Установка Node.js

Пакет nodejs уже был установлен в системе.

![Установка Node.js](image/2.png){#fig-002 width=60%}

## Установка gitflow

Установка пакета gitflow для работы с моделью ветвления.

![Установка gitflow](image/3.png){#fig-003 width=60%}

## Создание репозитория на GitVerse

Создан публичный репозиторий `2026-1--study--simulation-modeling` на основе шаблона.

![Создание репозитория](image/4.png){#fig-004 width=60%}

## Настройка SSH-ключа

SSH-ключ сгенерирован и добавлен в учётную запись GitVerse.

![SSH-ключ в GitVerse](image/5.png){#fig-005 width=60%}

## Создание GPG-ключа

Сгенерирован GPG-ключ RSA 4096 бит для подписи коммитов.

![Создание GPG-ключа](image/6.png){#fig-006 width=60%}

## Добавление GPG-ключа в GitVerse

GPG-ключ успешно добавлен в учётную запись.

![GPG-ключ в GitVerse](image/7.png){#fig-007 width=60%}

## Настройка подписи коммитов

Настроен git для автоматической подписи коммитов GPG-ключом.

![Настройка подписи коммитов](image/8.png){#fig-008 width=60%}

## Создание структуры курса

Выполнены `make prepare`, `git add`, `git commit` и `git push`.

![Структура курса и push](image/9.png){#fig-009 width=60%}

## Инициализация git flow

Выполнена команда `git flow init` с параметрами по умолчанию. Созданы ветки `master` и `develop`.

![Инициализация git flow](image/10.png){#fig-010 width=60%}

## Создание релиза

Создан релиз 1.0.0 и сгенерирован `CHANGELOG.md`.

![Создание релиза](image/11.png){#fig-011 width=60%}

## Завершение релиза

Релиз завершён: слияние в `master`, тег `v1.0.0`, обратное слияние в `develop`.

![Завершение релиза](image/12.png){#fig-012 width=60%}

# Результаты

## Выводы

- Установлены Quarto, Node.js, gitflow
- Создан репозиторий курса на GitVerse
- Настроены SSH- и GPG-ключи
- Выполнена инициализация git flow
- Создан первый релиз v1.0.0
