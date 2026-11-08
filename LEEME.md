# Álvaro Gestión — app instalable

"Puerta de entrada" que permite instalar el programa de Google (web app de Apps Script) como una app en el móvil, con icono propio y pantalla completa. No contiene datos ni claves: cada persona entra con su enlace personal (`?t=...`), igual que ahora.

## Archivos
- `index.html`: abre el programa de Google dentro de la app y recuerda el enlace personal.
- `manifest.webmanifest`, `sw.js`, `icon-*.png`, `apple-touch-icon.png`: lo necesario para que el móvil ofrezca "Instalar".
- `logo-original.png`: logo de Álvaro Mantenimiento Ibiza. Los iconos son un recorte de su emblema (tejado, llave y sol) sobre fondo blanco.

## Si cambia la dirección del programa de Google
Editar la constante `EXEC` en `index.html` (misma dirección `.../exec` de la implementación).

## Publicación (pendiente)
Pensada para GitHub Pages (gratis, requiere repositorio público). Esta carpeta es independiente del repositorio del programa para que `clasp push` nunca la suba a Google.

