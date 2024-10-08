Загружает содержимое файла с заданным URL с учетом наличия BOM. При необходимости происходит конвертация между кодировками.

### Синтаксис
`LoadUrlText(url) LoadUrlText(url, options)`

### Аргументы
- **url** (тип: `string`)  
    URL файла, содержимое которого нужно загрузить.
- **options** (тип: `object`, необязательный)  
    Объект с опциями для загрузки. В настоящий момент поддерживается единственная опция:
    - **DetectContentCharset** (тип: `boolean`): Если задано `true`, функция предварительно пытается определить, содержит ли файл данные в UTF-8, и, если да, возвращает содержимое файла без изменений.

### Результат
- `String`  
    Содержимое файла, возможно после конвертации кодировки.

### Описание
- Если файл начинается на UTF-16 BOM, происходит конвертация из UTF-16 в текущую кодировку (UTF-8).
- Если файл начинается на UTF-8 BOM, возвращается содержимое файла после BOM.
- Если BOM отсутствует и опция `DetectContentCharset` не установлена, происходит конвертация из однобайтовой кодировки по умолчанию (например, Windows-1251) в UTF-8.

### Смотри также
- [LoadFileText()](http://docs.datex.ru/article.htm?id=7172076235998782838)

[On Datex](http://docs.datex.ru/article.htm?id=7172076235998782839)