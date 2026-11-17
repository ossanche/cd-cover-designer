
# CD Cover Designer

Aplicación web para diseñar, personalizar e imprimir carátulas traseras de CD y DVD.

CD Cover Designer permite crear carátulas personalizadas mediante un editor visual que trabaja con las dos caras de la carátula, ofreciendo herramientas para añadir imágenes, textos, formas y listas de canciones, así como configurar las dimensiones y los parámetros de impresión.

## Características

### Editor de carátulas
- Edición independiente de la Cara A (exterior) y Cara B (interior).
- Visualización de la cara opuesta en transparencia y espejo.
- Zoom y rotación de la vista.
- Posicionamiento y redimensionamiento de elementos.
- Sistema de capas para organizar los elementos.

### Elementos de diseño
- Inserción de textos personalizados.
- Importación de imágenes.
- Creación de formas y rectángulos.
- Personalización de fuentes, tamaños y colores.
- Control de alineación, rotación y opacidad.
- Creación automática de textos para los lomos.
- Generación de listas de canciones.

### Impresión y exportación
- Exportación de carátulas a PDF.
- Impresión de una o ambas caras.
- Compatibilidad con papel A4 y Carta.
- Configuración de impresión a doble cara.
- Ajuste de posición y alineación.
- Marcas de corte y doblez.

### Proyectos y plantillas
- Guardado de proyectos en formato JSON.
- Recuperación de proyectos anteriores.
- Importación de plantillas XML.
- Guardado automático en el almacenamiento local del navegador.

## Tecnologías

- HTML5
- CSS3
- JavaScript
- html2canvas
- jsPDF
- LocalStorage
- XML

## Instalación y uso

No requiere instalación ni servidor backend.

1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` en un navegador web.
3. Comienza a diseñar tu carátula.

Para utilizar la exportación PDF es necesario disponer de conexión a Internet para cargar las bibliotecas externas utilizadas por la aplicación.

## Publicación online

La aplicación puede alojarse gratuitamente mediante GitHub Pages.

Una vez activado GitHub Pages, estará disponible desde la dirección pública del repositorio.

## Formatos

| Función | Formato |
|---|---|
| Guardar proyecto | JSON |
| Plantillas | XML |
| Exportar | PDF |
| Imágenes | Formatos compatibles con el navegador |

---

**CD Cover Designer**  
Herramienta web para diseñar y preparar carátulas personalizadas de CD y DVD.
