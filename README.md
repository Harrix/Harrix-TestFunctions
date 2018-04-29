# HarrixTestFunctions

Версия 1.32

Тестовые функции для глобальной оптимизации.

[https://github.com/Harrix/HarrixTestFunctions](https://github.com/Harrix/HarrixTestFunctions)

Файлы распространяются по лицензии [MIT](https://github.com/Harrix/HarrixTestFunctions/blob/master/LICENSE).

Сам документ находится в файле [**_HarrixTestFunctions.pdf**](https://github.com/Harrix/HarrixTestFunctions/blob/master/_HarrixTestFunctions.pdf).

Прямая ссылка на скачивание: [**_HarrixTestFunctions.pdf**](https://raw.github.com/Harrix/HarrixTestFunctions/master/_HarrixTestFunctions.pdf).

В данном документе рассмотрено множество тестовых функций, которые можно использовать для проведения исследований алгоритмов оптимизации. К каждой функции дано подробное описание, график (если это возможно), свойств и параметров, которые позволят единообразно проводить сравнения разных алгоритмов оптимизации во избежания несостыковок с точки зрения разного понимания нахождения ошибки, точности работы алгоритмом.

## Установка

Прочитать подробно об установке можно тут [http://blog.harrix.org/?p=1223](http://blog.harrix.org/?p=1223).

## Тестовые функции

На данный момент функций 30 штук.

* **HML_TestFunction_Ackley** - функция Ackley;
* **HML_TestFunction_GaussianQuartic** - функция Gaussian quartic;
* **HML_TestFunction_Griewangk** - функция Гриванка;
* **HML_TestFunction_HyperEllipsoid** - гипер-эллипсоид;
* **HML_TestFunction_ParaboloidOfRevolution** - эллиптический параболоид;
* **HML_TestFunction_Rastrigin** - функция Растригина;
* **HML_TestFunction_RastriginNovgorod** - функция Растригина новгородская;
* **HML_TestFunction_Rosenbrock** - функция Розенброка;
* **HML_TestFunction_RotatedHyperEllipsoid** - развернутый гипер-эллипсоид;
* **HML_TestFunction_Schwefel** - функция Швефеля;
* **HML_TestFunction_StepFunction** - функция Step (модифицированная версия De Jong 3);
* **HML_TestFunction_AdditivePotential** - аддитивная потенциальная функция;
* **HML_TestFunction_Bosom** - функция Bosom;
* **HML_TestFunction_EggHolder** - функция Egg Holder;
* **HML_TestFunction_Himmelblau** - функция Химмельблау;
* **HML_TestFunction_InvertedRosenbrock** - перевернутая функция Розенброка;
* **HML_TestFunction_Katnikov** - функция Катникова;
* **HML_TestFunction_Multiextremal3** - функция Multiextremal3;
* **HML_TestFunction_Multiextremal4** - функция Multiextremal4;
* **HML_TestFunction_MultiplicativePotential** - мультипликативная потенциальная функция;
* **HML_TestFunction_Rana** - функция Rana;
* **HML_TestFunction_RastriginWithChange** - функция Растригина с изменением коэффициентов;
* **HML_TestFunction_RastriginWithTurning** - функция Растригина овражная с поворотом осей;
* **HML_TestFunction_ReverseGriewank** - функция ReverseGriewank;
* **HML_TestFunction_ShekelsFoxholes** - функция "Лисьи норы" Шекеля;
* **HML_TestFunction_Sombrero** - функция Сомбреро;
* **HML_TestFunction_Multiextremal** - функция Multiextremal;
* **HML_TestFunction_Multiextremal2** - функция Multiextremal2;
* **HML_TestFunction_Wave** - волна;
* **HML_TestFunction_SumVector** - сумма всех элементов бинарного вектора.
 
## Графики некоторых функций

![HML_TestFunction_Ackley](https://raw.github.com/Harrix/HarrixTestFunctions/master/images/HML_TestFunction_Ackley.png)

![HML_TestFunction_AdditivePotential](https://raw.github.com/Harrix/HarrixTestFunctions/master/images/HML_TestFunction_AdditivePotential.png)

![HML_TestFunction_ParaboloidOfRevolution](https://raw.github.com/Harrix/HarrixTestFunctions/master/images/HML_TestFunction_ParaboloidOfRevolution.png)

![HML_TestFunction_Rastrigin](https://raw.github.com/Harrix/HarrixTestFunctions/master/images/HML_TestFunction_Rastrigin.png)

![HML_TestFunction_Rosenbrock](https://raw.githubusercontent.com/Harrix/HarrixTestFunctions/master/images/HML_TestFunction_Rosenbrock.png "HML_TestFunction_Rosenbrock")

## Про структуру проекта

Файл [**_HarrixTestFunctions.pdf**](https://github.com/Harrix/HarrixTestFunctions/blob/master/_HarrixTestFunctions.pdf) - это непосредственно сам документ тестовых функций.

В корневой папке находятся три папки. 

В папке [**Source**](https://github.com/Harrix/HarrixTestFunctions/blob/master/Source) располагаются файлы непосредственно документа, где находится файл [**_HarrixTestFunctions.tex**](https://github.com/Harrix/HarrixTestFunctions/blob/master/_HarrixTestFunctions.tex) (это исходник pdf документа) и файлы, которые являются вызываемыми или вспомогательными для [**_HarrixTestFunctions.tex**](https://github.com/Harrix/HarrixTestFunctions/blob/master/_HarrixTestFunctions.tex).

В папке [**MathcadFiles**](https://github.com/Harrix/HarrixTestFunctions/blob/master/MathcadFiles) располагаются файлы Mathcad, в которых реализованы функции, а также графики для рисунков из папки [**Source/images**](https://github.com/Harrix/HarrixTestFunctions/blob/master/Source/images) в папке [**Source**](https://github.com/Harrix/HarrixTestFunctions/blob/master/Source). 

В папке [**images**](https://github.com/Harrix/HarrixTestFunctions/blob/master/images) находятся служебные рисунки для отображения в этом файле.

## Сведения для редактирования файлов

Для полноценной работы редактированию LaTeX документа вам потребуются программа для компиляции \*.tex документов в \*.pdf. Автор использует для этого связку [MiKTex](http://www.miktex.org/) и [TeXstudio](http://texstudio.sourceforge.net/). 

В варианте, который использует автор, в \*.tex файлах справок для отображения русских букв используется модуль pscyr. Об его установке можно прочитать (и скачать) в статье [http://blog.harrix.org/?p=444](http://blog.harrix.org/?p=444).

Подробное описание установки и настройки связки MiKTeX + TeXstudio + pscyr можно прочитать в статье [http://blog.harrix.org/?p=849](http://blog.harrix.org/?p=849).

## Использованные технологии

- [LaTeX](http://ru.wikipedia.org/wiki/LaTeX), [MiKTeX](http://miktex.org/), [BiBTex](http://ru.wikipedia.org/wiki/BibTeX), [TeXstudio](http://texstudio.sourceforge.net/), [PSCyr]([http://blog.harrix.org/?p=444](http://blog.harrix.org/?p=444)).
- [HarrixLaTeXDocumentTemplate](https://github.com/Harrix/HarrixLaTeXDocumentTemplate).

## История проекта

Подробный список изменений в файле [CHANGELOG.md](https://github.com/Harrix/HarrixTestFunctions/blob/master/CHANGELOG.md).

## Контакты

Автор: Сергиенко Антон Борисович.

С автором можно связаться по адресу [sergienkoanton@mail.ru](mailto:sergienkoanton@mail.ru) или  [http://vk.com/harrix](http://vk.com/harrix).

Сайт автора, где публикуются последние новости: [http://blog.harrix.org](http://blog.harrix.org), а проекты располагаются по адресу: [http://harrix.org](http://harrix.org).