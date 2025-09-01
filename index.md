---
dg-publish: true
dg-home: true
tags:
---

Здесь **база знаний** от чата телеграма  [@Flutterflow_rus](https://t.me/flutterflow_rus) 

[[Общая информация о Базе знаний]]
[Официальная документация](https://docs.flutterflow.io/)

```dataview
TABLE WITHOUT ID file.link AS "Заметки",
dateformat(file.mtime, "dd.MM.yyyy") AS "Последнее посещение" 
FROM "" // из хранилища `FlutterFlow база знаний`
WHERE file.name != "index" // За последние 7 дней, исключая Homepage
SORT file.mtime DESCLIMIT 5 // последние 5 заметок
```