---
title: border-block-end-color
slug: Web/CSS/border-block-end-color
tags:
  - CSS
  - Experimental
  - Propiedad CSS
  - Propiedad Lógica CSS
  - Referencia
translation_of: Web/CSS/border-block-end-color
---
{{CSSRef}}{{SeeCompatTable}}

La propiedad [CSS](/es/docs/Web/CSS) `border-block-end-color` define el color del borde del final lógico de un elemento, que se mapea a un color de borde físico, dependiendo el modo de escritura, direccionalidad y orientación de texto del elemento. Corresponde a las propiedades {{cssxref("border-top-color")}}, {{cssxref("border-right-color")}}, {{cssxref("border-bottom-color")}}, o {{cssxref("border-left-color")}}, dependiendo de los valores definidos para {{cssxref("writing-mode")}}, {{cssxref("direction")}}, y {{cssxref("text-orientation")}}.

```css
border-block-end-color: yellow;
border-block-end-color: #F5F6F7;
```

Está relacionada con {{cssxref("border-block-start-color")}}, {{cssxref("border-inline-start-color")}}, y {{cssxref("border-inline-end-color")}}, que definen las otras propiedades de color de borde del elemento.

{{cssinfo}}

## Sintaxis

### Valores

- `<'border-color'>`
  - : Véase {{ cssxref("border-color") }}

### Sintaxis formal

{{csssyntax}}

## Ejemplo

### Contenido HTML

```html
<div>
  <p class="exampleText">Texto de ejemplo</p>
</div>
```

### Contenido CSS

```css
div {
  background-color: yellow;
  width: 120px;
  height: 120px;
}

.exampleText {
  writing-mode: vertical-lr;
  border: 10px solid blue;
  border-block-end-color: red;
}
```

{{EmbedLiveSample("Ejemplo", 140, 140)}}

## Especificación

| Especificación                                                                                                                       | Estado                                           | Comentarios        |
| ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------ | ------------------ |
| {{SpecName("CSS Logical Properties", "#propdef-border-block-end-color", "border-block-end-color")}} | {{Spec2("CSS Logical Properties")}} | Definición inicial |

## Compatibilidad en navegadores

{{Compat("css.properties.border-block-end-color")}}

## Mira también

- Las propiedades físicas mapeadas: {{cssxref("border-top-color")}}, {{cssxref("border-right-color")}}, {{cssxref("border-bottom-color")}}, y {{cssxref("border-left-color")}}
- {{cssxref("writing-mode")}}, {{cssxref("direction")}}, {{cssxref("text-orientation")}}+ bug 1297097
