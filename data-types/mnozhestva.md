# Множества

Множество в языке Питон — это структура данных, эквивалентная множествам в математике. Множество может состоять из различных элементов, порядок элементов в множестве неопределен. В множество можно добавлять и удалять элементы, можно перебирать элементы множества, можно выполнять операции над множествами \(объединение, пересечение, разность\). Можно проверять принадлежность элементу множества.

В отличии от массивов, где элементы хранятся в виде последовательного списка, в множествах порядок хранения элементов не определен \(более того, элементы множества хранятся не подряд, как в списке, а при помощи хитрых алгоритмов\). Это позволяет выполнять операции типа “проверить принадлежность элемента множеству” быстрее, чем просто перебирая все элементы множества.

Элементами множества может быть любой неизменяемый тип данных: числа, строки, кортежи. Изменяемые типы данных не могут быть элементами множества, в частности, нельзя сделать элементом множества список \(но можно сделать кортеж\) или другое множество. Требование неизменяемости элементов множества накладывается особенностями представления множества в памяти компьютера.

## Дополнительные ссылки:

* [https://foxford.ru/wiki/informatika/mnozhestva-v-python](https://foxford.ru/wiki/informatika/mnozhestva-v-python)
* [https://informatics.mccme.ru/mod/book/view.php?id=6693](https://informatics.mccme.ru/mod/book/view.php?id=6693)
* [https://pythonworld.ru/tipy-dannyx-v-python/mnozhestva-set-i-frozenset.html](https://pythonworld.ru/tipy-dannyx-v-python/mnozhestva-set-i-frozenset.html)
