\# API Documentation



\## GET /api/text

Возвращает простой текст.

Пример: http://localhost:1880/api/text

Ответ: `Это простой текстовый ответ от Node-RED.`



\## GET /api/info

Возвращает JSON с двумя полями.

Пример: http://localhost:1880/api/info

Ответ: `{"status":"ok","author":"Горбунов Кирилл","group":"УИР-241"}`



\## GET /api/items/:id

Возвращает объект по id.

\- Успех: http://localhost:1880/api/items/1 → `{"id":1,"name":"Item One","author":"Горбунов"}`

\- Ошибка: http://localhost:1880/api/items/999 → 404 `{"error":"Not found","id":"999"}`

