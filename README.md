# Техническое задание: Игра "Жизнь"

## Цель
Целью этого проекта является создание программы, которая реализует игру "Жизнь" с использованием Python и библиотеки Tkinter для создания графического интерфейса.

## Описание
Игра "Жизнь" (Game of Life) - это клеточный автомат, придуманный математиком Джоном Конвеем в 1970 году. Она моделирует эволюцию клеточных структур на двумерной решетке с простыми правилами. В этой игре клетки могут быть живыми или мертвыми, и их состояние изменяется в зависимости от числа соседей.

## Правила игры
1. **Живая клетка** продолжает существовать на следующем шаге, если у неё **2 или 3 соседа** (по горизонтали, вертикали или диагонали), в противном случае она умирает от одиночества или перенаселённости.
2. **Мёртвая клетка** становится живой, если у неё **ровно 3 соседа**.

## Функциональные требования
- Визуализация игрового поля в виде двумерной сетки клеток.
- Возможность запуска/остановки симуляции.
- Пользовательский интерфейс с кнопкой для управления симуляцией.

## Технические требования
- Язык программирования: Python 3.
- Библиотеки: Tkinter для создания графического интерфейса.
- Использование массивов NumPy для эффективной работы с двумерным массивом клеток.

## Зависимости
Для запуска этой программы потребуется Python версии 3 и библиотеки Tkinter и NumPy. Они могут быть установлены с использованием pip:

```shell
pip install numpy
pip install tkinter
```

## Пример реализации
Пример реализации игры "Жизнь" на Python с использованием библиотеки Tkinter можно найти в файле `game_of_life.py` в этом репозитории.

## Инструкции по установке и запуску
1. Убедитесь, что у вас установлен Python 3.
2. Скачайте содержимое репозитория.
3. Откройте терминал (командную строку) и перейдите в папку с содержимым репозитория.
4. Запустите программу, введя команду `python game_of_life.py`.

## Дальнейшие улучшения
- Добавление возможности сохранения и загрузки конфигураций игрового поля.
- Реализация более сложных правил и дополнительных функций, таких как рисование на поле клеток пользователем.

## Примечания
- Дополнительная информация о правилах игры "Жизнь" и её различных вариантах может быть найдена в литературе и онлайн ресурсах.
