Проверяет, не нажата ли какая-либо клавиша в данный момент. Обычно проверяются Ctrl или Shift.

### Синтаксис
`IsKeyPressed(arg1)`

### Аргументы
- **arg1** (`Integer`): Код клавиши, состояние которой нужно проверить.

### Результат
- **Boolean**: Возвращает `true`, если указанная клавиша нажата, и `false` в противном случае.

### Пример
```js
if (IsKeyPressed(17)) {     
 // Код для выполнения, если Ctrl нажата 
}
```

[On Datex](http://docs.datex.ru/article.htm?id=5665465792879477138)