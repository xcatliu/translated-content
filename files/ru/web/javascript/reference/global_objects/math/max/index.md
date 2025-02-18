---
title: Math.max()
slug: Web/JavaScript/Reference/Global_Objects/Math/max
tags:
  - JavaScript
  - Math
  - Method
  - Reference
translation_of: Web/JavaScript/Reference/Global_Objects/Math/max
---
{{JSRef("Global_Objects", "Math")}}

## Сводка

Метод **`Math.max()`** возвращает наибольшее из нуля или более чисел.

## Синтаксис

```
Math.max([value1[, value2[, ...]]])
```

### Параметры

- `value1, value2, ...`
  - : Числа.

## Описание

Поскольку метод `max()` является статическим методом объекта `Math`, вы всегда должны использовать его как `Math.max()`, а не пытаться вызывать метод на созданном экземпляре объекта `Math` (поскольку объект `Math` не является конструктором).

При вызове без аргументов результатом вызова будет значение -{{jsxref("Global_Objects/Infinity", "Infinity")}}.

Если хотя бы один из аргументов не может быть преобразован в число, результатом будет {{jsxref("Global_Objects/NaN", "NaN")}}.

## Примеры

### Пример: использование метода `Math.max()`

```js
Math.max(10, 20);   //  20
Math.max(-10, -20); // -10
Math.max(-10, 20);  //  20
```

#### Нахождение максимального элемента в массиве

Следующая функция использует метод {{jsxref("Function.prototype.apply()")}} для нахождения максимального элемента в числовом массиве. Вызов `getMaxOfArray([1, 2, 3])` эквивалентен вызову `Math.max(1, 2, 3)`, однако вы можете использовать функцию `getMaxOfArray()` вместе с программно сконструированными массивами любого размера. Рекомендуется использовать только в случае обработки массивов с небольшим количеством элементов.

```js
function getMaxOfArray(numArray) {
  return Math.max.apply(null, numArray);
}
```

## Спецификации

{{Specifications}}

## Совместимость с браузерами

{{Compat}}

## Смотрите также

- {{jsxref("Math.min()")}}
