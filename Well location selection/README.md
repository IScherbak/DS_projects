# Выбор локации для нефтяной скважины

## Описание проекта

Добывающей компании нужно решить, где бурить новую скважину.
Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. 

## Цель проекта

Построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. 
Для анализа потенциальной прибыли и рисков использовать технику *Bootstrap*.

## Описание данных

id — уникальный идентификатор скважины; <P>
f0, f1, f2 — три признака точек (признаки неизвестны, но известно, что они значимы для исследования); <P>
product — объём запасов в скважине (тыс. баррелей). <P>

## Вывод

Регион к предложению для разработки скважин - второй, т.к. среди прочих имеет минимальный риск убытков и максимально возможную прибыль.
В первом и третьем регионах риски кратно аналогичные во втором регионе.

## Используемые библиотеки

pandas, numpy, seaborn, math, matplotlib, scikit-learn, warnings
