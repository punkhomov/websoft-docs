Регистрирует фрагмент (элемент) существующей формы под новым URL. Новый URL состоит из URL формы и полного наименования элемента формы, которое включает в себя путь внутри формы от корня до этого элемента. Возвращает URL новой формы.

Редко используемая функция.

### Аргументы
- **formUrl** (тип `String`) 
	URL формы
- **elemPath** (тип `String`) 
	Полное наименование элемента формы, включающее в себя путь внутри формы от корня до этого элемента

### Результат
- `String`

### Пример
```js
RegisterSubForm('base3_events.xmd', 'events.event')
```

[On Datex](http://docs.datex.ru/article.htm?id=5620276905286592619)