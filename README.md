# Многопоточная функция генерации случайных чисел.

Пользователь вводит целые положительные числа `n` (размер массива) и `m` (количество потоков). Программа должна заполнить массив случайными числами, используя `m` потоков. Функцию генерации случайных чисел требуется реализовать без использования встроенных средств генерации случайных чисел. Вместо этого следует воспользоваться формулой [линейного конгруэнтного генератора](https://ru.wikipedia.org/wiki/%D0%9B%D0%B8%D0%BD%D0%B5%D0%B9%D0%BD%D1%8B%D0%B9_%D0%BA%D0%BE%D0%BD%D0%B3%D1%80%D1%83%D1%8D%D0%BD%D1%82%D0%BD%D1%8B%D0%B9_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4). Функция генерации чисел должна быть многопоточной, то есть позволять одновременный вызов из нескольких потоков. Каждые 100 вызовов должны меняться параметры a, c и m. Способ смены параметров не имеет значения.
