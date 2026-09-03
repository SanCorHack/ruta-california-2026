# Europa en California 2026 — GitHub Pages

Carpeta lista para publicar la guía interactiva como web/PWA.

## Publicar en GitHub Pages

1. En GitHub, crea un repositorio nuevo (por ejemplo `ruta-california-2026`).
2. Sube **todo el contenido de esta carpeta a la raíz del repositorio**: `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` y la carpeta `icons`.
3. En el repositorio abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama **main** y la carpeta **/(root)** y pulsa **Save**.
6. Espera unos minutos. GitHub mostrará la URL publicada, normalmente `https://TU-USUARIO.github.io/ruta-california-2026/`.

## Usarla como app en iPhone

1. Abre la URL publicada en **Safari**.
2. Pulsa **Compartir**.
3. Elige **Añadir a pantalla de inicio**.
4. Abre el nuevo icono `Ruta California`.

Los favoritos, visitados, checklist y geolocalizaciones resueltas se guardan en el almacenamiento local del dispositivo/navegador. Si cambias de navegador o borras los datos del sitio, usa **Checklist → Exportar progreso** antes.

## Conexión

La interfaz y los datos del itinerario se pueden volver a abrir gracias al service worker tras una primera visita. El mapa base de OpenStreetMap y la resolución de ubicaciones nuevas siguen necesitando internet.

## Privacidad

GitHub Pages publica el sitio en una URL accesible por internet. No uses esta opción si quieres mantener el itinerario completamente privado sin añadir una capa de autenticación externa.
