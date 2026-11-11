# Отчёт по лабораторной работе №4 (n8n)

**ФИО:** Горбунов Кирилл
**Группа:** УИР-241

## 1. Краткое описание
Установлен n8n через Docker. Созданы 6 базовых workflow, настроен Redis и выполнены операции создания, чтения и удаления ключа.

## 2. Использованные AI-промпты
- «Сгенерируй workflow n8n с Manual Trigger, Set и Code node»
- «Настрой Redis credentials для n8n в Docker»
- «Создай workflow для HTTP Request к catfact.ninja»

## 3. Освоенные ноды
Manual Trigger, Set, Code, NoOp, IF, HTTP Request, Schedule Trigger, Redis.

## 4. Скриншоты

### Версия n8n
![01-version](../screenshots/01-version.png)

### 2.1 Manual Set
![02-manual-set](../screenshots/02-manual-set.png)

### 2.2 Code
![03-code](../screenshots/03-code.png)

### 2.3 IF
![04-if](../screenshots/04-if.png)

### 2.4 Set
![05-set-code](../screenshots/05-set-code.png)

### 2.5 HTTP Request
![06-http-request](../screenshots/06-http-request.png)

### 2.6 Schedule
![07-schedule](../screenshots/07-schedule.png)

### Redis Set
![08-redis-set](../screenshots/08-redis-set.png)

### Redis Delete
![09-redis-delete](../screenshots/09-redis-delete.png)

## 5. Выводы
В ходе работы освоена платформа n8n как low-code инструмент автоматизации. Настроено взаимодействие с Redis, выполнены базовые и продвинутые сценарии. Установка через Docker обеспечивает изоляцию и удобство развёртывания.