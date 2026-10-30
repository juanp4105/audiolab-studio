# Rimay Studio

*Rimay* significa «hablar» y «la palabra» en kichwa. Rimay Studio (antes AudioLab Studio) es un editor de audio
multipista que funciona en el navegador, para cualquier persona que quiera aprender a editar y producir con sonido.
Importa WAV, MP3, M4A, OGG, OPUS y FLAC; edita con las herramientas Mover, Cuchilla, Mover en bloque y Selección
de tiempo; aplica efectos y favoritos; mezcla con medidores reales y exporta WAV o MP3.

- Página publicada: https://juanp4105.github.io/audiolab-studio/
- `index.html` es la compilación de un solo archivo (`npm run build:single` en el proyecto fuente).
  Para actualizarla, compile de nuevo y copie aquí el contenido de `dist-single/web/`.
- Los proyectos se guardan como archivos `.rimay` (los `.audiolab` anteriores se siguen abriendo). En Chrome y Edge,
  «Guardar como…» permite elegir la carpeta y Ctrl+S guarda directamente sobre el mismo archivo.
- Mientras haya cambios sin guardar, se guarda una copia automática en el navegador; si la ventana se cierra,
  al volver se ofrece recuperar el trabajo.
- Accesible con teclado y lector de pantalla (WCAG 2.2 AA): enlace para saltar a la línea de tiempo, menús con
  flechas, línea de tiempo operable sin ratón y avisos hablados.
- `manifest.webmanifest` y `sw.js` hacen que el sitio pueda instalarse como aplicación: una vez instalada,
  el sistema abre los archivos `.rimay` con Rimay Studio (doble clic) y funciona sin conexión.
- Licencias de los componentes incluidos: `LICENCIAS.txt`.
