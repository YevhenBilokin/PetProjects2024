Мини-проект: Анализ данных о продажах

Описание задачи:
Представь, что у тебя есть текстовый файл с данными о продажах товаров в магазине. Данные содержат информацию о каждом товаре, который был продан за день. Каждая строка в файле представляет одну продажу и содержит:
- Название товара,
- Количество проданных единиц,
- Стоимость одной единицы товара.

Твоя задача — написать программу для анализа этих данных, которая:
1. Читает файл с данными о продажах.
2. Выводит различные сводки по данным.
3. Поддерживает функции для анализа продаж с использованием базовых алгоритмов, циклов и рекурсии.

Формат файла с данными:
Создай файл с названием `sales.txt`, который будет содержать данные в таком формате: 
apple, 5, 10 banana, 3, 15 apple, 2, 10 orange, 10, 8 banana, 7, 15


Каждая строка содержит название товара, количество проданных единиц и стоимость одной единицы товара (через запятую).

Задачи:

1. **Чтение и парсинг файла**: 
   Создай функцию, которая прочитает файл и преобразует данные в удобный для обработки формат (список списков или кортежей).

2. **Общая сумма выручки**:
   Напиши функцию, которая вычислит общую сумму выручки за день.

3. **Продажи по каждому товару**:
   Напиши функцию, которая подсчитает количество проданных единиц для каждого товара.

4. **Самый продаваемый товар**:
   Напиши функцию, которая найдёт товар, который продали больше всего.

5. **Общая прибыль с каждого товара**:
   Напиши функцию, которая вычислит, сколько денег было заработано на каждом товаре.

6. **Поиск товаров, которые продались больше определённого количества**:
   Напиши рекурсивную функцию, которая возвращает список товаров, продажи которых превысили заданное количество.

7. **Визуальный вывод данных**:
   Добавь функцию, которая выведет все продажи в виде таблицы с колонками для товара, количества и цены.
