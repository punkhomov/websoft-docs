Функция `ArraySelectBySortedKey()` выбирает элементы массива, которые содержат определенное значение в заданном поле (ключе) внутри элемента. Для эффективности работы массива должен быть предварительно отсортирован по возрастанию значения ключа. Эта функция значительно быстрее, чем `ArraySelectByKey()`, однако порядок сортировки возвращаемых элементов не определен.

## Синтаксис
```
ArraySelectBySortedKey(array, keyValue, keyName)  
ArraySelectBySortedKey(array, keyValue, keyName, ignoreCase)
```

## Аргументы:
- **array**  
    Произвольный массив, поддерживающий прямой доступ по порядковому индексу.
- **keyValue**  
    Значение ключа, по которому будет производиться выборка.
- **keyName** (string)  
    Имя элемента, являющегося ключом.
- **ignoreCase** (bool, optional)  
    Игнорировать регистр (для массивов, содержащих строки). Этот аргумент является необязательным.

## Результат:
- **Array**  
    Возвращает массив, содержащий элементы, у которых значение ключа совпадает с `keyValue`.

[On Datex](http://docs.datex.ru/article.htm?id=5791375928854454900)