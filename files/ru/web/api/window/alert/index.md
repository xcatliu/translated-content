---
title: Window.alert()
slug: Web/API/Window/alert
translation_of: Web/API/Window/alert
---
{{ APIRef }}

Метод **`Window.alert()`** показывает диалоговое окно с опциональным (необязательным) сообщением и кнопкой OK.

## Синтаксис

```
window.alert(message);
```

- `message` это опциональная (необязательная) строка текста, которую вы хотите отобразить в диалоговом окне, или же объект, который будет преобразован в строку и отображён.

## Пример

```js
window.alert("Hello world!");
```

покажет:

![Image:AlertHelloWorld.png](/files/130/AlertHelloWorld.png)

## Больше JS

```js
alert();
```

## Примечания

Этот диалог следует использовать для сообщений, которые не требуют никакого ответа от пользователя, кроме подтверждения самого сообщения.

Окна сообщений - модальные, они препятствуют получению пользователем доступа к другим частям страницы до тех пор, пока окно не будет закрыто. По этой причине, вам не следует злоупотреблять этой функцией.

The following text is shared between this article, DOM:window\.prompt and DOM:window\.confirm Пользователи [Mozilla Chrome](/en-US/Chrome) (например, расширения для Firefox) должны использовать метод `nsIPromptService`.

Начиная с Chrome {{CompatChrome(46.0)}} этот метод заблокирован в {{htmlelement("iframe")}} пока атрибут sandbox не установлен в значение `allow-modal`.

{{gecko_minversion_inline("23.0")}} Аргумент является опциональным и необязательным согласно спецификации.

## Спецификации

| Спецификация                                                                                                 | Статус                           | Комментарий |
| ------------------------------------------------------------------------------------------------------------ | -------------------------------- | ----------- |
| {{SpecName('HTML WHATWG', 'timers-and-user-prompts.html#dom-alert', 'alert()')}} | {{Spec2('HTML WHATWG')}} |             |

## Совместимость с браузерами

{{Compat}}

## Смотрите также

- Элемент {{HTMLElement("dialog")}}
- {{domxref("window.confirm","confirm")}}
- {{domxref("window.prompt","prompt")}}
