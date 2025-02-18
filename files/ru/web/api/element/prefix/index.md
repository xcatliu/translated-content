---
title: Node.prefix
slug: Web/API/Element/prefix
translation_of: Web/API/Node/prefix
original_slug: Web/API/Node/prefix
---
{{APIRef("DOM")}}

Свойство **`Node.prefix`** только для чтения, возвращающее префикс пространства имён указанного узла или `null,` если не указан префикс. Это свойство только для чтения.

## Синтаксис

```
string = element.prefix
```

## Пример

Следующее выражение выведет "x".

```xml
<x:div onclick="alert(this.prefix)"/>
```

## Примечание

Это будет работать только когда используется соответствующий парсер пространства имен. т.е. когда документ обработан как XML mime-type. Это не будет работать для документов HTML.

## Спецификация

- [Node.prefix](http://www.w3.org/TR/2000/REC-DOM-Level-2-Core-20001113/core.html#ID-NodeNSPrefix) (введено в употребление в DOM2)

## Совместимость с браузерами

{{Compat}}
