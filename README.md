# Rimay Studio

*Rimay* significa «hablar» y «la palabra» en kichwa. Rimay Studio (antes AudioLab Studio) es un editor de audio
multipista que funciona en el navegador, para cualquier persona que quiera aprender a editar y producir con sonido.
Graba desde el micrófono (también sobre la música de otras pistas), dibuja líneas de volumen y panorama sobre cada clip, escribe guiones y graba cada línea, importa WAV, MP3, M4A, OGG, OPUS y FLAC; edita con las herramientas Mover, Cuchilla, Mover en bloque y Selección
de tiempo; aplica efectos y favoritos; mezcla con medidores reales y exporta WAV o MP3.

- Página publicada: https://juanp4105.github.io/audiolab-studio/
- Taller de guion: https://juanp4105.github.io/audiolab-studio/guion.html — escribir guiones de radio, pódcast y
  anuncios desde plantillas, con la duración en vivo, y enviarlos a Rimay Studio para grabar cada línea.
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
- Interfaz en español y en inglés: se elige según el idioma del navegador y se cambia en *Vista › Idioma / Language*
  (o con `?lang=en` / `?lang=es` en la dirección).
- Licencias de los componentes incluidos: `LICENCIAS.txt`.

## English

*Rimay* means “to speak” and “the word” in Kichwa, an Indigenous language of the Andes. Rimay Studio is a multitrack
audio editor that runs in the browser, for anyone who wants to learn audio editing and production: record from the
microphone (also over music on other tracks), draw volume and pan lines on each clip, write scripts and record each line,
import WAV, MP3, M4A, OGG, OPUS and FLAC, edit, apply effects, mix with real meters and export WAV or MP3. No accounts,
no cloud: your audio never leaves your computer.

- App: https://juanp4105.github.io/audiolab-studio/?lang=en
- Script Workshop: https://juanp4105.github.io/audiolab-studio/guion.html?lang=en
- The interface follows the browser language; switch it in *View › Idioma / Language*.
