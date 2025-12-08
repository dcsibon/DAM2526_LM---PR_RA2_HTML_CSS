# **PRUEBA INDIVIDUAL – RA2 - HTML+CSS (Preguntas prácticas + Defensa de tu proyecto web)**

Durante esta sesión tendrás que realizar **tres ejercicios prácticos** y elaborar un **informe de evidencias**, donde deberás demostrar que comprendes lo que has construido en la Práctica 8.

Puedes consultar tu código y realizar cambios directamente en tu proyecto para hacer las pruebas que necesites.

---

# ✅ **Ejercicio 1**

Observa este HTML y CSS:

```html
<header class="site-header">
  <h1>Mi Sitio Web</h1>

  <nav class="main-nav">
      ...
  </nav>
</header>
```

```css
h1 {
  text-align: center;
}
```

### **1A. Pregunta**

**¿Por qué NO se centra el texto del `<h1>` en este caso? Explícalo con tus palabras.**

---

### **1B. Ejercicio**

**Indica cómo podrías centrar el contenido de `<h1>` de dos formas diferentes**.

Debes escribir el CSS necesario.

---

### **1C. Ejercicio**

Ahora quiero que **el `<h1>` y el menú de navegación estén en la misma línea**, y que **el texto del `<h1>` quede centrado en el espacio que le toca entre el borde izquierdo del header y el menú**.

Representación aproximada:

```
|            h1             ||    nav    |
```

Indica:

1. Cómo lo harías con **Flexbox**
2. Opcional: cómo lo harías con **Grid (muy sencillo)**

Debes escribir el CSS necesario.

---

# ✅ **Ejercicio 2 — Reorganización del header con tres elementos**

Ahora debes incluir **también el botón del menú lateral** dentro del `<header>`.

El objetivo es que la cabecera quede así:

```
| btn |         h1          |   nav   |
```

Donde:

* El **botón** está alineado a la izquierda.
* El **h1** está **centrado** entre el botón y el menú.
* El **nav** está alineado a la derecha.

### **2A. Ejercicio**

Cambia tu HTML para introducir el botón dentro de `header`.

### **2B. Ejercicio**

Indica el CSS necesario para maquetar este diseño usando:

✔ **Flexbox** (obligatorio)
✧ Grid (opcional, si conoces cómo hacerlo)

---

# ✅ **Ejercicio 3 — Miniaturas, zoom y enlace a la imagen original**

En tu **galería de imágenes**, debes realizar lo siguiente:

### **3A. Crear miniaturas**

Genera nuevas imágenes pequeñas (por ejemplo 200px de ancho aprox.).
Debes reemplazar las imágenes de la galería por estas miniaturas.

### **3B. Efecto hover**

Al pasar el ratón por encima:

* debe haber **zoom suave** (por ejemplo usando `transform: scale(1.1);`)
* debe aparecer un **marco**, sombra o borde (elige tú el estilo)

### **3C. Enlace a la imagen original**

Al hacer clic en la miniatura, la imagen original (de mayor tamaño) debe abrirse en **otra pestaña**.

Tu tarea consiste en:

* escribir el HTML corregido,
* escribir el CSS que genera el zoom + marco,
* incluir una captura en tu informe de evidencias mostrando el resultado.

---

# ✅ **Ejercicio 4 — Informe de evidencias del proyecto (defensa técnica simple)**

Debes elaborar un **documento PDF** o **Markdown** donde expliques y muestres capturas de tu propia web.

Este informe debe incluir:

---

## **4.1. Introducción**

Explica en 4–6 líneas:

* el tema de tu web,
* qué contenido has incluido,
* cuál era tu idea de diseño.

---

## **4.2. Evidencias de HTML5**

Incluye capturas y explicaciones breves del uso de:

* `header`, `main`, `section`, `footer`
* el menú superior
* el menú lateral ☰
* la sección Hero
* la tabla
* el formulario
* la galería de imágenes
* enlaces internos y externos

---

## **4.3. Evidencias de CSS**

Incluye ejemplos de código mostrando:

* selectores utilizados (tipo, clase, id, descendente…)
* pseudoclases como `:hover`
* Flexbox o Grid en alguna parte
* uso de sombras (`box-shadow`) o cards
* estilos de tus menús

Explica qué has intentado conseguir con ese diseño.

---

## **4.4. Fuentes utilizadas**

Debes explicar:

* qué fuente local has incluido (`@font-face`)
* qué fuente online has añadido (Google Fonts)
* por qué te han gustado esas tipografías

Incluye fragmentos de código.

---

## **4.5. Menú lateral: breve explicación**

No tienes que explicar JavaScript en detalle.
Solo:

* qué ocurre al pulsar el botón,
* qué clase cambia,
* cómo se mueve el menú con CSS.

Ejemplo válido:

> “El botón añade la clase `.active` al menú. Con CSS el menú pasa de `left: -230px` a `left: 0`, por eso se desliza.”

---

## **4.6. Conclusión personal**

Explica:

* qué has aprendido,
* qué te gustaría mejorar,
* qué ha sido lo que más te ha costado,
* qué parte de tu web te gusta más.

---

## **Entrega**

Enlace al README de un repositorio de GitHub dónde lo contestes y expliques todo.

* **IMPORTANTE!!** Antes de las 14:40 debes entregar el enlace como mínimo con un COMMIT con el documento bastante avanzado.
* La entrega final de esta prueba la podrás realizar el jueves, dónde tendrás 1h más para agregar contenido al README que entregarás *(PERO NO MODIFICAR, NI CORREGIR LO REALIZADO EN EL DÍA DE HOY)*

---
