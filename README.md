# Melancoholic — sitio personal

## Publicar en GitHub Pages
1. Sube el contenido de esta carpeta a la raíz de tu repositorio.
2. Reemplaza tu `index.html` anterior por este. Conserva `playlist.json` (es tu respaldo Wimpy actual).
3. En Settings → Pages, usa Deploy from a branch → `main` → `/(root)`.

## Contenido editable
- `playlist.json`: tus playlists de Wimpy. Si agregas más playlists al respaldo, aparecerán en el selector de Música.
- `gallery.json`: imágenes y pies de foto de Galería. Sube los archivos a `assets/gallery/` y escribe su ruta en este JSON.
- `diary.json`: pequeñas entradas personales.
- `library.json`: libros, juegos, arte y otros descubrimientos.
- `writing.json`: poemas, relatos y textos.

## Añadir imágenes a Galería
GitHub Pages no permite que los visitantes suban archivos directamente desde la página. Para añadir imágenes tú mismo: abre el repositorio → Add file → Upload files, sube las imágenes a `assets/gallery/`, confirma el commit y agrega sus rutas en `gallery.json`.

## Formato de ejemplo
En `gallery.json`: `{"image":"assets/gallery/mi-foto.jpg","caption":"Una tarde cualquiera"}`

El sitio es público. No publiques datos privados ni contraseñas en los JSON. Los cambios pueden tardar unos minutos en aparecer.
