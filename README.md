# Portafolio SmartInventoryIA

Abre `index.html` en un navegador. El portafolio usa HTML y CSS estáticos. Las fuentes Inter y Plus Jakarta Sans se cargan desde Google Fonts cuando hay conexión.

- `index.html` presenta el proyecto.
- `paginas/` contiene los dos semestres y el prototipo.
- `css/styles.css` contiene los estilos compartidos.
- `assets/` conserva el logo y los iconos.
- `documentos/` contiene las evidencias académicas originales. El borrador conceptual es un HTML autónomo con sus propios controles.

## Añadir una versión

Edita la sección correspondiente en `paginas/ctei-2.html`. Inserta un bloque `article.version` al principio de su línea de tiempo y conserva las entregas anteriores. Incluye la etiqueta, la fecha del documento, su estado, la descripción y los enlaces con rutas como `../documentos/nombre.pdf`. Usa `details` y `summary` para registrar la retroalimentación de cada versión, los cambios realizados y los pendientes.

Para agregar un semestre, crea su página en `paginas/` y actualiza el menú compartido y los accesos de la portada. Marca la página activa con `aria-current="page"`.

GitHub Pages puede servir estos mismos archivos desde la raíz elegida, con la estructura de carpetas y `.nojekyll`. No requiere compilación.
