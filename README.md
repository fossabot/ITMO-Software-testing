<h2 align=center>Тестирование программного обеспечения</a> </h2>

<h3 align=center> <a href="lab1">Лабораторная работа 1</a> </h3>

  1. Для функции `sin(x)` провести модульное тестирование разложения функции в степенной ряд. Выбрать достаточное тестовое покрытие;
  2. Провести модульное тестирование алгоритма BFS (обход ориентированного графа в ширину). Для этого выбрать характерные точки внутри алгоритма, и для предложенных самостоятельно наборов исходных данных записать последовательность попадания в характерные точки. Сравнить последовательность попадания с эталонной;
  3. Сформировать доменную модель для заданного текста.  Разработать тестовое покрытие для данной доменной модели

Описание предметной области 

`
Голова робота, сидящего в углу, сначала резко дернулась вверх,
а затем едва заметно закачалась из стороны в сторону. Он тяжело
поднялся на ноги и сделал то, что показалось бы постороннему
наблюдателю героической попыткой пересечь комнату. Он остановился
перед Триллиан и посмотрел, как будто, сквозь ее левое плечо.
`


<h3 align=center> <a href="lab2">Лабораторная работа 2</a> </h3>

Провести интеграционное тестирование программы, осуществляющей вычисление системы функций (в соответствии с вариантом).
```
x <= 0 : (((((tan(x) * cos(x)) - (csc(x) - cos(x))) ^ 2) / cot(x)) ^ 2)
x > 0 : (((((log_3(x) + log_2(x)) / (log_5(x) ^ 3)) + log_10(x)) + log_10(x)) / (log_5(x) - log_5(x)))
```
<h3 align=center> <a href="lab3">Лабораторная работа 3</a> </h3>
Сформировать варианты использования, разработать на их основе тестовое покрытие покрытие и провести функциональное тестирование интерфейса сайта `http://www.linkedin.com/`
Требования к выполнению работы:

Тестовое покрытие должно быть сформировано на основании набора прецедентов использования сайта.
Тестирование должно осуществляться автоматически - с помощью системы автоматизированного тестирования Selenium.
Шаблоны тестов должны формироваться при помощи Selenium IDE и исполняться при помощи Selenium RC в браузерах Firefox и Chrome.
Предполагается, что тестируемый сайт использует динамическую генерацию элементов на странице, т.е. выбор элемента в DOM должен осуществляться не на основании его ID, а с помощью XPath.
