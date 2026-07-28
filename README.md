MK Camera Overlay Engine 2.2

Motor independiente para crear overlays transparentes de cámara y usarlos en TikTok LIVE Studio, OBS u otra fuente de navegador.

Archivos

index.html: editor visual.

live.html: visor transparente para la fuente web.

overlay.json: proyecto publicado.

URL del overlay

El editor vuelve a mostrar la URL calculada automáticamente. La estructura es:

https://TU-USUARIO.github.io/TU-REPOSITORIO/live.html?config=overlay.json

Después de editar, descarga el JSON y reemplaza overlay.json en GitHub. La URL no cambia.

Cambios de la versión 2.2

Recupera el campo y botón para copiar la URL del overlay.

Glow de imágenes basado en la transparencia real de la imagen.

Al quitar verde, azul, negro o un color personalizado, el glow sigue el contorno resultante en lugar del rectángulo completo.

Controles de intensidad y expansión del glow para imágenes.

Glow animado entre dos colores.

Loop maestro de 15 segundos.

Fuentes, partículas, presets, capas y reemplazo de imágenes.

Publicación en GitHub Pages

Sube los tres archivos principales a la raíz del repositorio, activa Pages desde la rama main y la carpeta / (root), y abre el editor con la URL principal del repositorio.
