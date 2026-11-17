# Portafolio SmartInventoryIA

Página estática en HTML y CSS, sin JavaScript, frameworks, fuentes externas ni compilación. Compatible con GitHub Pages y apertura local.

## Archivos

- `index.html`: todo el contenido, enlaces, comentarios del docente y versiones. Hay comentarios HTML para localizar secciones y agregar las futuras V2.
- `css/styles.css`: apariencia y adaptación a móvil. Los colores están al inicio, en `:root`.
- `documentos/`: evidencias originales con nombres cortos para los enlaces.

## Abrir

Abre `index.html` en el navegador. Los desplegables usan `<details>` y `<summary>` nativos de HTML. No almacenan comentarios nuevos: muestran la retroalimentación académica ya recibida.

## Editar una entrega

1. Busca su título en `index.html`.
2. Cambia el texto dentro de los párrafos sin borrar las etiquetas.
3. Para añadir una versión, copia un bloque completo `<article class="version">…</article>` dentro del `div` con clase `timeline` de esa sección.
4. Coloca la más reciente primero y conserva la anterior. Cambia etiqueta de versión, fecha, descripción, comentarios y enlaces.
5. Copia el nuevo documento a `documentos/` y utiliza ese nombre en `href="documentos/nombre.pdf"`.
6. Abre la página y comprueba el enlace.

No se ha creado una V2 ficticia. El borrador conceptual está disponible por separado hasta recibir el documento V2. La V2 metodológica se añadirá cuando esté terminada. No confundir una versión disponible con una versión aprobada por el docente.

## Publicar en GitHub Pages

Sube el CONTENIDO de esta carpeta a la raíz del repositorio elegido: `index.html`, `css/`, `documentos/`, `.nojekyll` y este README. No necesitas subir el ZIP.

En GitHub, entra en Settings → Pages, selecciona publicación desde una rama (Deploy from a branch), la rama que contenga los archivos, y la carpeta raíz (`/root`). Guarda. Usa la URL que GitHub muestre cuando termine de publicar.

Los enlaces locales son relativos para funcionar dentro de un repositorio de GitHub Pages. Esta entrega no ha sido subida ni publicada en GitHub.

## Alcance de esta primera versión

Incluye presentación, pregunta y objetivo, antecedentes, cuatro entregas, comentarios resumidos y su seguimiento, borrador conceptual y enlace al prototipo. Las fechas son las de los documentos, salvo aviso. No incluye video final ni resultados predictivos aún no demostrados.

Los documentos se conservan como evidencia: los cambios al portafolio no corrigen los originales. El HTML conceptual adjunto es un archivo autónomo recibido, con su propio código y controles; la página principal del portafolio funciona exclusivamente con HTML y CSS.
