# Задача "Исследование JVM через VisualVM"

## Описание
Предлагаем вам изучить использование памяти через VisualVM при загрузке новых классов и создании новых объектов

## Инструкция
Скачайте и установите утилиту [VisualVM](https://visualvm.github.io/download.html).  
Запульте и запустите проект [отсюда](https://github.com/Arsennikum/jvm-visualvm-experience).  

## Ответ

Сначала прогрмамма спит 30 секунд.

Так как загрузка классво ленивая, классы не загружаются, пока мы к нимне обратимся.

Затем начинается загрузка классов из зависимостей:

![Class loader](https://github.com/NataliaSafiullina/HW_JVM/raw/main/src/jvm_work.png)