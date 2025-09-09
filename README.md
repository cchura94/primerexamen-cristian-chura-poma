# Primer examen parcial - Tecnologías de Internet

**Alumno:** Cristian Chura Poma
**Proyecto:** Landing MANACO

Breve descripción:
Desarrollo de una landing page responsive y accesible para la empresa MANACO. 
El objetivo es replicar exactamente la imagen entregada, aplicando HTML5 semántico, accesibilidad y SEO.

## Accesibilidad (a11y)

- Añadí un enlace "Saltar al contenido" para permitir acceder directamente al contenido principal usando teclado.
- Implementé `:focus-visible` para que elementos focuseables tengan un indicador de foco claro al navegar con teclado.
- Uso de elementos semánticos (header, nav, main, section, article, footer) y `aria-label`/`aria-labelledby` donde corresponde.
- Las imágenes ficticias están representadas con `<figure role="img" aria-label="...">` para describir las imágenes sin usar archivos.
- Probé la navegación por teclado (Tab / Shift+Tab) para verificar el orden lógico de focos.
