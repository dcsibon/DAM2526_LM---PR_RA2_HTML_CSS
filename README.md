# **PRUEBA INDIVIDUAL – RA2 - HTML+CSS**

Durante esta sesión tendrás que realizar **tres ejercicios prácticos** y elaborar un **informe de evidencias**, donde deberás demostrar que comprendes lo que has construido en la Práctica 8.

Puedes consultar tu código y realizar cambios directamente en tu proyecto para hacer las pruebas que necesites.

---

## ✅ **Ejercicio 1**

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
.site-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

h1 {
  text-align: center;
}
```

### **1A. Pregunta**

**¿Por qué NO se centra el texto del `<h1>` en este caso? Explícalo con tus palabras.**
(por qué visual y estructuralmente no aparece centrado entre el borde izquierdo y el menú)

---

### **1B. Ejercicio - Soluciona de dos formas diferentes**

**Debes indicar dos formas diferentes de conseguir que el `h1` si quede centrado visualmente en la cabecera.**

⚠️ **IMPORTANTE**:

* Una solución usando Flexbox
* Otra usando CSS Grid

En cada caso debes escribir:

* Una breve explicación de la idea,
* El CSS necesario para lograr el centrado.

---

### **1C. Ejercicio – Convertir la cabecera en dos filas**

Sin modificar el HTML, debes conseguir mediante CSS que la cabecera se reorganice de la siguiente forma:

* En la **primera fila** se muestra solo el `<h1>`, centrado horizontalmente.
* En la **segunda fila** se muestra el menú de navegación (`<nav class="main-nav">`), también centrado horizontalmente.
* Ambos elementos forman parte del **mismo header**, solo cambia la distribución.
* Entre la fila del `h1` y la fila del menú debe haber exactamente 30px de separación vertical *(No puedes añadir etiquetas nuevas en el HTML. Solo se permite modificar el CSS)*

Escribe el **CSS necesario** para conseguir esa estructura.

---

### **1D. Ejercicio – Dar relieve y separación visual al header**

Se pretende que la cabecera del sitio (`.site-header`) tenga un aspecto más definido y se diferencie claramente del resto de la página.

Debes conseguir, únicamente con CSS, que:

* La cabecera tenga un **color de fondo** distinto al del resto de la página.
* Haya una **separación visual clara** con el contenido que va debajo (por ejemplo, usando un borde inferior y una sombra).
* El contenido del header tenga un **espaciado interior** adecuado para que no quede “pegado” a los bordes.

Escribe las reglas CSS que aplicarías a `.site-header` para lograr ese efecto.

---

## ✅ **Ejercicio 2 — Reorganización del header con tres elementos**

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
✧ Grid (opcional, pero lo valoraré positivamente si conoces cómo hacerlo)

---

## ✅ **Ejercicio 3 — Miniaturas, zoom y enlace a la imagen original**

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

## ✅ **Ejercicio 4 — Informe de evidencias del proyecto (defensa técnica simple)**

Debes elaborar un **documento PDF** o **Markdown** donde expliques y muestres capturas de tu propia web.

Este informe debe incluir:

---

### **4.1. Introducción**

Explica en 4–6 líneas:

* el tema de tu web,
* qué contenido has incluido,
* cuál era tu idea de diseño.

---

### **4.2. Evidencias de HTML5**

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

### **4.3. Evidencias de CSS**

Incluye ejemplos de código mostrando:

* selectores utilizados (tipo, clase, id, descendente…).
* pseudoclases.
* Flexbox o Grid en alguna parte.
* uso de sombras (`box-shadow`) o cards.
* estilos de tus menús.

Explica qué has intentado conseguir con ese diseño.

---

### **4.4. Fuentes utilizadas**

Debes explicar:

* qué fuente local has incluido (`@font-face`)
* qué fuente online has añadido (Google Fonts)
* por qué te han gustado esas tipografías

Incluye fragmentos de código.

---

### **4.5. Menú lateral: breve explicación**

No tienes que explicar JavaScript en detalle.
Solo:

* qué ocurre al pulsar el botón,
* qué clase cambia,
* cómo se mueve el menú con CSS.

---

### **4.6. Conclusión personal**

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
