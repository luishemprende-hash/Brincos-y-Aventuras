# Brinco y Aventuras 3D — versión 2

## Archivos
- `index.html`: juego completo.
- `manifest.webmanifest`: metadatos para instalar como aplicación web.
- `sw.js`: caché para uso sin conexión después de la primera visita.
- `icon-192.png` y `icon-512.png`: iconos de la app.

## Publicarlo gratis con GitHub Pages
1. Crea o inicia sesión en https://github.com
2. Crea un repositorio público, por ejemplo `brinco-aventuras`.
3. Sube todos los archivos de esta carpeta a la raíz del repositorio.
4. Abre **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**, elige `main` y `/ (root)`, y pulsa **Save**.
6. Espera a que GitHub Pages publique el sitio. El enlace será similar a `https://TU-USUARIO.github.io/brinco-aventuras/`.
7. Abre ese enlace en Chrome en Android. Usa el botón **Instalar** si aparece, o menú ⋮ → **Instalar aplicación** / **Añadir a pantalla principal**.

## Alternativa sencilla
También puedes subir estos archivos a un servicio de hosting estático como Netlify Drop: https://app.netlify.com/drop

## Notas
- La instalación PWA necesita que el sitio esté servido por HTTPS (GitHub Pages y Netlify lo proporcionan).
- El progreso, el récord y los niveles desbloqueados se guardan localmente en el navegador del mismo dispositivo.
- El sonido se activa después de una interacción del usuario, como suele exigir Android/Chrome.
- Es un juego original inspirado en el género de plataformas, no utiliza personajes, música ni recursos de Mario Bros.
