# Отчёт по лабораторной работе №2 (Node-RED)

**ФИО:** Горбунов Кирилл  
**Группа:** УИР-241

## Способ установки

Node-RED установлен через npm (без Docker).

- Node.js: v24.21.0
- Node-RED: v5.0.8

## Освоенные ноды

inject, debug, function, switch, change, template, http request, mqtt in/out, http in/response, ui_gauge, ui_chart, telegram receiver/sender/command, file in/out, flow context.

## Использованные AI-промпты

1. «Сгенерируй JS-код для function node с let/const, if/else, циклом for, массивом и объектом»
2. «Составь Mustache-шаблон для JSON с полями name, lab, group»
3. «Настрой MQTT flow с публичным брокером broker.hivemq.com»

## Скриншоты

### 1. Версии Node.js и npm

![Версии Node.js и npm](../screenshots/00-node-npm-version.png)

### 2. Версии Node-RED и Node.js

![Версии Node-RED](../screenshots/01-nodered-versions.png)

### 3. Inject → Debug

![Inject Debug](../screenshots/01-inject-debug.png)

### 4. Function node

![Function](../screenshots/02-function.png)

### 5. Switch node

![Switch](../screenshots/03-switch.png)

### 6. Change node

![Change](../screenshots/04-change.png)

### 7. Template node

![Template](../screenshots/05-template.png)

### 8. HTTP Request

![HTTP Request](../screenshots/06-http-request.png)

### 9. MQTT

![MQTT](../screenshots/07-mqtt.png)

### 10. GET-эндпоинты

![API Text](../screenshots/08a-endpoints-text.png)
![API Info](../screenshots/08b-endpoints-info.png)
![API Success](../screenshots/08c-endpoints-success.png)
![API 404](../screenshots/08d-endpoints-404.png)

### 11. Dashboard

![Dashboard](../screenshots/09-dashboard.png)

### 12. Telegram-бот

![Telegram](../screenshots/10-telegram.png)

### 13. Файлы

![Files](../screenshots/11-files.png)

### 14. Контекст

![Context](../screenshots/12-context.png)

## Выводы

В ходе работы я освоил Node-RED как low-code инструмент. Научился собирать потоки из готовых нод, работать с function-нодами (JavaScript), настраивать HTTP-эндпоинты, MQTT, Telegram-бота и dashboard. Понял, как работает контекст (flow context) для хранения состояния между сообщениями. Установка через npm дала больше контроля над версиями, чем Docker.