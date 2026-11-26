# Diseñador de catálogo DRENHISA

Abre `index.html` en Chrome (doble clic) o usa la versión publicada en Vercel. No requiere instalación.

## Qué incluye
- **Biblioteca de imágenes** (botón "🖼 Imágenes"): importa varias fotos a la vez (o arrástralas), ponles nombre y etiquetas, y elígelas desde ahí en cualquier página. Cada foto se importa una sola vez.
- **Página de producto**: título con palabras en color (`[[Agua Potable]]`), descripción, usos, tabla, listas de medidas, fotos y textos arrastrables.
- **Página con varios artículos**: medidas siempre en 2 columnas, filas que se llenan solas, alineación izquierda/derecha según la tolerancia, secciones, artículos de ancho completo y 3 estilos. Si no cabe, continúa en otra hoja.
- **Tamaño de la foto de cada artículo**: control deslizante o arrastrando el cuadrito azul de la esquina de la foto.
- **Miniaturas** de cada página y **Vista general** de todo el catálogo.
- Medidas: escribe `1/2`, `2 1/2` y se convierten a ½”, 2½”. Con valor: `1 | 50mts y 100mts`.
- **Exportar PNG (Canva)**: genera cada artículo (nombre + medidas, sin foto) como PNG transparente de alta resolución (3×, 4× o 6×), o cada hoja completa sin fotos ni títulos, cortada abajo donde termina el contenido y con las listas empezando siempre en el mismo punto, en un ZIP. Pensado para pegarlos en Canva sobre tus propios diseños.
- Se autoguarda en el navegador (incluida la biblioteca); usa **Guardar archivo** / **Abrir…** como respaldo.
- **Exportar PDF**: en el diálogo de impresión elige "Guardar como PDF", tamaño Carta, márgenes ninguno y activa "Gráficos de fondo".

Pendiente: portada y contraportada (el código base existe pero no está activado en la interfaz).

Las librerías para generar imágenes y ZIP (html2canvas y JSZip, licencia MIT) están en la carpeta `vendor/`; no hace falta internet para usarlas.
