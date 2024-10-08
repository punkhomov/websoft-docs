Загружает код на JavaScript из заданного URL и выполняет его.

### Синтаксис
`EvalCodeUrl( codeUrl )`  
`EvalCodeUrl( codeUrl, subCode )`

### Аргументы
- **codeUrl** (тип `String`)  
    URL, содержащий код.
- **subCode** (тип `String`, необязательный)  
    Вспомогательный код, выполняемый после выполнения основного кода. Обычно содержит вызов функции, описанной в основном коде.

### Результат
Возвращает любое значение, в зависимости от выполненного кода.

### Пример
```js
EvalCodeUrl( 'rcr_lib_backup.js', 'RunBackup()' )
```

### Примечание
Использование данной функции для вызова функций, описанных в файле, не рекомендуется после появления функции [OpenCodeLib()](http://docs.datex.ru/article.htm?id=5620276905286592593), которая предлагает более понятные правила области видимости переменных:
```js
OpenCodeLib( 'rcr_lib_backup.js' ).RunBackup()
```

[On Datex](http://docs.datex.ru/article.htm?id=5620250451197911782)