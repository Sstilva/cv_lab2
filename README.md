# Компьютерное зрение лаба 2 
## Задача поиска объекта на изображении по шаблону


Данный проект представляет собой реализацию алгоритма поиска объекта на изображении с использованием алгоритмов **ORB**(Oriented FAST and Rotated BRIEF) и **BFMatcher**

1. Используется ORB (Oriented FAST and Rotated BRIEF) для обнаружения ключевых точек и их дескрипторов на обоих изображениях
2. Затем используется **BFMatcher** для сопоставления дескрипторов ключевых точек (Это позволяет найти совпадения между ключевыми точками).
3. Совпадения сортируются по расстоянию и отбираются наиболее близкие. 
4. Далее определяется ограничивающий прямоугольник вокруг совпавших точек, который указывает на местоположение объекта на исходном изображении.


### Метрики
* Метрика точности - 0.39
### Примеры реализации
* Удачный поиск объекта
<img width="825" alt="Снимок экрана 2023-10-07 в 14 16 52" src="https://github.com/Sstilva/cv_lab2/assets/57155484/bffe44f8-0c75-418a-ba17-c016b50d8013">
<img width="768" alt="Снимок экрана 2023-10-07 в 14 17 08" src="https://github.com/Sstilva/cv_lab2/assets/57155484/d3f23447-aa0b-4d9f-8582-c8a5864e05f4">

* Неудачный поиск объекта
<img width="830" alt="Снимок экрана 2023-10-07 в 14 18 37" src="https://github.com/Sstilva/cv_lab2/assets/57155484/4ad084a2-8076-4291-99b6-456e0787a14b">


## Команда
 * Байрамова Хумай
 * Данишевский Никита
 * Калинин Александр
 * Лисицина Василиса


