Узкоспециализированная функция. Работает аналогично [Sleep()](http://docs.datex.ru/article.htm?id=5620276892448878769), но с продолжением обработки очереди сообщений в главном потоке в SpXml.exe. Если вызвана не в главном потоке или не в SpXml.exe, работает так же, как и Sleep().

### Аргументы
- **timeout** (тип `Integer`)  
    Таймаут в миллисекундах.

[On Datex](http://docs.datex.ru/article.htm?id=7172076235998782760)