---
title: <details>
slug: Web/HTML/Element/details
tags:
  - Elemento
  - Elementos HTML interactivos
  - HTML
  - HTML5
  - Referencia
  - Web
translation_of: Web/HTML/Element/details
original_slug: Web/HTML/Elemento/details
---
{{ SeeCompatTable() }}

## Resumen

El elemento HTML Details **\<details>** es usado como un widget de revelación a través del cual el usuario puede obtener información adicional .

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">
        <a href="/es/docs/Web/Guide/HTML/categorias_de_contenido"
          >Categorías de contenido</a
        >
      </th>
      <td>
        <a href="/es/docs/Web/Guide/HTML/categorias_de_contenido"
          >Contenido dinámico</a
        >
        , contenido de seccionamiento, contenido interactivo, contenido palpable
        .
      </td>
    </tr>
    <tr>
      <th scope="row">Contenido permitido</th>
      <td>
        Un elemento {{HTMLElement("summary")}} seguido de
        <a href="/es/docs/Web/Guide/HTML/categorias_de_contenido"
          >contenido dinámico</a
        >
      </td>
    </tr>
    <tr>
      <th scope="row">Omisión de etiquetas</th>
      <td>{{no_tag_omission}}</td>
    </tr>
    <tr>
      <th scope="row">Elementos padres permitidos</th>
      <td>
        Cualquier elemento que acepte
        <a href="/es/docs/Web/Guide/HTML/categorias_de_contenido"
          >contenido dinámico</a
        >.
      </td>
    </tr>
    <tr>
      <th scope="row">Interfaz DOM</th>
      <td>{{domxref("HTMLDetailsElement")}}</td>
    </tr>
  </tbody>
</table>

## Atributos

Este elemento incluye los [atributos globales](/es/docs/Web/HTML/Atributos_Globales) .

- {{htmlattrdef("open")}}
  - : Este atributo Booleano indica si los detalles serán mostrados al usuario cuando la página se cargue . Por default el valor es `false` y por lo tanto los detalles estarán ocultos.

## Ejemplo

```html
<details>
  <summary>Some details</summary>
  <p>More info about the details.</p>
</details>
```

### Resultado

{{EmbedLiveSample("Example")}}

> **Nota:** Si el el ejemplo de arriba no funciona , ver [Compatibilidad con navegadores](#compatibilidad_con_navegadores) para determinar si el navegador soporta esta característica .

## Especificaciones

| Especificaciones                                                                                                                 | Estatus                          | Comentario |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- | ---------- |
| {{SpecName('HTML WHATWG', 'interactive-elements.html#the-details-element', '&lt;details&gt;')}} | {{Spec2('HTML WHATWG')}} |            |
| {{SpecName('HTML5.1', 'semantics.html#the-details-element', '&lt;details&gt;')}}                     | {{Spec2('HTML5.1')}}     |            |

## Compatibilidad con navegadores

{{Compat("html.elements.details")}}

## Ver también

- {{HTMLElement("summary")}}

{{HTMLRef}}
