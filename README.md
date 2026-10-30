# AudioLab Studio

Editor de audio multipista que funciona en el navegador: importa WAV y MP3, edita con las
herramientas Mover, Cuchilla, Mover en bloque y Selección de tiempo, aplica efectos y favoritos,
mezcla con medidores reales y exporta WAV o MP3.

- Página publicada: https://juanp4105.github.io/audiolab-studio/
- `index.html` es la compilación de un solo archivo (`npm run build:single` en el proyecto fuente).
  Para actualizarla, compile de nuevo y copie aquí el contenido de `dist-single/web/`.
- Los proyectos se guardan como archivos `.audiolab`. En Chrome y Edge, «Guardar como…» permite elegir la carpeta
  y Ctrl+S guarda directamente sobre el mismo archivo.
- `manifest.webmanifest` y `sw.js` hacen que el sitio pueda instalarse como aplicación: una vez instalada,
  el sistema abre los archivos `.audiolab` con AudioLab Studio (doble clic) y funciona sin conexión.
- Licencias de los componentes incluidos: `LICENCIAS.txt`.
