Функция `ArrayOptFindBySortedKey()` ищет первый элемент массива с заданным значением определенного поля (ключа).

Если такой элемент не найден, возвращается `undefined`.

## Особенности:
Эта функция предполагает, что массив предварительно отсортирован по ключевому полю в порядке возрастания, что значительно повышает скорость поиска по сравнению с функцией `ArrayOptFindByKey()`. Функцию полезно использовать для частого поиска в больших фиксированных справочниках, которые были заранее отсортированы.

## Аргументы:
- **array**  
    Массив, в котором будет производиться поиск элемента по ключу.
- **keyValue**  
    Значение ключа, по которому будет производиться поиск. Должно быть строкой.
- **keyName** _(необязательный аргумент)_  
    Имя элемента массива, который используется в качестве ключа. Если имя ключа не указано, используется первичный ключ.

## Результат:
- **Any**  
    Возвращает первый элемент, значение ключа которого совпадает с `keyValue`. Если такой элемент не найден, возвращается `undefined`.

[On Datex](http://docs.datex.ru/article.htm?id=5620250451197911700)