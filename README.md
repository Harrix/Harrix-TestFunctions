HarrixTestFunctions
===================

Версия 1.4

Тестовые функции для глобальной оптимизации.

https://github.com/Harrix/HarrixTestFunctions

Файлы распространяются по лицензии [Apache License, Version 2.0](../master/LICENSE.txt).

Сам документ находится в файле [**_HarrixTestFunctions.pdf**](../master/_HarrixTestFunctions.pdf).

В данном документе рассмотрено множество тестовых функций, которые можно использовать для проведения исследований алгоритмов оптимизации. К каждой функции дано подробное описание, график (если это возможно), свойств и параметров, которые позволят единообразно проводить сравнения разных алгоритмов оптимизации во избежания несостыковок с точки зрения разного понимания нахождения ошибки, точности работы алгоритмом.

Тестовые функции
----------------

На данный момент функций 5 штук.
 * **MHL_TestFuction_Ackley** - функция Ackley.
 * **MHL_TestFuction_ParaboloidOfRevolution** - эллиптический параболоид.
 * **MHL_TestFuction_Rastrigin** - функция Растригина.
 * **MHL_TestFuction_Rosenbrock** - функция Розенброка.
 * **MHL_TestFuction_SumVector** - сумма всех элементов бинарного вектора.
 
Графики некоторых функций
-------------------------

![alt text](../master/images/MHL_TestFunction_Ackley.png "MHL_TestFunction_Ackley")

![alt text](../master/images/MHL_TestFunction_ParaboloidOfRevolution.png "MHL_TestFunction_ParaboloidOfRevolution")

![alt text](../master/images/MHL_TestFunction_Rastrigin.png "MHL_TestFunction_Rastrigin")

![alt text](../master/images/MHL_TestFunction_Rosenbrock.png "MHL_TestFunction_Rosenbrock")

Про структуру проекта
---------------------

Файл [**_HarrixTestFunctions.pdf**](../master/_HarrixTestFunctions.pdf) - это непосредственно сам документ тестовых функций.

В корневой папке находятся три папки. 

В папке [**Source**](../master/Source) располагаются файлы непосредственно документа, где находится файл [**_HarrixTestFunctions.tex**](../master/_HarrixTestFunctions.tex) (это исходник pdf документа) и файлы, которые являются вызываемыми или вспомогательными для [**_HarrixTestFunctions.tex**](../master/_HarrixTestFunctions.tex).

В папке [**MathcadFiles**](../master/MathcadFiles) располагаются файлы Mathcad, в которых реализованы функции, а также графики для рисунков из папки [**Source/images**](../master/Source/images) в папке [**Source**](../master/Source). 

В папке [**images**](../master/images) находятся служебные рисунки для отображения в этом файле.

Сведения для редактирования файлов
----------------------------------

Для полноценной работы редактированию LaTeX документа вам потребуются программа для компиляции *.tex документов в *.pdf. Автор использует для этого связку [MiKTex](http://www.miktex.org/) и [TeXstudio](http://texstudio.sourceforge.net/). 

В варианте, который использует автор, в *.tex файлах справок для отображения русских букв используется модуль pscyr. Об его установке можно прочитать (и скачать) в статье http://blog.harrix.org/?p=444.

История проекта
---------------

Подробный список изменений в файле [CHANGELOG.md](../master/CHANGELOG.md).

Контакты
--------

Автор: Сергиенко Антон Борисович.

С автором можно связаться по адресу sergienkoanton@mail.ru или  http://vk.com/harrix.

Сайт автора, где публикуются последние новости: http://blog.harrix.org, а проекты располагаются по адресу: http://harrix.org.