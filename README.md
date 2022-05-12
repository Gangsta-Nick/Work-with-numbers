## Stream API

### Работа с числами

Составьте ArrayList из набора чисел `1, 2, 5, 16, -1, -2, 0, 32, 3, 5, 8, 23, 4` и произведите над ним следующие действия:

Отфильтруйте положительные числа.
Найдите среди этих положительных чисел четные.
Отсортируйте отфильтрованные числа в порядке возрастания.
Выведите результат на экран.

### Реализация

Реализуйте два класса `Main` и `StreamMain`, в каждом из которых в функции `main()` составьте `ArrayList` из приведенных выше чисел и произведите над ними указанные операции, причем:

* в первом классе работа выполнена без `Stream API`, использованны коллекции
* во втором классе используются стримы из библиотеки `Stream API`.

И с помощью стримов, и без них Вы должны получить одинаковый ответ: `2 4 8 16 32`
