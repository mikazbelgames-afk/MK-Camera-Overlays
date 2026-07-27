# MK Camera Overlays 1.0

Motor web para crear overlays transparentes de cámara y usarlos en TikTok LIVE Studio u OBS.

## Archivos

- `index.html`: editor.
- `live.html`: visor transparente para el live.
- `overlay.json`: configuración que carga el visor.

## Uso

1. Sube los tres archivos a un repositorio de GitHub Pages.
2. Abre `index.html` y crea tu overlay.
3. Presiona **Exportar overlay.json**.
4. Reemplaza el archivo `overlay.json` del repositorio por el nuevo.
5. En la fuente de navegador de tu programa de live usa:

```text
https://TU-USUARIO.github.io/TU-REPOSITORIO/live.html?config=overlay.json
```

6. Configura la fuente con el mismo tamaño del proyecto, por ejemplo `1080 × 1920`.

## Vista local

El botón **Vista en vivo** abre una previsualización usando el proyecto guardado en el navegador.

## Transparencia

La cuadrícula solo aparece en el editor. `live.html` mantiene el fondo completamente transparente.
