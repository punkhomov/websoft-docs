Перемещает XML-документ из одного URL в другой URL. В отличие от обычного перемещения файла, действие этой функции сопровождается выполнением стандартных свойств `OnSave`, `OnBeforeSave` и других. Документ сначала пересохраняется по новому URL, затем удаляется из предыдущего. Редко используемая функция.

### Синтаксис
`MoveDoc( url, newUrl )`

### Аргументы
- **url** (`String`): URL существующего документа.
- **newUrl** (`String`): Новый URL документа.

[On Datex](http://docs.datex.ru/article.htm?id=5620276905286592590)