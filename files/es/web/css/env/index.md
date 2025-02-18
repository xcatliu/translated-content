---
title: env()
slug: Web/CSS/env
tags:
  - CSS
  - Experimental
  - Función CSS
  - Variables CSS
  - env
  - env()
translation_of: Web/CSS/env()
original_slug: Web/CSS/env()
---
La función [CSS](/es/docs/Web/CSS) **`env()`** puede ser utilizada para insertar el valor de una variable de entorno, que sea global para un documento en particular, al contrario de una [propiedad personalizada](/es/docs/Web/CSS/--_). Entonces, la funcion env() puede ser utilizada para remplazar el valor en ubicaciones arbitrarias, de la misma manera que la función [var()](/es/docs/Web/CSS/var).

La función env() puede ser utilizada en el lugar de cualquier parte de un valor en cualquier propiedad de cualquier elemento, o de cualquier parte de un valor en cualquier descriptor de cualquier regla @, y en varios otros lugares donde los valores CSS están permitidos.

Las Variables de Entorno CSS están actualmente en curso de definición en un borrador de Recomendación: [CSS Environment Variables Module Level 1](https://drafts.csswg.org/css-env-1/).

## Compatibilidad con navegadores

{{Compat("css.properties.custom-property.env")}}
