# CSharp_lab05
Лабораторная работа №5
«Массивы и коллекции. Интерфейс IEnumerable»

Цели работы:
Научиться реализации интерфейса IEnumerable и работе с массивами и коллекциями языка C#.

Задание№1
Создайте класс MyMatrix, представляющий матрицу m на n.
Создайте конструктор, принимающий число строк и столбцов, заполняющий матрицу случайными числами в диапазоне, который пользователь вводит при запуске программы.
Создайте метод Fill, перезаполняющий матрицу случайными значениями.
Создайте метод ChangeSize, изменяющий число строк и/или столбцов с копированием значений существующей матрицы. Если новая матрица больше существующий, то метод должен дозаполнить новую матрицу случайными числами.
Создайте метод ShowPartialy, принимающий в качестве параметров начальные и конечные значения строк и столбцов, значения матрицы внутри которых нужно вывести на консоль.
Создайте метод Show, выводящий все значения матрицы на консоль.
Создайте индексатор для матрицы вида this[int index1, int index2] с аксессором и мутатором.

Задание№2
Создайте класс MyList<T>.
Реализуйте в простейшем приближении возможность использования его экземпляра аналогично экземпляру класса List<T>.
Минимально требуемый интерфейс взаимодействия с экземпляром должен включать метод добавления элемента, индексатор для получения значения элемента по указанному индексу, свойство получения общего количества элементов и поддержку инициализатора коллекции.
При выполнении нельзя использовать коллекции, только массивы.

Задание№3
Создайте коллекцию MyDictionary<TKey,TValue>.
Реализуйте в простейшем приближении возможность использования ее экземпляра аналогично экземпляру класса Dictionary<TKey,TValue>.
Минимально требуемый интерфейс взаимодействия с экземпляром должен включать метод добавления элемента, индексатор для получения значения элемента по указанному индексу и свойство только для чтения для получения общего количества элементов.
Реализуйте возможность перебора элементов коллекции в цикле foreach. При выполнении нельзя использовать коллекции, только массивы.

