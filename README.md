# 📝 Editor Markdown en Vivo

Este proyecto es un **Editor Markdown en Vivo** que permite al usuario escribir texto con sintaxis Markdown, generar una vista previa en HTML y aplicar estilos dinámicos a los encabezados. Además, incluye un contador de palabras y caracteres en tiempo real.

---

## 🧠 Paradigma de Programación

El enfoque principal de este proyecto es la **programación imperativa y manipulativa del DOM** mediante JavaScript. Las interacciones se realizan directamente con elementos HTML usando métodos como:

- `getElementById()` para seleccionar nodos.
- `addEventListener()` para manejar eventos.
- `innerHTML` para actualizar contenido.
- `querySelectorAll()` para manipular múltiples elementos.
- Uso de una **librería externa (`marked`)** para convertir Markdown a HTML.

Esto permite un flujo de trabajo donde el **usuario interactúa con el DOM** y los cambios se reflejan dinámicamente sin recargar la página.

---

## ✅ Historias de Usuario

- ✅ **Como usuario**, quiero escribir texto Markdown en un textarea, para generar contenido estructurado.
- ✅ **Como usuario**, quiero ver una vista previa de mi Markdown convertido a HTML con un solo clic.
- ✅ **Como usuario**, quiero aplicar un estilo de contraste a los encabezados de la vista previa, para distinguir mejor los títulos.
- ✅ **Como usuario**, quiero ver un contador de palabras y caracteres mientras escribo, para llevar control de mi contenido.
- ✅ **Como usuario**, quiero una interfaz clara, responsiva y amigable, para poder trabajar desde distintos dispositivos.

---

## 📌 Conclusión

Este proyecto pone en práctica habilidades fundamentales de JavaScript moderno, centradas en la **manipulación del DOM** y el uso de **eventos** para crear una experiencia interactiva. Se integran conceptos de diseño responsivo, separación de responsabilidades (HTML + CSS + JS) y uso de librerías externas. El resultado es una herramienta funcional que permite comprender el flujo entre entrada, procesamiento y salida en una aplicación web real.

---

🎯 _Desarrollado como parte del Módulo 3: JavaScript y DOM._
