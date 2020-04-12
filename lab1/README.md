# Лабораторная работа #1

## Данные
Модель представляется в виде файла формата `.stl`.

![data_demo](images/1.png)

## Фильтр
В качестве фильтра применялся `vtkSmoothPolyDataFilter`, который
корректирует координаты точки с помощью сглаживания Лапласа.

![filter_demo1](images/2.png)

## Виджет
Выбран `vtkImplicitPlaneWidget`, который 
предназначен для интерактивного отсечения полигональных
данных плоскостью.

![widget_demo](images/3.png)