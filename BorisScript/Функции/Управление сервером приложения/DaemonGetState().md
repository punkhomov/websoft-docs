Определяет статус зарегистрированного сервера приложения (службы Windows).

Значения статуса:
- `0` - сервер выключен
- `1` - сервер включен
- `2` - сервер начинает работу
- `3` - сервер завершает работу

### Аргументы
- **serverID** (тип `String`) Идентификатор сервера

### Результат
- `Integer`

### Пример
```js
DaemonGetState('EStaff_Server')
```

[On Datex](http://docs.datex.ru/article.htm?id=5620250451197911748)