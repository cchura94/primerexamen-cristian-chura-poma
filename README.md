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

## SEO

- Definí un `<title>` único y descriptivo: "MANACO - Calzado que impulsa tu paso".
- Añadí una meta descripción de 156 caracteres para mejorar la indexación y mostrar un texto atractivo en buscadores.
- Incorporé etiquetas Open Graph (og:title, og:description, og:image, og:type, og:url) para mejorar la visualización en redes sociales.
- Mantengo la jerarquía correcta de encabezados (un solo H1, luego H2 para secciones).
- Usé un placeholder de imagen en OG hasta que la empresa defina una imagen oficial.