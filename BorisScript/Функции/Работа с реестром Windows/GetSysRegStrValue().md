Возвращает строковое значение из реестра Windows. Если элемент не существует, возвращается пустая строка.

### Синтаксис
`GetSysRegStrValue( path, name )`

### Аргументы
- **path** (`String`): Полный путь к ключу реестра.
- **name** (`String`): Имя элемента. Если указано пустое имя, используется элемент по умолчанию.

### Результат
- **String**: Строковое значение элемента реестра или пустая строка, если элемент не существует.

### Пример
``` js
GetSysRegStrValue( 'HKEY_CURRENT_USER\\Software\\Clients\\Mail\\', '' )
```

[On Datex](http://docs.datex.ru/article.htm?id=5620276892448878618)