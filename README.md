# react_task1_ex1_work

> цитата

Заголовок таблицы1 | Заголовок таблицы2
-------------------|-------------------
текст1             | текст2


```plantuml
@startuml
[/src] --> [/static/js/main.chunk.js]
[/node_modules] --> [/static/js/vendors~main.chunk.js]
[/public/favicon.ico] --> [/favicon.ico]
[/public/manifest.json] --> [/manifest.json]
[/manifest.json] --> [index.html]
[/public/index.html] --> [index.html]
[/favicon.ico] --> [index.html]
[/static/js/main.chunk.js] --> [index.html]
[/static/js/vendors~main.chunk.js] --> [index.html]
[/bundle.js] -l-> [index.html]
@enduml
```