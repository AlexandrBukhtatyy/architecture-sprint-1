# Выбор фреймворка для создания микро-фронтенда

| <!-- --> | <!-- -->                                                               |
|----------|------------------------------------------------------------------------|
| Status   | Предложено                                                             |
| issue    | Для перехода на микрофронтенд нужно выбрать более подходящий фреймворк |
| desicion |                                                                        |
| ticket   | 1.1                                                                    |


Содержание:
* [Описание](#описание)
    * [Проблема](#проблема)
    * [Предложение](#assumptions)
    * [Предложение](#assumptions)
    * [Ограничения](#constraints)
    * [Варианты](#positions)
    * [Аргументы](#argument)
    * [Реализация](#implications)
* [Решение](#решение)
* [Полезные ссылки](#полезные ссылки)

## Описание

### Проблема

### Предложение

### Ограничения
Решение должно:
* Изолировать модули
* Позволять загружать модули в runtime       |
* Шарить между модулями общие зависимости
* Быть производительным
* Иметь достаточно документации
* Поддерживаемым комьюнити
* Простым

### Варианты
* Module Federation
* Native Federation
* Single-Spa

### Аргументы
Предлагаю использовать Module Federatio, так как данное решение решает наши проблемы в полной мере.

| <!-- -->                         | Module Federation | Native Federation | Single-Spa |
|----------------------------------|-------------------|-------------------|------------|
| Загрузка модулей в runtime       | +                 |                   |            |
| Общее использование зависимостей |                   |                   |            |
| Изоляция модулей                 |                   |                   |            |
| Производительность               |                   |                   |            |
| Популярность                     |                   |                   |            |
| Документация                     |                   |                   |            |
| Простота                         |                   |                   |            |
| Framework Agnostic               |                   |                   |            |
|                                  |                   |                   |            |

### Реализация

## Решение

## Полезные ссылки
* [Understanding the Difference Between Native Federation, Module Federation, and Single-Spa](https://medium.com/@erickzanetti/understanding-the-difference-between-native-federation-module-federation-and-single-spa-6cd6d29029b5)
* [Micro Frontends with Native Federation](https://dev.to/florianrappl/micro-frontends-with-native-federation-56j4)
