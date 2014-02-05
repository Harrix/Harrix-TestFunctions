HarrixTestFunctions
===================

Версия 1.30

Тестовые функции для глобальной оптимизации.

https://github.com/Harrix/HarrixTestFunctions

Файлы распространяются по лицензии [Apache License, Version 2.0](../master/LICENSE.txt).

Сам документ находится в файле [**_HarrixTestFunctions.pdf**](../master/_HarrixTestFunctions.pdf).

Прямая ссылка на скачивание: [**_HarrixTestFunctions.pdf**](https://raw.github.com/Harrix/HarrixTestFunctions/master/_HarrixTestFunctions.pdf).

В данном документе рассмотрено множество тестовых функций, которые можно использовать для проведения исследований алгоритмов оптимизации. К каждой функции дано подробное описание, график (если это возможно), свойств и параметров, которые позволят единообразно проводить сравнения разных алгоритмов оптимизации во избежания несостыковок с точки зрения разного понимания нахождения ошибки, точности работы алгоритмом.

Установка
---------

Прочитать подробно об установке можно тут http://blog.harrix.org/?p=1223.

Тестовые функции
----------------

На данный момент функций 29 штук.
 * **MHL_TestFunction_Ackley** - функция Ackley;
 * **MHL_TestFunction_GaussianQuartic** - функция Gaussian quartic;
 * **MHL_TestFunction_Griewangk** - функция Гриванка;
 * **MHL_TestFunction_HyperEllipsoid** - гипер-эллипсоид;
 * **MHL_TestFunction_ParaboloidOfRevolution** - эллиптический параболоид;
 * **MHL_TestFunction_Rastrigin** - функция Растригина;
 * **MHL_TestFunction_RastriginNovgorod** - функция Растригина новгородская;
 * **MHL_TestFunction_Rosenbrock** - функция Розенброка;
 * **MHL_TestFunction_RotatedHyperEllipsoid** - развернутый гипер-эллипсоид;
 * **MHL_TestFunction_Schwefel** - функция Швефеля;
 * **MHL_TestFunction_StepFunction** - функция Step (модифицированная версия De Jong 3);
 * **MHL_TestFunction_AdditivePotential** - аддитивная потенциальная функция;
 * **MHL_TestFunction_EggHolder** - функция Egg Holder;
 * **MHL_TestFunction_Himmelblau** - функция Химмельблау;
 * **MHL_TestFunction_InvertedRosenbrock** - перевернутая функция Розенброка;
 * **MHL_TestFunction_Katnikov** - функция Катникова;
 * **MHL_TestFunction_Multiextremal3** - функция Multiextremal3;
 * **MHL_TestFunction_Multiextremal4** - функция Multiextremal4;
 * **MHL_TestFunction_MultiplicativePotential** - мультипликативная потенциальная функция;
 * **MHL_TestFunction_Rana** - функция Rana;
 * **MHL_TestFunction_RastriginWithChange** - функция Растригина с изменением коэффициентов;
 * **MHL_TestFunction_RastriginWithTurning** - функция Растригина овражная с поворотом осей;
 * **MHL_TestFunction_ReverseGriewank** - функция ReverseGriewank;
 * **MHL_TestFunction_ShekelsFoxholes** - функция "Лисьи норы" Шекеля;
 * **MHL_TestFunction_Sombrero** - функция Сомбреро;
 * **MHL_TestFunction_Multiextremal** - функция Multiextremal;
 * **MHL_TestFunction_Multiextremal2** - функция Multiextremal2;
 * **MHL_TestFunction_Wave** - волна;
 * **MHL_TestFunction_SumVector** - сумма всех элементов бинарного вектора.
 
Графики некоторых функций
-------------------------

![alt text](../master/images/MHL_TestFunction_Ackley.png "MHL_TestFunction_Ackley")

![alt text](../master/images/MHL_TestFunction_AdditivePotential.png "MHL_TestFunction_AdditivePotential")

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

Для полноценной работы редактированию LaTeX документа вам потребуются программа для компиляции \*.tex документов в \*.pdf. Автор использует для этого связку [MiKTex](http://www.miktex.org/) и [TeXstudio](http://texstudio.sourceforge.net/). 

В варианте, который использует автор, в \*.tex файлах справок для отображения русских букв используется модуль pscyr. Об его установке можно прочитать (и скачать) в статье http://blog.harrix.org/?p=444.

Подробное описание установки и настройки связки MiKTeX + TeXstudio + pscyr можно прочитать в статье http://blog.harrix.org/?p=849.

Использованные технологии
-------------------------

- LaTeX, MiKTeX, BibTex, TeXstudio, pscyr.
- HarrixLaTeXDocumentTemplate.

История проекта
---------------

Подробный список изменений в файле [CHANGELOG.md](../master/CHANGELOG.md).

Контакты
--------

Автор: Сергиенко Антон Борисович.

С автором можно связаться по адресу sergienkoanton@mail.ru или  http://vk.com/harrix.

Сайт автора, где публикуются последние новости: http://blog.harrix.org, а проекты располагаются по адресу: http://harrix.org.