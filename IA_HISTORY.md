# IA_HISTORY.md — Registro de Uso de IA

**Alumno/a:** <!-- Tu nombre completo -->
**Fecha:** <!-- Fecha del examen, ej: 21/04/2026 -->

---

> **Instrucciones:** Documentar los 2 prompts más importantes que usaste durante el examen.
> Completar **todas** las secciones con criterio propio. No se trata de copiar lo que generó la IA — se evalúa tu capacidad de analizar, detectar errores y tomar decisiones técnicas fundamentadas.
>
> **Mínimo por sección de análisis: 3 oraciones.** Respuestas de una línea no se consideran válidas.

---

> **Ejemplo de análisis insuficiente** ❌
> _"La IA generó el código y funcionó bien."_
>
> **Ejemplo de análisis aceptable** ✅
> _"La IA reemplazó los `<div>` por etiquetas semánticas, pero usó `<section>` para la navegación en lugar de `<nav>`. Lo detecté al revisar la estructura en DevTools. Técnicamente es incorrecto porque `<nav>` tiene un rol ARIA implícito que `<section>` no tiene, así que lo corregí manualmente."_

---

## Prompt 1

### Momento del proceso

```
<!--
  Indicá en qué punto del examen usaste este prompt.
  No es sobre la hora exacta — es sobre el contexto: ¿qué estabas intentando resolver cuando recurriste a la IA?
  Ej: "Cuando no sabía cómo estructurar el layout con Grid."
  Ej: "Al terminar el HTML, para verificar si me faltaba algo de accesibilidad."
  Ej: "Al principio del ejercicio de JS, para entender cómo arrancar."
-->
```

### Lo que le pedí a la IA

```
<!-- Pegá aquí el prompt exacto que escribiste. Debe ser el texto que vos escribiste, no la respuesta. -->
```

### Análisis del resultado obtenido

```
<!--
  Describí con tus propias palabras qué generó la IA. No copies el código ni la respuesta — analizála.
  Mínimo 3 oraciones. Respondé:
  - ¿Qué enfoque tomó la IA para resolver el problema?
  - ¿El resultado era lo que esperabas? ¿Por qué sí o por qué no?
  - ¿Qué parte te resultó útil como punto de partida?
-->
```

### Qué debí corregir manualmente y por qué

```
<!--
  Esta sección es la más importante. Sé específico/a. Mínimo 3 oraciones.
  Respondé:
  - ¿Qué error concreto tenía el resultado? (semántico, de accesibilidad, lógico, de estilo, etc.)
  - ¿Cómo lo detectaste? (al probarlo en el browser, al leer el código, al ver la consola...)
  - ¿Por qué estaba técnicamente incorrecto o insuficiente?
  - ¿Qué cambiaste exactamente para que funcionara bien?
  Si no corregiste nada, explicá por qué el resultado era correcto tal como estaba.
-->
```

---

## Prompt 2

### Momento del proceso

```
<!--
  Indicá en qué punto del examen usaste este prompt.
  No es sobre la hora exacta — es sobre el contexto: ¿qué estabas intentando resolver cuando recurriste a la IA?
  Ej: "Cuando no sabía cómo estructurar el layout con Grid."
  Ej: "Al terminar el HTML, para verificar si me faltaba algo de accesibilidad."
  Ej: "Al principio del ejercicio de JS, para entender cómo arrancar."
-->
```

### Lo que le pedí a la IA

```
<!-- Pegá aquí el prompt exacto que escribiste. Debe ser el texto que vos escribiste, no la respuesta. -->
```

### Análisis del resultado obtenido

```
<!--
  Describí con tus propias palabras qué generó la IA. No copies el código ni la respuesta — analizála.
  Mínimo 3 oraciones. Respondé:
  - ¿Qué enfoque tomó la IA para resolver el problema?
  - ¿El resultado era lo que esperabas? ¿Por qué sí o por qué no?
  - ¿Qué parte te resultó útil como punto de partida?
-->
```

### Qué debí corregir manualmente y por qué

```
<!--
  Esta sección es la más importante. Sé específico/a. Mínimo 3 oraciones.
  Respondé:
  - ¿Qué error concreto tenía el resultado? (semántico, de accesibilidad, lógico, de estilo, etc.)
  - ¿Cómo lo detectaste? (al probarlo en el browser, al leer el código, al ver la consola...)
  - ¿Por qué estaba técnicamente incorrecto o insuficiente?
  - ¿Qué cambiaste exactamente para que funcionara bien?
  Si no corregiste nada, explicá por qué el resultado era correcto tal como estaba.
-->
```

---

## Reflexión final

```
<!--
  Mínimo 3 oraciones. Respondé:
  - ¿Qué tipo de errores repitió la IA que tuviste que corregir?
  - ¿Hubo algo que la IA resolvió bien a la primera sin que necesitaras tocarlo?
  - ¿Cambiarías la forma en que le pedís cosas a la IA la próxima vez? ¿Por qué?
-->
```
## IA_HISTORY.md — Registro de Uso de IA

**Alumno/a:** Irina Dandrea  
**Fecha:** 23/04/2026  

---

## Prompt 1

### Momento del proceso

Cuando estaba corrigiendo la estructura HTML, especialmente al momento de reemplazar los `<div>` por etiquetas semánticas y no sabía exactamente cuáles usar en cada caso.

### Lo que le pedí a la IA

"cómo reemplazar div por etiquetas semánticas en html como header main section footer y nav"

### Análisis del resultado obtenido

La IA propuso reemplazar los `<div>` por etiquetas semánticas como `<header>`, `<main>`, `<section>` y `<footer>`. El enfoque fue correcto en general porque apuntaba a mejorar la estructura del documento y la accesibilidad. Sin embargo, en algunos casos no tuvo en cuenta el contexto específico de cada bloque, como la navegación o listas. Me resultó útil como guía inicial para entender qué etiquetas debía usar.

### Qué debí corregir manualmente y por qué

Tuve que corregir la navegación porque la IA sugería mantener `<div>` en lugar de usar `<nav>` y listas con `<ul>` y `<li>`. Detecté esto al revisar la consigna del examen y notar que pedía específicamente estructuras semánticas correctas. Técnicamente es incorrecto usar `<div>` para navegación porque `<nav>` tiene un significado semántico claro y mejora la accesibilidad. También corregí etiquetas como `<h1>` y `<p>` que inicialmente estaban mal estructuradas o no estaban cerradas correctamente.

---

## Prompt 2

### Momento del proceso

Cuando estaba creando los estilos CSS y necesitaba aplicar layout moderno con Grid y Flexbox según la consigna.

### Lo que le pedí a la IA

"ejemplo de css con grid para layout y flexbox para navbar"

### Análisis del resultado obtenido

La IA generó un ejemplo de CSS utilizando `display: grid` para la estructura principal y `display: flex` para la navegación. El enfoque fue correcto porque respondía directamente a lo pedido en la consigna. El resultado fue útil como base para implementar rápidamente un layout funcional. Sin embargo, algunos valores eran genéricos y no estaban adaptados al diseño específico del proyecto.

### Qué debí corregir manualmente y por qué

Tuve que ajustar colores y algunos tamaños porque la IA no consideraba el contraste requerido por accesibilidad (WCAG). Detecté esto al leer la consigna y ver los comentarios de error en el CSS original. Técnicamente, un contraste bajo dificulta la lectura, por lo que modifiqué colores para mejorar la visibilidad. También adapté las clases a las que ya existían en el HTML para que el CSS funcione correctamente.

---

## Reflexión final

La IA repitió errores relacionados con el uso genérico de etiquetas y no siempre respetó completamente la semántica correcta del HTML. Sin embargo, fue muy útil para dar una base rápida tanto en HTML como en CSS. Me ayudó especialmente a entender cómo estructurar el layout con Grid y Flexbox. La próxima vez intentaría hacer prompts más específicos, indicando mejor el contexto del proyecto, para obtener resultados más precisos desde el principio.