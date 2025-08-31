# Taller introductorio de HTML, CSS y JavaScript

## 1. ¿Qué es HTML y cuál es su función en la web?
HTML (HyperText Markup Language) es el lenguaje estándar para crear páginas web. Su función es estructurar el contenido en elementos como títulos, párrafos, imágenes, enlaces y tablas, permitiendo que los navegadores lo interpreten y muestren correctamente.

---

## 2. ¿Qué es una etiqueta HTML y menciona las etiquetas más comunes?
Una etiqueta HTML es un elemento que define cómo se organiza el contenido en una página. Generalmente se escriben con apertura `<etiqueta>` y cierre `</etiqueta>`.  
**Etiquetas comunes:** `<html>`, `<head>`, `<body>`, `<h1>...<h6>`, `<p>`, `<a>`, `<img>`, `<div>`, `<span>`.

---

## 3. ¿Qué es un atributo de una etiqueta HTML y menciona los más comunes?
Los atributos son características adicionales que se agregan a las etiquetas para definir propiedades o comportamientos. Se escriben dentro de la etiqueta de apertura.  
**Ejemplos:**  
- `id`: identifica un elemento de forma única.  
- `class`: agrupa elementos para aplicar estilos.  
- `src`: indica la ubicación de una imagen o recurso.  
- `href`: define el destino de un enlace.  
- `alt`: describe una imagen.  


## 4. ¿Qué es CSS y cómo se utiliza para el diseño web?
CSS (Cascading Style Sheets) es el lenguaje que da presentación y estilo a los documentos HTML. Permite cambiar colores, fuentes, márgenes, tamaños, posiciones y adaptar el diseño para distintos dispositivos. Se puede aplicar en línea, en el mismo archivo HTML o en un archivo externo.

---

## 5. ¿Qué es una propiedad en CSS y menciona las propiedades más comunes?
Una propiedad en CSS es una característica que define cómo se verá un elemento HTML. Siempre tiene un nombre y un valor.  
**Ejemplos comunes:**  
- `color`: cambia el color del texto.  
- `background-color`: color de fondo.  
- `font-size`: tamaño de la letra.  
- `margin`: espacio externo del elemento.  
- `padding`: espacio interno.  
- `border`: define un borde.  

---

## 6. ¿Qué es un selector en CSS y cuáles tipos existen?
Un selector es lo que indica a qué elementos HTML se aplicarán los estilos en CSS.  
**Tipos de selectores:**  
- Por etiqueta: `p { }`  
- Por clase: `.miClase { }`  
- Por id: `#miId { }`  
- Universal: `* { }`  
- Combinadores: `div p { }`  

---

## 7. ¿Qué es JavaScript y cómo añade la interactividad a las páginas web?
JavaScript es un lenguaje de programación que permite añadir interactividad a las páginas web. Gracias a JS se pueden validar formularios, crear animaciones, actualizar contenido sin recargar la página y responder a las acciones del usuario como clics o movimientos del ratón.

## 8. ¿Cuáles son los tipos de datos primitivos en JavaScript?
JavaScript tiene varios tipos básicos de datos llamados primitivos:  
- `string`: cadenas de texto.  
- `number`: números enteros o decimales.  
- `boolean`: verdadero o falso.  
- `null`: ausencia de valor.  
- `undefined`: variable sin valor asignado.  
- `symbol`: identificadores únicos.  
- `bigint`: números muy grandes.  

---

## 9. ¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en JavaScript?
Las estructuras de control permiten decidir o repetir acciones en el programa.  
- **if/else:** ejecutan bloques de código según una condición.  
- **switch:** permite elegir entre múltiples casos.  
- **for y while:** repiten instrucciones mientras se cumpla una condición.  

Ejemplo:
```js
if (edad >= 18) {
  console.log("Eres mayor de edad");
} else {
  console.log("Eres menor de edad");
}
```

---

## 10. ¿Por qué es importante usar nombres significativos para variables y métodos?
Porque mejora la claridad del código, facilita su mantenimiento y permite que otros desarrolladores (o el propio autor en el futuro) entiendan rápidamente qué hace cada parte del programa.

---

## 11. ¿Qué es una variable de entorno y por qué son importantes?
Son valores externos que configuran el comportamiento de un programa (como contraseñas, URLs o claves de API). Son importantes porque ayudan a separar la configuración del código, aumentan la seguridad y permiten usar diferentes configuraciones en desarrollo, pruebas o producción.

---

## 12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?
Son un conjunto de utilidades integradas en el navegador para inspeccionar, depurar y optimizar páginas web.  
Se accede con **F12** o **Ctrl+Shift+I** (Windows/Linux) o **Cmd+Option+I** (Mac).

---

## 13. ¿Qué se puede hacer en el panel "Elements"?
Permite ver y modificar el **HTML y CSS** en tiempo real, inspeccionar la estructura del DOM y probar cambios de estilo sin modificar el archivo original.

---

## 14. ¿Cómo se utiliza el panel "Console" y para qué es útil?
La consola sirve para:  
- Ejecutar comandos **JavaScript**.  
- Mostrar mensajes de depuración con `console.log`.  
- Revisar errores en el código de forma inmediata.  

---

## 15. ¿Qué información se puede obtener del panel "Network" y por qué es importante?
Muestra todas las peticiones que realiza la página (**imágenes, scripts, CSS, APIs**), su tiempo de carga y si hubo errores.  
Es útil para **optimizar el rendimiento** y entender cómo se comunica la página con los servidores.
