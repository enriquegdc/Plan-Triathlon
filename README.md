# Plan de triatlón 30 semanas - PWA offline

Esta carpeta contiene una versión instalable como PWA del plan.

Archivos principales:
- `index.html`: app del plan.
- `manifest.json`: datos de instalación.
- `sw.js`: cache offline.
- `icons/`: iconos de la app.

Uso recomendado:
1. Sube esta carpeta a un alojamiento HTTPS como GitHub Pages, Netlify o Vercel.
2. Abre la URL desde el móvil.
3. En iPhone: Safari → Compartir → Añadir a pantalla de inicio.
4. En Android: Chrome → menú ⋮ → Instalar app o Añadir a pantalla de inicio.
5. Abre la app una vez con conexión; después funcionará offline.

Nota: por seguridad, los navegadores no permiten que el modo PWA/offline funcione bien si abres el archivo directamente como `file://`. Para instalarla como app necesitas servirla desde HTTPS o desde `localhost`.
